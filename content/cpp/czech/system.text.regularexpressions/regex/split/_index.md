---  
title: Split()  
second_title: Aspose.Slides pro C++ API Reference  
description: Rozděluje řetězec podle shod regulárního výrazu.  
type: docs  
weight: 105  
url: /cs/system.text.regularexpressions/regex/split/  
---
## Regex::Split(const String\&) metoda

Rozděluje řetězec podle regulárních výrazů.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) k rozdělení. |

### Návratová hodnota

[Array](../../../system/array/) podřetězců mezi shodami.

## Regex::Split(const String\&, int) metoda

Rozděluje řetězec podle regulárních výrazů.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) k rozdělení. |
| count | int | Limit počtu podřetězců. |

### Návratová hodnota

[Array](../../../system/array/) podřetězců mezi shodami.

## Regex::Split(const String\&, int, int) metoda

Rozděluje vstupní řetězec zadaný maximální početkrát do pole podřetězců na pozicích definovaných regulárním výrazem zadaným v konstruktoru [Regex](../). Vyhledávání vzoru regulárního výrazu začíná na zadané pozici znaku ve vstupním řetězci.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Řetězec k rozdělení. |
| count | int | Maximální počet provedení rozdělení. |
| startat | int | Pozice znaku ve vstupním řetězci, kde začne vyhledávání. |

### Návratová hodnota

Pole řetězců.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) metoda

Rozděluje řetězec podle regulárního výrazu.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Vzor regulárního výrazu. |
| options | [RegexOptions](../../regexoptions/) | Možnosti shody. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Časový limit. |

### Návratová hodnota

[Array](../../../system/array/) řetězců mezi shodami.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) metoda

Rozděluje řetězec podle regulárního výrazu.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Vstupní řetězec. |
| pattern | const [String](../../../system/string/)\& | Vzor regulárního výrazu. |
| count | int | [Match](../../match/) limit počtu. |
| options | [RegexOptions](../../regexoptions/) | Možnosti shody. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Časový limit. |

### Návratová hodnota

[Array](../../../system/array/) řetězců mezi shodami.

## Viz také

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [Regex](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)