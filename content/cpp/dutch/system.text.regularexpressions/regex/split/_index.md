---
title: Split()
second_title: Aspose.Slides voor C++ API Referentie
description: Splitst tekenreeks op basis van regex-overeenkomsten.
type: docs
weight: 105
url: /nl/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) methode


Splitst een tekenreeks op basis van regex-overeenkomsten.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |

### Returnwaarde

[Array](../../../system/array/) of substrings between matches.

## Regex::Split(const String\&, int) methode


Splitst een tekenreeks op basis van regex-overeenkomsten.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) to split. |
| count | int | Limiet van het aantal substrings. |

### Returnwaarde

[Array](../../../system/array/) of substrings between matches.

## Regex::Split(const String\&, int, int) methode


Splitst een invoertekenreeks een opgegeven maximum aantal keren in een array van substrings, op de posities die worden gedefinieerd door een reguliere expressie opgegeven in de [Regex](../)-constructor. Het zoeken naar het patroon van de reguliere expressie begint op een opgegeven tekenpositie in de invoertekenreeks.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | De tekenreeks die gesplitst moet worden. |
| count | int | Het maximale aantal keren dat de splitsing kan plaatsvinden. |
| startat | int | De tekenpositie in de invoertekenreeks waar de zoekopdracht begint. |

### Returnwaarde

Een array van strings.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) methode


Splitst een tekenreeks op basis van regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| options | [RegexOptions](../../regexoptions/) | Matchopties. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Time-out. |

### Returnwaarde

[Array](../../../system/array/) of strings between matchse.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) methode


Splitst een tekenreeks op basis van regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Invoertekenreeks. |
| pattern | const [String](../../../system/string/)\& | Regexp-patroon. |
| count | int | [Match](../../match/) nummerlimiet. |
| options | [RegexOptions](../../regexoptions/) | Matchopties. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Time-out. |

### Returnwaarde

[Array](../../../system/array/) of strings between matchse.

## Zie ook

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Regex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)