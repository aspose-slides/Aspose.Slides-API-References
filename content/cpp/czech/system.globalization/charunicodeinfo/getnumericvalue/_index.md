---
title: GetNumericValue()
second_title: Aspose.Slides pro C++ API Reference
description: Získá číselnou hodnotu spojenou se zadaným znakem.
type: docs
weight: 27
url: /cs/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) metoda


Získá číselnou hodnotu spojenou se zadaným znakem.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| ch | char16_t | Unicode znak. |

### Návratová hodnota

Číselná hodnota nebo -1, pokud zadaný znak není číselný znak.

## CharUnicodeInfo::GetNumericValue(const String\&, int) metoda


Získá číselnou hodnotu spojenou se znakem na zadaném indexu řetězce.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Řetězec obsahující Unicode znak. |
| index | int | Index Unicode znaku. |

### Návratová hodnota

Číselná hodnota nebo -1, pokud zadaný znak není číselný znak.

## Viz také

* Třída [CharUnicodeInfo](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Globalization](../../)
* Knihovna [Aspose.Slides](../../../)