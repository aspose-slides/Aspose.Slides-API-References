---
title: Write()
second_title: Aspose.Slides pro C++ API Reference
description: Zapisuje zadaný podrozsah bajtů ze zadaného pole bajtů do podkladového proudu.
type: docs
weight: 66
url: /cs/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje zadaný podrozsah bajtů ze zadaného pole bajtů do podkladového proudu.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Index založený na nule prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapisuje zadaný podrozsah bajtů ze zadaného pole bajtů do podkladového proudu.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Index založený na nule prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BufferedStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)