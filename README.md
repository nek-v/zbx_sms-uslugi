zbx_sms-uslugi
==============

Zabbix шаблон для мониторинга баланса сервиса СМС-Услуги

## Установка

* Скопируйте файлы в стандартные каталоги.
* Отредактируйте в скриптах ```/usr/lib/zabbix/alertscripts/sms-uslugi``` и ```/usr/lib/zabbix/externalscripts/sms-uslugi``` переменные:
```php
//
$login = 'your login';
//
$password = 'your password';
```
* Сделайте их исполняемыми
```bash
sudo -i
chown -R zabbix:zabbix /usr/lib/zabbix
find /usr/lib/zabbix/ -type f -iname "sms-uslugi" -exec chmod +x {} \;
```

## Ссылки
* [Zabbix](https://www.zabbix.com/documentation/3.0/ru/start)
* [СМС-Услуги](http://sms-uslugi.ru)

