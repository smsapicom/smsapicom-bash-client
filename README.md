Sending SMS message from Linux Terminal
===========

Bash client which allows you to send SMS message and manage your account in SMSAPI.com

```bash
$ ./smsapi sms send --username LOGIN --password PASS 48xxxyyyzzz,48zzzyyyxxx "Hello world"
```

```bash
$ ./smsapi 
Usage: smsapi sms send [OPTIONS] <to> <message>
Options:
  --username <string>
  --password <password>  md5 api password

  --from <string>        Sender name
  --encoding <string>    Message encoding (default:utf8)

  -f, --fast <0|1>       Fast

  -n, --normalize <0|1>  Normalize message
  -v                     Verbose
```

config file ".smsapi.rc" may be placed in workspace folder or in user's home folder

=======

