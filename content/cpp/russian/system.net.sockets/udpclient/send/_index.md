---
title: Send()
second_title: Справочник API Aspose.Slides для C++
description: Отправляет UDP-датаграмму на хост, указанный удалённой конечной точкой.
type: docs
weight: 79
url: /ru/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) метод


Отправляет UDP-датаграмму на хост, указанный удалённой конечной точкой.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив типа [Byte](../../../system/byte/) для отправки |
| bytes | **int32_t** | Количество байтов в датаграмме. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Объект [IPEndPoint](../../../system.net/ipendpoint/), представляющий хост и порт, куда будет отправлена датаграмма. |

### Возвращаемое значение

Количество отправленных байтов.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) метод


Отправляет UDP-датаграмму на указанный порт указанного удалённого хоста.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив типа [Byte](../../../system/byte/) для отправки |
| bytes | **int32_t** | Количество байтов в датаграмме. |
| hostname | [String](../../../system/string/) | Имя удалённого хоста. |
| port | **int32_t** | Номер удалённого порта. |

### Возвращаемое значение

Количество отправленных байтов.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) метод


Отправляет UDP-датаграмму на удалённый хост.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив типа [Byte](../../../system/byte/) для отправки. |
| bytes | **int32_t** | Количество байтов в датаграмме. |

### Возвращаемое значение

Количество отправленных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)