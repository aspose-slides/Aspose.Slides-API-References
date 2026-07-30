---
title: GetSocketOption()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací hodnotu, která odpovídá zadanému názvu volby.
type: docs
weight: 729
url: /cs/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) metoda


Vrací hodnotu, která odpovídá zvolenému názvu volby.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Úroveň socketové volby. |
| optionName | [SocketOptionName](../../socketoptionname/) | Název volby. |

### Návratová hodnota

Hodnota, která odpovídá zvolenému názvu volby.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) metoda


Získá hodnotu, která odpovídá zvolenému názvu volby.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Úroveň socketové volby. |
| optionName | [SocketOptionName](../../socketoptionname/) | Název volby. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Výstupní parametr, do kterého bude přiřazena odpovídající hodnota. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) metoda


Vrací hodnotu, která odpovídá zvolenému názvu volby.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | Úroveň socketové volby. |
| optionName | [SocketOptionName](../../socketoptionname/) | Název volby. |
| optionLength | **int32_t** | Délka volby. |

### Návratová hodnota

Hodnota, která odpovídá zvolenému názvu volby.

## Viz také

* Výčet [SocketOptionLevel](../../socketoptionlevel/)
* Výčet [SocketOptionName](../../socketoptionname/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [Object](../../../system/object/)
* Třída [Socket](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)