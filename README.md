# Привязка доменного имени к ВМ с веб-сервером

Привяжете собственное доменное имя к виртуальной машине [Yandex Compute Cloud](https://yandex.cloud/ru/docs/compute/) с веб-сервером. Доменное имя может быть зарегистрировано у любого регистратора доменных имен.

Виртуальная машина будет создана из публичного образа [LAMP](https://yandex.cloud/ru/marketplace/products/yc/lamp) с предустановленным веб-сервером [Apache HTTP Server](https://httpd.apache.org). Также для руководства подойдет публичный образ [LEMP](https://yandex.cloud/ru/marketplace/products/yc/lemp) с веб-сервером [NGINX](https://www.nginx.com).

В качестве примера используется доменное имя `example.com`, которое будет связано с IP-адресом виртуальной машины с помощью [записей DNS](https://yandex.cloud/ru/docs/dns/concepts/resource-record) в [Yandex Cloud DNS](https://yandex.cloud/ru/docs/dns/).

Подготовка инфраструктуры для привязки доменного имени к ВМ с веб-сервером с помощью Terraform описана в [практическом руководстве](https://yandex.cloud/ru/docs/tutorials/web/bind-domain-vm/), необходимые для настройки конфигурационные файлы `bind-domain-to-vm.auto.tfvars` и `bind-domain-to-vm.tf` расположены в этом репозитории.
