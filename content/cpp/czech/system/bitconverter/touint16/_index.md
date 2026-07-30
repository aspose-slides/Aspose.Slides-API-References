---
title: ToUInt16()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Převádí dva bajty ze zadaného pole počínaje zadaným indexem na neoznačenou 16-bitovou celočíselnou hodnotu.
type: docs
weight: 92
url: /cs/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Převede dva bajty ze zadaného pole počínaje zadaným indexem na neoznačenou 16-bitovou celočíselnou hodnotu.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít s převzetím bajtů pro převod |

### Návratová hodnota

Neoznačená 16-bitová celočíselná hodnota vzniklá převodem

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Převede dva bajty ze zadaného pole počínaje zadaným indexem na neoznačenou 16-bitovou celočíselnou hodnotu.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít s převzetím bajtů pro převod |

### Návratová hodnota

Neoznačená 16-bitová celočíselná hodnota vzniklá převodem

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* třída [BitConverter](../)
* jmenný prostor [System](../../)
* knihovna [Aspose.Slides](../../../)