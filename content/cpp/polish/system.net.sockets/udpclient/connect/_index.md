---
title: Connect()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Nawiązuje połączenie z określonym portem na określonym hoście.
type: docs
weight: 66
url: /pl/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metoda

Nawiązuje połączenie z określonym portem na określonym hoście.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Nazwa zdalnego hosta DNS, z którym zamierzasz się połączyć. |
| port | **int32_t** | Lokalny numer portu, z którego zamierzasz komunikować się. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda

Nawiązuje połączenie z hostem pod określonym adresem na określonym porcie.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | [IPAddress](../../../system.net/ipaddress/) zdalnego hosta, do którego mają być wysyłane dane. |
| port | **int32_t** | Lokalny numer portu, z którego zamierzasz komunikować się. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metoda

Nawiązuje połączenie z zdalnym punktem końcowym.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | punkt końcowy, do którego wiążesz połączenie UDP. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [UdpClient](../)
* Klasa [IPAddress](../../../system.net/ipaddress/)
* Klasa [IPEndPoint](../../../system.net/ipendpoint/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)