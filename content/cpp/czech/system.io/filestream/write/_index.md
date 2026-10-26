---
title: Write()
second_title: Aspose.Slides pro C++ API Reference
description: Zapíše určený podrozsah bajtů ze zadaného pole bajtů do proudu.
type: docs
weight: 248
url: /cs/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapíše specifikovaný podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapíše specifikovaný podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu. |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [FileStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)