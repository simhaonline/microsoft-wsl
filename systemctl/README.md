# init-systemd
Script to enable systemd support on current WSL2 images. 

# Usage
### Run the script and commands
```sh
git clone https://github.com/simhaonline/microsoft-wsl.git
cd microsoft-wsl/systemctl/
sudo bash init-systemd
# Enter your password and wait until the script has finished
cmd.exe /C setx WSLENV BASH_ENV/u
cmd.exe /C setx BASH_ENV /etc/bash.bashrc
rm -rf microsoft-wsl
```
### Then restart the shell and try running systemctl
```sh
systemctl
```
# Have fun using systemd on WSL2. 
