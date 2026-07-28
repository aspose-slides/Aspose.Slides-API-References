---
title: Send()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wysyła datagram UDP do hosta w zdalnym punkcie końcowym.
type: docs
weight: 79
url: /pl/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) metoda


Wysyła datagram UDP do hosta w zdalnym punkcie końcowym.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica typu [Byte](../../../system/byte/) do wysłania |
| bytes | **int32_t** | Liczba bajtów w datagramie. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Obiekt [IPEndPoint](../../../system.net/ipendpoint/) reprezentujący host i port, do którego ma zostać wysłany datagram. |

### Wartość zwracana

Liczba bajtów, które zostały wysłane.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) metoda


Wysyła datagram UDP na określony port na określonym zdalnym hoście.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica typu [Byte](../../../system/byte/) do wysłania |
| bytes | **int32_t** | Liczba bajtów w datagramie. |
| hostname | [String](../../../system/string/) | Nazwa zdalnego hosta. |
| port | **int32_t** | Numer zdalnego portu. |

### Wartość zwracana

Liczba bajtów, które zostały wysłane.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) metoda


Wysyła datagram UDP do zdalnego hosta.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tablica typu [Byte](../../../system/byte/) do wysłania. |
| bytes | **int32_t** | Liczba bajtów w datagramie. |

### Wartość zwracana

Liczba bajtów, które zostały wysłane.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPEndPoint](../../../system.net/ipendpoint/)
* Klasa [UdpClient](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Net::Sockets](../../)
* Biblioteka [Aspose.Slides](../../../)