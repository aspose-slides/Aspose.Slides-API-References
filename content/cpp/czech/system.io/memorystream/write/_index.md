---
title: Write()
second_title: Aspose.Slides pro C++ API Reference
description: Zapíše určený podrozsah bajtů ze specifikovaného pole bajtů do proudu.
type: docs
weight: 92
url: /cs/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše určený podrozsah bajtů ze specifikovaného pole bajtů do proudu.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Nulový index prvku v **buffer**, od kterého začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu, který se má zapsat |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše určený podrozsah bajtů ze specifikovaného pole bajtů do proudu.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Nulový index prvku v **buffer**, od kterého začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu, který se má zapsat |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [MemoryStream](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)