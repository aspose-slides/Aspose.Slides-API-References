---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av UnmanagedMemoryStream.
type: docs
weight: 118
url: /sv/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) konstruktor


Skapar en ny instans av [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pointer | **uint8_t** * | En pekare till en ohanterad buffert |
| length | **int64_t** | Storleken på den ohanterade bufferten i byte |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) konstruktor


Skapar en ny instans av [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pointer | **uint8_t** * | En pekare till en ohanterad buffert |
| length | **int64_t** | Storleken på den ohanterade bufferten i byte |
| capacity | **int64_t** | Den totala mängden minne som tilldelats strömmen |
| access | [FileAccess](../../fileaccess/) | Anger om strömmen ska vara skrivskyddad, skrivbar eller båda |

## Se även

* Enum [FileAccess](../../fileaccess/)
* Klass [UnmanagedMemoryStream](../)
* Namnområde [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)