---
title: ToInt16()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí dva bajty ze zadaného pole počínaje zadaným indexem na 16-bitovou celočíselnou hodnotu.
type: docs
weight: 53
url: /cs/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Převádí dva bajty ze zadaného pole počínaje zadaným indexem na 16-bitové celé číslo.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) která obsahuje bajty ke konverzi |
| startIndex | int | [Index](../../index/) v poli, od kterého se mají začít brát bajty pro konverzi |

### Návratová hodnota

16-bitová celočíselná hodnota výsledná po konverzi

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Převádí dva bajty ze zadaného pole počínaje zadaným indexem na 16-bitové celé číslo.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, která obsahuje bajty ke konverzi |
| startIndex | int | [Index](../../index/) v poli, od kterého se mají začít brát bajty pro konverzi |

### Návratová hodnota

16-bitová celočíselná hodnota výsledná po konverzi

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)