# GuestShell_CookBook

This repo provides tested usecases for Cisco GuestShell.
Guestshell is a virtualized Linux-based environment. In fact it is CentOS Stream 8 with restricted functionality.
All usecesaes was tested on C9300-24UX switch with 17.12.3 IOSXE.

# UseCases
0. setup.txt - Initial setup of C9300 and GuestShell common for all following usecases
1. speedtest.txt - To measure Internet upload/download directly from switch
2. scan.txt - To scan TCP/UDP ports from switch
3. iperf.txt - To measure bandwith between switch and another iperf peer
4. file_transfers.txt - To transfer files via different protocols (FTP, SFTP, SCP, TFTP)
5. http.txt - To run simple static web page on switch or serve files via http
6. jumphost.txt - Tu use switch as jumphost for http/ssh