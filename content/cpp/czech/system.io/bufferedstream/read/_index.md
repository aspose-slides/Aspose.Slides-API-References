---
title: Read()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Přečte z podkladového proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.
type: docs
weight: 53
url: /cs/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Čte z podkladového proudu zadaný počet bajtů a zapisuje je do zadaného pole bajtů.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapisují přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde začít zápis |
| count | **int32_t** | Počet bajtů ke čtení |

### Návratová hodnota

Počet přečtených bajtů

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Čte z podkladového proudu zadaný počet bajtů a zapisuje je do zadaného pole bajtů.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pole bajtů, do kterého se zapisují přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde začít zápis |
| count | **int32_t** | Počet bajtů ke čtení |

### Návratová hodnota

Počet přečtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BufferedStream](../)
* Jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)