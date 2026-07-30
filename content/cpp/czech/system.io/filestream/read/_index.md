---
title: Read()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Načte z proudu zadaný počet bajtů a zapíše je do určeného bajtového pole.
type: docs
weight: 183
url: /cs/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného bajtového pole.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bajtové pole, do kterého se zapíšou načtené bajty. |
| offset | **int32_t** | Nulová pozice v **buffer**, odkud se začne zapisovat. |
| count | **int32_t** | Počet bajtů k načtení. |

### Návratová hodnota

Počet načtených bajtů.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Načte z proudu zadaný počet bajtů a zapíše je do určeného bajtového pole.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na bajtové pole, do kterého se zapíšou načtené bajty. |
| offset | **int32_t** | Nulová pozice v **buffer**, odkud se začne zapisovat. |
| count | **int32_t** | Počet bajtů k načtení. |

### Návratová hodnota

Počet načtených bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [FileStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)