# ipip.net BestTrace for Linux

https://www.ipip.net/product/client.html

# How to install(如何安装)

### X86 Linux(64Bit)

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttrace -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/sbin/besttrace
sudo chmod +x /usr/sbin/besttrace
```

### X86 Linux(32Bit)

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttrace32 -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/sbin/besttrace
sudo chmod +x /usr/sbin/besttrace
```

### Arm Linux

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttracearm -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/sbin/besttrace
sudo chmod +x /usr/sbin/besttrace
```

### BSD Linux(64Bit)

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttracebsd -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/sbin/besttrace
sudo chmod +x /usr/sbin/besttrace
```

### BSD Linux(32Bit)

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttracebsd32 -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/sbin/besttrace
sudo chmod +x /usr/sbin/besttrace
```

### Mac

```
wget https://raw.githubusercontent.com/royzheng/besttrace_linux/main/besttracemac -O /tmp/besttrace
sudo mv /tmp/besttrace /usr/local/sbin/besttrace
sudo chmod +x /usr/local/sbin/besttrace
```

# Usage(如何使用)

```
sudo besttrace 183.6.248.88
```
