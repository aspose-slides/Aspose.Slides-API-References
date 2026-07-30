---
title: ToUInt32()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na nepodepsanou 32-bitovou celočíselnou hodnotu.
type: docs
weight: 105
url: /cs/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na nepodepsanou 32-bitovou celočíselnou hodnotu.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty ke konverzi |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro konverzi |

### Návratová hodnota

Ne-podepsaná 32-bitová celočíselná hodnota vzniklá konverzí

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na nepodepsanou 32-bitovou celočíselnou hodnotu.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView který obsahuje bajty ke konverzi |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro konverzi |

### Návratová hodnota

Ne-podepsaná 32-bitová celočíselná hodnota vzniklá konverzí

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)