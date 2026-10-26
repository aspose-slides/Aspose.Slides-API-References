---
title: ToSingle()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na hodnotu s jednoduchou přesností.
type: docs
weight: 131
url: /cs/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) metoda

Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na hodnotu s jednoduchou přesností.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro převod |

### Návratová hodnota

Hodnota s jednoduchou přesností získaná převodem

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) metoda

Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na hodnotu s jednoduchou přesností.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, kde začít brát bajty pro převod |

### Návratová hodnota

Hodnota s jednoduchou přesností získaná převodem

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)