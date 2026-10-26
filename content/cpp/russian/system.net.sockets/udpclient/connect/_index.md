---
title: Connect()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает соединение с указанным портом на указанном хосте.
type: docs
weight: 66
url: /ru/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) метод

Устанавливает соединение с указанным портом на указанном хосте.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Имя удалённого DNS-хоста, к которому вы хотите подключиться. |
| port | **int32_t** | Номер локального порта, с которого вы собираетесь передавать данные. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) метод

Устанавливает соединение с хостом по указанному адресу и порту.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) удалённого хоста, которому отправляются данные. |
| port | **int32_t** | Номер локального порта, с которого вы собираетесь передавать данные. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) метод

Устанавливает соединение с удалённой конечной точкой.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | конечная точка, к которой вы привязываете UDP-соединение. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)