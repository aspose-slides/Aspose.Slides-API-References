---
title: Write()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Pokud je režim balení binární, zapíše do proudu určený podrozsah bajtů ze zadaného pole bajtů, jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ char_type a poté zapíše výsledek do proudu.
type: docs
weight: 79
url: /cs/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Pokud je režim balení binární, zapíše do proudu určený podrozsah bajtů ze zadaného pole bajtů, jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ **char_type** a poté zapíše výsledek do proudu.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Index založený na nule prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše určený podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Index založený na nule prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDOStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)