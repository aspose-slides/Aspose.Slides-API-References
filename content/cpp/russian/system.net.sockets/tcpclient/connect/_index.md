---
title: Connect()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает соединение с указанным удалённым хостом.
type: docs
weight: 248
url: /ru/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) метод

Устанавливает соединение с указанным удалённым хостом.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Имя удалённого хоста для подключения. |
| port | **int32_t** | Порт удалённого хоста для подключения. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) метод

Устанавливает соединение с указанным удалённым хостом.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP-адрес удалённого хоста. |
| port | **int32_t** | Порт удалённого хоста для подключения. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) метод

Устанавливает соединение с указанным удалённым хостом.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Удалённый хост для подключения. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) метод

Устанавливает соединение с указанным удалённым хостом.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-адреса удалённого хоста. |
| port | **int32_t** | Порт удалённого хоста для подключения. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [TcpClient](../)
* Класс [IPAddress](../../../system.net/ipaddress/)
* Класс [IPEndPoint](../../../system.net/ipendpoint/)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)