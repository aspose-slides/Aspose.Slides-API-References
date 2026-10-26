---
title: UdpClient()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új példányt a UdpClient osztályból.
type: docs
weight: 27
url: /hu/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() konstruktor

Inicializál egy új példányt a [UdpClient](../) osztályból.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) konstruktor

Inicializál egy új példányt a [UdpClient](../) osztályból.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | érték, amely meghatározza a socket címzési sémáját. |

## UdpClient::UdpClient(int32_t) konstruktor

Inicializál egy új példányt a [UdpClient](../) osztályból.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| port | **int32_t** | a helyi portszám, amelyről kommunikálni kíván. |

## UdpClient::UdpClient(int32_t, AddressFamily) konstruktor

Inicializál egy új példányt a [UdpClient](../) osztályból.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| port | **int32_t** | a helyi portszám, amelyről kommunikálni kíván. |
| family | [AddressFamily](../../addressfamily/) | érték, amely meghatározza a socket címzési sémáját. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Inicializál egy új példányt a [UdpClient](../) osztályból. param local EP a helyi végpont, amelyhez a UDP kapcsolatot köti.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) konstruktor

Létrehoz egy új példányt a [UdpClient](../) osztályból, és csatlakozik a megadott távoli DNS-kiszolgálóhoz a megadott porton.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | A távoli DNS-kiszolgáló neve, amelyhez csatlakozni kíván. |
| port | **int32_t** | A helyi portszám, amelyről kommunikálni kíván. |

## Lásd még

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)