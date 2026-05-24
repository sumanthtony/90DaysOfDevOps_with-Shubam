# Linux Commands Cheat Sheet

## Process Management Commands

| Command | Usage |
|---------|--------|
| `ps -ef` | Show all running processes |
| `top` | Monitor system processes live |
| `htop` | Interactive process viewer |
| `kill PID` | Stop a process using PID |
| `kill -9 PID` | Force kill a process |
| `jobs` | Show background jobs |
| `bg` | Run job in background |
| `fg` | Bring background job to foreground |
| `uptime` | Show system uptime and load |
| `free -h` | Check memory usage |

---

## File System Commands

| Command | Usage |
|---------|--------|
| `pwd` | Show current directory |
| `ls -l` | List files with details |
| `cd directory` | Change directory |
| `mkdir test` | Create new directory |
| `touch file.txt` | Create empty file |
| `cp file1 file2` | Copy files |
| `mv file1 file2` | Move or rename file |
| `rm -rf folder` | Delete directory forcefully |
| `find / -name file.txt` | Search file in system |
| `du -sh *` | Check folder sizes |
| `df -h` | Check disk space usage |
| `cat file.txt` | View file content |
| `tail -f logs.txt` | Monitor logs live |
| `grep "error" file.txt` | Search text inside file |

---

## Networking Troubleshooting Commands

| Command | Usage |
|---------|--------|
| `ping google.com` | Check network connectivity |
| `ip addr` | Show IP address details |
| `curl google.com` | Test website/API response |
| `dig google.com` | Check DNS records |
| `netstat -tulnp` | Show open ports |
| `ss -tulnp` | Display listening ports |
| `hostname -I` | Show system IP address |
| `traceroute google.com` | Track network path |
| `wget URL` | Download files from internet |

---

## Useful Log Commands

| Command | Usage |
|---------|--------|
| `journalctl -xe` | View system logs |
| `dmesg` | Show kernel logs |
| `tail -100 /var/log/syslog` | View recent logs |
