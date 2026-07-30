---
title: Read()
second_title: Aspose.Slides pro C++ API Reference
description: Pokud je režim balení binární, přečte ze streamu určený počet bajtů, jinak přečte určený počet znaků a převede je na typ uint8_t. Výsledek čtení zapíše do určeného pole bajtů. Nepodporováno!
type: docs
weight: 66
url: /cs/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Pokud je režim balení binární, přečte ze streamu určený počet bajtů, jinak přečte určený počet znaků a převede je na typ **uint8_t**. Výsledek čtení zapíše do určeného pole bajtů. Nepodporováno!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, od které se má začít zapisovat |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet bajtů nebo znaků přečtených

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Přečte ze streamu určený počet bajtů a zapíše je do určeného pole bajtů.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole bajtů, do kterého se zapíšou přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, od které se má začít zapisovat |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet bajtů přečtených

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDOStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)