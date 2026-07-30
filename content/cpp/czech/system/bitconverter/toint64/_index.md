---
title: ToInt64()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Převede osm bajtů ze zadaného pole počínaje určeným indexem na 64bitovou celočíselnou hodnotu.
type: docs
weight: 79
url: /cs/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Převede osm bajtů ze zadaného pole počínaje určeným indexem na 64bitové celé číslo.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít odebírat bajty pro převod |

### Návratová hodnota

64-bitová celočíselná hodnota získaná převodem

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Převede osm bajtů ze zadaného pole počínaje určeným indexem na 64bitové celé číslo.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít odebírat bajty pro převod |

### Návratová hodnota

64-bitová celočíselná hodnota získaná převodem

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)