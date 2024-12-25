## Одно из решений:
Создать .bash скрипт и прописать в нём следующий код:
```
#!/bin/bash
cp /var/log/syslog ~/syslog_backup.log
grep "error" /var/log/syslog > ~/error_logs.txt
```
