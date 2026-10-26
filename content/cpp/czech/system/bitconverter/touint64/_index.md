---
title: ToUInt64()
second_title: Aspose.Slides pro C++ - API Reference
description: Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na nezápornou 64-bitovou celočíselnou hodnotu.
type: docs
weight: 118
url: /cs/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na nezápornou 64-bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro převod |

### Návratová hodnota

Nezáporná 64-bitová celočíselná hodnota získaná konverzí

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na nezápornou 64-bitovou celočíselnou hodnotu.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro převod |

### Návratová hodnota

Nezáporná 64-bitová celočíselná hodnota získaná konverzí

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)