---
title: ToBoolean()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí jeden bajt ze specifikovaného pole počínaje určeným indexem na logickou hodnotu.
type: docs
weight: 27
url: /cs/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Převádí jeden bajt ze specifikovaného pole počínaje určeným indexem na logickou hodnotu.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### Návratová hodnota

[Boolean](../../boolean/) value resulting from conversion

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Převádí jeden bajt ze specifikovaného pole počínaje určeným indexem na logickou hodnotu.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### Návratová hodnota

[Boolean](../../boolean/) value resulting from conversion

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)