---
title: Read()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Pokud je režim balení binární, přečte z proudu určený počet bajtů, jinak přečte určený počet znaků a převede je na typ uint8_t. Výsledek čtení zapíše do určeného pole bajtů.
type: docs
weight: 66
url: /cs/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Pokud je režim balení binární, přečte z proudu určený počet bajtů, jinak přečte určený počet znaků a převede je na typ **uint8_t**. Výsledek čtení zapíše do určeného pole bajtů.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíší přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, odkud se má začít zapisovat |
| count | **int32_t** | Počet bajtů, které se mají přečíst |

### Návratová hodnota

Počet přečtených bajtů nebo znaků


## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Přečte z proudu určený počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého se zapíší přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, odkud se má začít zapisovat |
| count | **int32_t** | Počet bajtů, které se mají přečíst |

### Návratová hodnota

Počet přečtených bajtů


## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDIStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)