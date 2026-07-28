---
title: NetworkStream()
second_title: Aspose.Slides for C++ API referenciája
description: Új példányt hoz létre.
type: docs
weight: 170
url: /hu/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | A socket, amely adatküldésre és -fogadásra szolgál. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | A socket, amely adatküldésre és -fogadásra szolgál. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Meghatározza a példány számára a megadott socket feletti hozzáférés típusát. |
| ownsSocket | **bool** | Egy érték, amely azt jelzi, hogy a jelenlegi példány a megadott socket tulajdonjogát átveszi, ha az érték igaz. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | A socket, amely adatküldésre és -fogadásra szolgál. |
| ownsSocket | **bool** | Egy érték, amely azt jelzi, hogy a jelenlegi példány a megadott socket tulajdonjogát átveszi, ha az érték igaz. |

## Lásd még

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Socket](../../socket/)
* Osztály [NetworkStream](../)
* Névterület [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)