---
title: ToChar()
second_title: Aspose.Slides for C++ referenční příručka API
description: Převádí dva bajty ze zadaného pole počínaje zadaným indexem na hodnotu typu char_t.
type: docs
weight: 40
url: /cs/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) metoda


Převádí dva bajty ze zadaného pole počínaje zadaným indexem na hodnotu typu char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít brát bajty pro převod |

### Návratová hodnota

char_t hodnota vzniklá po převodu

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) metoda


Převádí dva bajty ze zadaného pole počínaje zadaným indexem na hodnotu typu char_t.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít brát bajty pro převod |

### Návratová hodnota

char_t hodnota vzniklá po převodu

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)