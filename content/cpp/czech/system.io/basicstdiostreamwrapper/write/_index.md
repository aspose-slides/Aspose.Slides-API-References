---
title: Write()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Pokud je režim zabalení binární, zapíše do proudu určený podrozsah bajtů ze zadaného pole bajtů, jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ char_type a poté zapíše výsledek do proudu.
type: docs
weight: 79
url: /cs/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Pokud je režim zabalení binární, zapíše do toku určený podrozsah bajtů ze zadaného pole bajtů, jinak převede určený podrozsah bajtů ze zadaného pole bajtů na typ char_type a pak zapíše výsledek do toku.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapíše určený podrozsah bajtů ze zadaného pole bajtů do toku.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDIOStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)