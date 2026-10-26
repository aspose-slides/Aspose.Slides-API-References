---
title: UdpClient()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует новый экземпляр класса UdpClient.
type: docs
weight: 27
url: /ru/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() конструктор

Инициализирует новый экземпляр класса [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) конструктор

Инициализирует новый экземпляр класса [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | значение, указывающее схему адресации сокета. |

## UdpClient::UdpClient(int32_t) конструктор

Инициализирует новый экземпляр класса [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| port | **int32_t** | локальный номер порта, из которого вы собираетесь передавать данные. |

## UdpClient::UdpClient(int32_t, AddressFamily) конструктор

Инициализирует новый экземпляр класса [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| port | **int32_t** | локальный номер порта, из которого вы собираетесь передавать данные. |
| family | [AddressFamily](../../addressfamily/) | значение, указывающее схему адресации сокета. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) конструктор

Инициализирует новый экземпляр класса [UdpClient](../). param local EP локальная конечная точка, к которой вы привязываете UDP-соединение.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) конструктор

Создает новый экземпляр класса [UdpClient](../) и подключается к указанному удаленному хосту на указанном порту.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | имя удаленного DNS-хоста, к которому вы собираетесь подключиться. |
| port | **int32_t** | локальный номер порта, из которого вы собираетесь передавать данные. |

## См. также

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [UdpClient](../)
* Класс [IPEndPoint](../../../system.net/ipendpoint/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)