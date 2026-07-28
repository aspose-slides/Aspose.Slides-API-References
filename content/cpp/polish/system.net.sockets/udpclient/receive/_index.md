---
title: Receive()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca datagram wysłany przez serwer.
type: docs
weight: 92
url: /pl/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) metoda

Zwraca datagram wysłany przez serwer.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | Obiekt [IPEndPoint](../../../system.net/ipendpoint/) reprezentujący zdalny host, z którego dane zostały wysłane. |

### Wartość zwracana

Tablica bajtów, do której zostaną przypisane odebrane dane.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPEndPoint](../../../system.net/ipendpoint/)
* Klasa [UdpClient](../)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)