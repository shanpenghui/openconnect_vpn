# openconnect_vpn
Use cisco vpn account with openconnect

# Usage

## 1. Install packages

```shell
sudo apt update && apt install openconnect network-manager-openconnect-gnome vpnc
```

## 2. Start with cmd

```shell
sudo openconnect -u <user_name> -b <vpn_address>
```

Then you should enter your password and it will works.