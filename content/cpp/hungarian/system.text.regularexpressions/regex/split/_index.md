---
title: Split()
second_title: Aspose.Slides C++ API hivatkozás
description: A karakterláncot regex egyezések alapján osztja fel.
type: docs
weight: 105
url: /hu/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metódus


Felosztja a karakterláncot regex egyezések alapján.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) a felosztáshoz. |

### Visszatérési érték

[Array](../../../system/array/) a találatok közötti részkarakterláncok.



## Regex::Split(const String\&, int) metódus


Felosztja a karakterláncot regex egyezések alapján.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) a felosztáshoz. |
| count | int | A felosztás legfeljebb ennyi alkalommal történhet. |

### Visszatérési érték

[Array](../../../system/array/) a találatok közötti részkarakterláncok.



## Regex::Split(const String\&, int, int) metódus


A bemeneti karakterláncot a [Regex](../) konstruktorban megadott reguláris kifejezéssel meghatározott helyeken egy meghatározott legnagyobb számú alkalommal bontja fel részkarakterláncokra. A reguláris kifejezés keresése a bemeneti karakterlánc egy meghatározott karakterpozíciójától indul.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | A felosztandó karakterlánc. |
| count | int | A felosztás legfeljebb ennyi alkalommal történhet. |
| startat | int | A karakterpozíció a bemeneti karakterláncban, ahol a keresés megkezdődik. |

### Visszatérési érték

Egy karakterlánc tömb.



## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metódus


Felosztja a karakterláncot reguláris kifejezés szerint.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Reguláris kifejezés minta. |
| options | [RegexOptions](../../regexoptions/) | Egyezési beállítások. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Időkorlát. |

### Visszatérési érték

[Array](../../../system/array/) a találatok közötti karakterláncok.



## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metódus


Felosztja a karakterláncot reguláris kifejezés szerint.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Bemeneti karakterlánc. |
| pattern | const [String](../../../system/string/)\& | Reguláris kifejezés minta. |
| count | int | [Match](../../match/) számkorlát. |
| options | [RegexOptions](../../regexoptions/) | Egyezési beállítások. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Időkorlát. |

### Visszatérési érték

[Array](../../../system/array/) a találatok közötti karakterláncok.



## Lásd még

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [Regex](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Text::RegularExpressions](../../)
* Könyvtár [Aspose.Slides](../../../)