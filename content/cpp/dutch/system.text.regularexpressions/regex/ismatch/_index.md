---
title: IsMatch()
second_title: Aspose.Slides for C++ API-referentie
description: Zoekt regex in een string.
type: docs
weight: 53
url: /nl/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) methode


Zoekt regex in een string.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Doelstring. |
| startat | int | Beginindex. |

### Retourwaarde

True als de string overeenkomt met regex, false anders.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) methode


Controleert of een string overeenkomt met patroon.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| options | [RegexOptions](../../regexoptions/) | Vergelijkingsopties. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Time-out. |
| startat | int | [Match](../../match/) beginnende positie. |

### Retourwaarde

True als een overeenkomst wordt gevonden, false anders.

## Zie ook

* Enum [RegexOptions](../../regexoptions/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)