---
title: GetDigitValue()
second_title: Aspose.Slides for C++ API-referenciája
description: Megkapja a megadott karakter számértékét.
type: docs
weight: 14
url: /hu/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) metódus

Lekéri a megadott karakter számértékét.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | char16_t | Unicode karakter. |

### Visszatérési érték

A számérték vagy -1, ha a megadott karakter nem számjegy.

## CharUnicodeInfo::GetDigitValue(const String\&, int) metódus

Lekéri a karakter számértékét a megadott indexű karakter esetén a karakterláncban.

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | A karakterlánc, amely unicode karaktert tartalmaz. |
| index | int | Az unicode karakter indexe. |

### Visszatérési érték

A számérték vagy -1, ha a megadott karakter nem számjegy.

## Lásd még

* Osztály [CharUnicodeInfo](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)