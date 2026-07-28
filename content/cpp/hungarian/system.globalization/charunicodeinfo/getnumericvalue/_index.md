---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API-referencia
description: Lekéri a megadott karakterhez tartozó numerikus értéket.
type: docs
weight: 27
url: /hu/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) metódus


Lekéri a megadott karakterhez tartozó numerikus értéket.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char16_t | Unicode karakter. |

### Visszatérési érték

A numerikus érték, vagy -1, ha a megadott karakter nem numerikus karakter.

## CharUnicodeInfo::GetNumericValue(const String\&, int) metódus


Lekéri a karakterhez tartozó numerikus értéket a karakterlánc megadott indexén.

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Az unicode karaktert tartalmazó karakterlánc. |
| index | int | Az unicode karakter indexe. |

### Visszatérési érték

A numerikus érték, vagy -1, ha a megadott karakter nem numerikus karakter.

## Lásd még

* Osztály [CharUnicodeInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)