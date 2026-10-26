---
title: Connect()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает соединение с указанной удалённой конечной точкой.
type: docs
weight: 560
url: /ru/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) метод


Устанавливает соединение с указанной удалённой конечной точкой.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | Удалённая конечная точка. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) метод


Устанавливает соединение с указанной удалённой конечной точкой.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP-адрес удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |

## Socket::Connect(String, int32_t) метод


Устанавливает соединение с указанной удалённой конечной точкой.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Имя удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) метод


Устанавливает соединение с указанной удалённой конечной точкой.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-адреса удалённого хоста. |
| port | **int32_t** | Номер порта удалённого хоста. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)