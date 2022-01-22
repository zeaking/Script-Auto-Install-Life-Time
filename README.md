# Script-Auto-Install-Life-Time
Step 1
apt update && apt upgrade -y && update-grub && sleep 2 && reboot

Step 2
apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/syfqsamvpn/scriptvps/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
