# mikrotik-fail2ban

Fail2ban for MikroTik RouterOS
You need create log:

* /system logging action add name=l2tplogin target=memory
* /system logging action add name=sstplogin target=memory
* /system logging action add name=ovpnlogin target=memory

For firewall rules use address lists:
* badl2tp
* badip
* badovpn
