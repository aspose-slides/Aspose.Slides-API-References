---
title: Split()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Dzieli ciąg według dopasowań wyrażenia regularnego.
type: docs
weight: 105
url: /pl/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) metoda


Dzieli ciąg za pomocą dopasowań wyrażenia regularnego.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) do podzielenia. |

### Wartość zwracana

[Array](../../../system/array/) podciągów pomiędzy dopasowaniami.

## Regex::Split(const String\&, int) metoda


Dzieli ciąg za pomocą dopasowań wyrażenia regularnego.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) do podzielenia. |
| count | int | Limit liczby podciągów. |

### Wartość zwracana

[Array](../../../system/array/) podciągów pomiędzy dopasowaniami.

## Regex::Split(const String\&, int, int) metoda


Dzieli ciąg wejściowy maksymalną określoną liczbę razy na tablicę podciągów, w miejscach określonych wyrażeniem regularnym podanym w konstruktorze [Regex](../). Wyszukiwanie wzorca wyrażenia regularnego rozpoczyna się od określonej pozycji znaku w ciągu wejściowym.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg do podzielenia. |
| count | int | Maksymalna liczba wystąpień podziału. |
| startat | int | Pozycja znaku w ciągu wejściowym, od której rozpocznie się wyszukiwanie. |

### Wartość zwracana

Tablica ciągów.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metoda


Dzieli ciąg przy użyciu wyrażenia regularnego.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| options | [RegexOptions](../../regexoptions/) | Opcje dopasowania. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Limit czasu. |

### Wartość zwracana

[Array](../../../system/array/) ciągów pomiędzy dopasowaniami.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metoda


Dzieli ciąg przy użyciu wyrażenia regularnego.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Ciąg wejściowy. |
| pattern | const [String](../../../system/string/)\& | Wzorzec wyrażenia regularnego. |
| count | int | [Match](../../match/) limit liczby. |
| options | [RegexOptions](../../regexoptions/) | Opcje dopasowania. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Limit czasu. |

### Wartość zwracana

[Array](../../../system/array/) ciągów pomiędzy dopasowaniami.

## Zobacz także

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)