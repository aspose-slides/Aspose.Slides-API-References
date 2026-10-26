---
title: IsMatch()
second_title: Aspose.Slides for C++ API referenciája
description: Illeszti a reguláris kifejezést a karakterláncra.
type: docs
weight: 53
url: /hu/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) metódus

Illeszti a reguláris kifejezést a karakterláncra.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Célkarakterlánc. |
| startat | int | Kezdő index. |

### Visszatérési érték

Igaz, ha a karakterlánc illeszkedik a regex-re, egyébként hamis.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) metódus

Ellenőrzi, hogy a karakterlánc illeszkedik-e a mintára.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Reguláris kifejezés minta. |
| options | [RegexOptions](../../regexoptions/) | Illesztési beállítások. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Időkorlát. |
| startat | int | [Match](../../match/) kezdő pozíció. |

### Visszatérési érték

Igaz, ha a találat megvan, egyébként hamis.

## Lásd még

* Enum [RegexOptions](../../regexoptions/)
* Osztály [String](../../../system/string/)
* Osztály [Regex](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtere [System::Text::RegularExpressions](../../)
* Könyvtár [Aspose.Slides](../../../)