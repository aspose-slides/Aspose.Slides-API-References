---
title: UdpClient()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av UdpClient-klassen.
type: docs
weight: 27
url: /sv/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() konstruktor

Initierar en ny instans av klassen [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) konstruktor

Initierar en ny instans av klassen [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | värde som anger adressschema för socketen. |

## UdpClient::UdpClient(int32_t) konstruktor

Initierar en ny instans av klassen [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| port | **int32_t** | det lokala portnumret från vilket du avser att kommunicera. |

## UdpClient::UdpClient(int32_t, AddressFamily) konstruktor

Initierar en ny instans av klassen [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| port | **int32_t** | det lokala portnumret från vilket du avser att kommunicera. |
| family | [AddressFamily](../../addressfamily/) | värde som anger adressschema för socketen. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) konstruktor

Initierar en ny instans av klassen [UdpClient](../). param local EP den lokala slutpunkten som du binder UDP-anslutningen till.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) konstruktor

Skapar en ny instans av klassen [UdpClient](../) och ansluter till den angivna fjärrvärden på den angivna porten.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Namnet på den fjärr-DNS-värd du avser att ansluta till. |
| port | **int32_t** | det lokala portnumret från vilket du avser att kommunicera. |

## Se även

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [UdpClient](../)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)