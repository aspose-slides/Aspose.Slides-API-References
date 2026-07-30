---
title: Read()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Pokud je režim zapouzdření binární, přečte ze streamu zadaný počet bajtů, jinak přečte zadaný počet znaků a převede je na typ uint8_t. Výsledek čtení zapíše do zadaného bytového pole.
type: docs
weight: 66
url: /cs/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Pokud je režim zapouzdření binární, přečte ze streamu zadaný počet bajtů, jinak přečte zadaný počet znaků a převede je na typ **uint8_t**. Výsledek čtení zapíše do zadaného bytového pole.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte pole, do kterého se zapíšou přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, kde začít zapisovat |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů nebo znaků

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Přečte ze streamu zadaný počet bajtů a zapíše je do zadaného bytového pole.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte pohled, do kterého se zapíšou přečtené bajty |
| offset | **int32_t** | Nulová pozice v **buffer**, kde začít zapisovat |
| count | **int32_t** | Počet bajtů k přečtení |

### Návratová hodnota

Počet přečtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [BasicSTDIOStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)