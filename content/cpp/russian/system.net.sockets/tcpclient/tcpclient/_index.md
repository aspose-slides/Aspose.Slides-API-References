---
title: TcpClient()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 235
url: /ru/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) конструктор

Создает новый экземпляр.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Точка подключения, к которой привязан сокет. |

## TcpClient::TcpClient() конструктор

Создает новый экземпляр.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) конструктор

Создает новый экземпляр.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Семейство адресов. |

## TcpClient::TcpClient(String, int32_t) конструктор

Создает новый экземпляр.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Имя удалённого хоста для подключения. |
| port | **int32_t** | Порт удалённого хоста для подключения. |

## См. также

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPEndPoint](../../../system.net/ipendpoint/)
* Класс [TcpClient](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)