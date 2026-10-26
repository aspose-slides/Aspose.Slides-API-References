---
title: TcpListener()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр.
type: docs
weight: 53
url: /ru/system.net.sockets/tcplistener/tcplistener/
---
## TcpListener::TcpListener(System::SharedPtr\<IPEndPoint\>) конструктор


Создаёт новый экземпляр.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPEndPoint> localEP)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Локальная конечная точка, к которой должен быть привязан сокет слушателя. |

## TcpListener::TcpListener(System::SharedPtr\<IPAddress\>, int32_t) конструктор


Создаёт новый экземпляр.

```cpp
System::Net::Sockets::TcpListener::TcpListener(System::SharedPtr<IPAddress> localaddr, int32_t port)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localaddr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Локальный IP-адрес. |
| port | **int32_t** | Номер порта для прослушивания. |

## TcpListener::TcpListener(int32_t) конструктор


Создаёт новый экземпляр.

```cpp
System::Net::Sockets::TcpListener::TcpListener(int32_t port)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| port | **int32_t** | Номер порта для прослушивания. |

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPEndPoint](../../../system.net/ipendpoint/)
* Класс [TcpListener](../)
* Класс [IPAddress](../../../system.net/ipaddress/)
* Пространство имён [System::Net::Sockets](../../)
* Библиотека [Aspose.Slides](../../../)