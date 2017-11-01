# tmux-for-param-ishan


Just do the following steps for running proxy on param ishan and installing tmux

1
Add proxy details to .bashrc in the following format
export ALL_PROXY=http://usrname:passwd@ip:port

export HTTP_PROXY=$ALL_PROXY

export HTTPS_PROXY=$ALL_PROXY

export FTP_PROXY=$ALL_PROXY

export RSYNC_PROXY=$ALL_PROXY

export http_proxy=$ALL_PROXY

export https_proxy=$ALL_PROXY

export ftp_proxy=$ALL_PROXY

export rsync_proxy=$ALL_PROXY

2
hcmod 755 sun.sh

3
./run.sh

4 tmux successfully installs on the system
