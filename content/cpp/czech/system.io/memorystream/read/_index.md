---
title: Read()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů.
type: docs
weight: 79
url: /cs/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou načtené bajty |
| offset | **int32_t** | Pozice v **buffer** začínající od nuly, kam se má zapisovat |
| count | **int32_t** | Počet bajtů, které se mají načíst |

### Návratová hodnota

Počet načtených bajtů

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Načte z proudu zadaný počet bajtů a zapíše je do zadaného pole bajtů.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého se zapíšou načtené bajty |
| offset | **int32_t** | Pozice v **buffer** začínající od nuly, kam se má zapisovat |
| count | **int32_t** | Počet bajtů, které se mají načíst |

### Návratová hodnota

Počet načtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [MemoryStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)