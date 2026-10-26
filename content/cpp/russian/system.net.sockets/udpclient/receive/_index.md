---
title: Receive()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает датаграмму, отправленную сервером.
type: docs
weight: 92
url: /ru/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) метод

Возвращает датаграмму, отправленную сервером.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | [IPEndPoint](../../../system.net/ipendpoint/) представляет удалённый хост, с которого были отправлены данные. |

### Возвращаемое значение

Массив байтов, в который будут помещены полученные данные.

## Смотрите также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPEndPoint](../../../system.net/ipendpoint/)
* Класс [UdpClient](../)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)