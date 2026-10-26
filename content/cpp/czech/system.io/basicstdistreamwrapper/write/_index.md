---
title: Write()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Pokud je režim zapouzdření binární, zapíše do proudu určený podrozsah bajtů ze zadaného pole bajtů; jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ char_type a poté zapíše výsledek do proudu. Nepodporováno!
type: docs
weight: 79
url: /cs/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Pokud je režim balení binární, zapíše do proudu určený podrozsah bajtů ze zadaného pole bajtů, jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ char_type a poté zapíše výsledek do proudu. Nepodporováno!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše určený podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDIStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)