# 3.7_2
# 1
```
vagrant@vagrant:~$ ifconfig
eth0: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 10.0.2.15  netmask 255.255.255.0  broadcast 10.0.2.255
        inet6 fe80::a00:27ff:feb1:285d  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:b1:28:5d  txqueuelen 1000  (Ethernet)
        RX packets 1609  bytes 1241846 (1.2 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 787  bytes 104004 (104.0 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 14  bytes 1354 (1.3 KB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 14  bytes 1354 (1.3 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0
```
```
C:\Users\pashicop>ipconfig /all

Настройка протокола IP для Windows

   Имя компьютера  . . . . . . . . . : PaShi
   Основной DNS-суффикс  . . . . . . :
   Тип узла. . . . . . . . . . . . . : Гибридный
   IP-маршрутизация включена . . . . : Нет
   WINS-прокси включен . . . . . . . : Нет

Адаптер Ethernet Ethernet:

   Состояние среды. . . . . . . . : Среда передачи недоступна.
   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Физический адрес. . . . . . . . . : A0-B3-CC-45-3E-53
   DHCP включен. . . . . . . . . . . : Да
   Автонастройка включена. . . . . . : Да

Адаптер Ethernet VirtualBox Host-Only Network:

   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Физический адрес. . . . . . . . . : 0A-00-27-00-00-06
   DHCP включен. . . . . . . . . . . : Нет
   Автонастройка включена. . . . . . : Да
   Локальный IPv6-адрес канала . . . : fe80::6843:97a5:caf8:bcf6%6(Основной)
   IPv4-адрес. . . . . . . . . . . . : 192.168.56.1(Основной)
   Маска подсети . . . . . . . . . . : 255.255.255.0
   Основной шлюз. . . . . . . . . :
   IAID DHCPv6 . . . . . . . . . . . : 755630119
   DUID клиента DHCPv6 . . . . . . . : 00-01-00-01-29-2B-1F-5B-A0-B3-CC-45-3E-53
   DNS-серверы. . . . . . . . . . . : fec0:0:0:ffff::1%1
                                       fec0:0:0:ffff::2%1
                                       fec0:0:0:ffff::3%1
   NetBios через TCP/IP. . . . . . . . : Включен

Адаптер беспроводной локальной сети Подключение по локальной сети* 11:

   Состояние среды. . . . . . . . : Среда передачи недоступна.
   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #3
   Физический адрес. . . . . . . . . : 40-A3-CC-2B-D0-7D
   DHCP включен. . . . . . . . . . . : Да
   Автонастройка включена. . . . . . : Да

Адаптер беспроводной локальной сети Подключение по локальной сети* 12:

   Состояние среды. . . . . . . . : Среда передачи недоступна.
   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #4
   Физический адрес. . . . . . . . . : 42-A3-CC-2B-D0-7C
   DHCP включен. . . . . . . . . . . : Да
   Автонастройка включена. . . . . . : Да

Адаптер беспроводной локальной сети Беспроводная сеть 2:

   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : Intel(R) Dual Band Wireless-AC 8265
   Физический адрес. . . . . . . . . : 40-A3-CC-2B-D0-7C
   DHCP включен. . . . . . . . . . . : Да
   Автонастройка включена. . . . . . : Да
   Локальный IPv6-адрес канала . . . : fe80::f99d:8137:8803:276f%23(Основной)
   IPv4-адрес. . . . . . . . . . . . : 192.168.0.11(Основной)
   Маска подсети . . . . . . . . . . : 255.255.255.0
   Аренда получена. . . . . . . . . . : 13 февраля 2022 г. 16:44:32
   Срок аренды истекает. . . . . . . . . . : 14 февраля 2022 г. 23:17:00
   Основной шлюз. . . . . . . . . : fe80::1%23
                                       192.168.0.1
   DHCP-сервер. . . . . . . . . . . : 192.168.0.1
   IAID DHCPv6 . . . . . . . . . . . : 356557772
   DUID клиента DHCPv6 . . . . . . . : 00-01-00-01-29-2B-1F-5B-A0-B3-CC-45-3E-53
   DNS-серверы. . . . . . . . . . . : fe80::1%23
                                       192.168.0.1
   NetBios через TCP/IP. . . . . . . . : Включен

Адаптер Ethernet Сетевое подключение Bluetooth 2:

   Состояние среды. . . . . . . . : Среда передачи недоступна.
   DNS-суффикс подключения . . . . . :
   Описание. . . . . . . . . . . . . : Bluetooth Device (Personal Area Network) #2
   Физический адрес. . . . . . . . . : 40-A3-CC-2B-D0-80
   DHCP включен. . . . . . . . . . . : Да
   Автонастройка включена. . . . . . : Да
```
# 2
lldp - link layer desription protocol 
`vagrant@vagrant:~$ sudo apt install lldpd`
# 3
```
auto eth0.22
iface eth0.22 inet static
        address 10.1.4.8
        netmask 255.0.0.0
        vlan_raw_device eth0
```
