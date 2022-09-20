# wslnet
A simple tool to forward the TCP ports of WSL 2 services to the host OS

![alt text](https://github.com/rvizx/wslnet/blob/main/ss.png?raw=true)


visit [releases](https://github.com/rvizx/wslnet/releases) to download the latest version of wslnet.

# usage

```
--help    - show help info and exit.
--info    - shows information about the forwarded ports.
--reset   -   all     - reset all previous port forwarding rules. (example : wslnet --reset all)
          -   <port>  - reset only the specified port. (example : wslnet --reset 9001)
--forward - forward ports. ( example: wslnet.exe --forward 9001,7777,31337 )
```
