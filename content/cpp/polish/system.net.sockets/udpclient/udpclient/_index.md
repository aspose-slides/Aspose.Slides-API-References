---
title: UdpClient()
second_title: Odniesienie API Aspose.Slides dla C++
description: Inicjalizuje nową instancję klasy UdpClient.
type: docs
weight: 27
url: /pl/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() konstruktor

Inicjalizuje nową instancję klasy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) konstruktor

Inicjalizuje nową instancję klasy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | wartość określająca schemat adresowania gniazda. |

## UdpClient::UdpClient(int32_t) konstruktor

Inicjalizuje nową instancję klasy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| port | **int32_t** | lokalny numer portu, z którego zamierzasz komunikować się. |

## UdpClient::UdpClient(int32_t, AddressFamily) konstruktor

Inicjalizuje nową instancję klasy [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| port | **int32_t** | lokalny numer portu, z którego zamierzasz komunikować się. |
| family | [AddressFamily](../../addressfamily/) | wartość określająca schemat adresowania gniazda. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Inicjalizuje nową instancję klasy [UdpClient](../). param local EP lokalny punkt końcowy, do którego podłączasz połączenie UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) konstruktor

Tworzy nową instancję klasy [UdpClient](../) i łączy się z określonym zdalnym hostem na określonym porcie.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | nazwa zdalnego hosta DNS, z którym zamierzasz się połączyć. |
| port | **int32_t** | lokalny numer portu, z którego zamierzasz komunikować się. |

## Zobacz także

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [UdpClient](../)
* Klasa [IPEndPoint](../../../system.net/ipendpoint/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)