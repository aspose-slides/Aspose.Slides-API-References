---
title: Split()
second_title: Aspose.Slides för C++ API-referens
description: Delar strängen efter regex-matchningar.
type: docs
weight: 105
url: /sv/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metod


Delar strängen efter regex-matchningar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) att dela. |

### Returvärde

[Array](../../../system/array/) av delsträngar mellan matchningar.

## Regex::Split(const String\&, int) metod


Delar strängen efter regex-matchningar.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) att dela. |
| count | int | Begränsning för antal delsträngar. |

### Returvärde

[Array](../../../system/array/) av delsträngar mellan matchningar.

## Regex::Split(const String\&, int, int) metod


Delar en indatasträng ett angivet maximalt antal gånger i en array av delsträngar, på de positioner som definieras av ett reguljärt uttryck som anges i [Regex](../)-konstruktorn. Sökningen efter mönstret i det reguljära uttrycket startar på en angiven teckenposition i indatasträngen.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Strängen som ska delas. |
| count | int | Det maximala antalet gånger split kan utföras. |
| startat | int | Teckenpositionen i indatasträngen där sökningen ska börja. |

### Returvärde

En array av strängar.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metod


Delar strängen efter regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regexp-mönster. |
| options | [RegexOptions](../../regexoptions/) | Matchningsalternativ. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Returvärde

[Array](../../../system/array/) av strängar mellan matchningar.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metod


Delar strängen efter regexp.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Indatasträng. |
| pattern | const [String](../../../system/string/)\& | Regexp-mönster. |
| count | int | [Match](../../match/) antalgräns. |
| options | [RegexOptions](../../regexoptions/) | Matchningsalternativ. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Timeout. |

### Returvärde

[Array](../../../system/array/) av strängar mellan matchningar.

## Se även

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)