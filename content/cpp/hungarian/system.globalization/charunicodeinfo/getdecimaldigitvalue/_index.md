---
title: GetDecimalDigitValue()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a megadott karakter decimális számjegyértékét.
type: docs
weight: 1
url: /hu/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) metódus

Visszaadja a megadott karakter decimális számjegyértékét.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char16_t | Unicode karakter. |

### Visszatérési érték

A decimális számjegy értéke, vagy -1, ha a megadott karakter nem decimális számjegy.

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) metódus

Visszaadja a megadott karakterláncban a megadott indexnél található karakter decimális számjegyértékét.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A Unicode karaktert tartalmazó karakterlánc. |
| index | int | A Unicode karakter indexe. |

### Visszatérési érték

A decimális számjegy értéke, vagy -1, ha a megadott karakter nem decimális számjegy.

## Lásd még

* Osztály [CharUnicodeInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)