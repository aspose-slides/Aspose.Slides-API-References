---
title: ToInt32()
second_title: Aspose.Slides pro C++ API Reference
description: Převede čtyři bajty ze zadaného pole začínajícího na zadaném indexu na 32bitovou celočíselnou hodnotu.
type: docs
weight: 66
url: /cs/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Převede čtyři bajty ze zadaného pole začínající na zadaném indexu na 32bitové celé číslo.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít odebírat bajty pro převod |

### Návratová hodnota

32bitová celočíselná hodnota získaná převodem

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Převede čtyři bajty ze zadaného pole začínající na zadaném indexu na 32bitové celé číslo.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít odebírat bajty pro převod |

### Návratová hodnota

32bitová celočíselná hodnota získaná převodem

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)