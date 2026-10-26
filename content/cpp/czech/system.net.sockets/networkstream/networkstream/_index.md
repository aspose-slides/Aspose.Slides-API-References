---
title: NetworkStream()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Vytvoří novou instanci.
type: docs
weight: 170
url: /cs/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Socket, který se používá k odesílání a přijímání dat. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Socket, který se používá k odesílání a přijímání dat. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Určuje typ přístupu přiřazený instanci nad specifikovaným socketem. |
| ownsSocket | **bool** | Hodnota, která určuje, zda aktuální instance přebírá vlastnictví specifikovaného socketu, pokud je hodnota true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | Socket, který se používá k odesílání a přijímání dat. |
| ownsSocket | **bool** | Hodnota, která určuje, zda aktuální instance přebírá vlastnictví specifikovaného socketu, pokud je hodnota true. |

## Viz také

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Socket](../../socket/)
* Třída [NetworkStream](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)