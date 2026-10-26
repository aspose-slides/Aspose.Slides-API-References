---
title: Read()
second_title: Aspose.Slides pro C++ API Reference
description: Přečte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.
type: docs
weight: 144
url: /cs/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Přečte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se mají zapsat přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde se má zápis zahájit |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Přečte z proudu zadaný počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého se mají zapsat přečtené bajty |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde se má zápis zahájit |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [UnmanagedMemoryStream](../)
* Namespace [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)