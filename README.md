ftp-filedrop
============

Quick script for dropping files into a FTP folder

Usage
---------------------
### Dropping a file into the folder

**Limitation** It needs an extension for now

```bash
export ftpserver='hostname' ; export user='username' ; export pass='Password' ; export file='filename.ext' ; export dir='/dest/filepath'; ./drop.rb
```

### Getting a list only

```bash
export ftpserver='hostname' ; export user='username' ; export pass='Password' ; export file='listonly' ; export dir='/dest/filepath'; ./drop.rb
```