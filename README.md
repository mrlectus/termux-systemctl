# Description
Systemctl for termux.

## Warning
only use if you've installed termux-service.

```
$ pkg install termux-service
```

# Usage
Make sure you change permission of executable before moving to path.

```
$ cd systemctl_termux
```

```
$ chmod +x systemctl && cp systemctl $HOME/.local/bin
```

## start service
```
$ systemctl start mysqld
```

## stop service
```
$ systemctl stop mysqld
```

## restart service
```
$ systemctl restart service
```

## check status
```
$ systemctl status mysqld
```
