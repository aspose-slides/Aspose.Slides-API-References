---
title: Replace()
second_title: Referencia de la API de Aspose.Slides para C++
description: Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.
type: docs
weight: 92
url: /es/system.text.regularexpressions/regex/replace/
---
## Regex::Replace(const String\&, const String\&) método


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| replacement | const [String](../../../system/string/)\& | Cadena de reemplazo. |

### Valor devuelto

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Regex::Replace(const String\&, const char_t *) método


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *replacement)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| replacement | const char_t * | Cadena de reemplazo. |

### Valor devuelto

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Regex::Replace(const String\&, const MatchEvaluator\&) método


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por un delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para generar cadenas de reemplazo basadas en las coincidencias. |

### Valor devuelto

Cadenas de entrada con todas las coincidencias reemplazadas.

## Regex::Replace(const String\&, const MatchEvaluator\&, int) método


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por un delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para generar cadenas de reemplazo basadas en las coincidencias. |
| count | int | Límite del número de reemplazos. |

### Valor devuelto

Cadenas de entrada con todas las coincidencias reemplazadas.

## Regex::Replace(const String\&, const MatchEvaluator\&, int, int) método


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por un delegado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const MatchEvaluator &evaluator, int count, int startat)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para generar cadenas de reemplazo basadas en las coincidencias. |
| count | int | Límite del número de reemplazos. |
| startat | int | [Index](../../../system/index/) en la cadena de entrada para iniciar el reemplazo en. |

### Valor devuelto

Cadenas de entrada con todas las coincidencias reemplazadas.

## Regex::Replace(const String\&, const String\&, int) método


Reemplaza subcadenas en la cadena. No implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count)
```

## Regex::Replace(const String\&, const String\&, int, int) método


Reemplaza subcadenas en la cadena. No implementado.

```cpp
String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &replacement, int count, int startat)
```

## Regex::Replace(const String\&, const char_t *, const char_t *) método


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const char_t *pattern, const char_t *replacement)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const char_t * | [Regex](../) patrón. |
| replacement | const char_t * | Cadena de reemplazo. |

### Valor devuelto

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Regex::Replace(const String\&, const String\&, const char_t *) método


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const char_t *replacement)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patrón. |
| replacement | const char_t * | Cadena de reemplazo. |

### Valor devuelto

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&, RegexOptions) método


Reemplaza todas las coincidencias en la cadena con cadenas de reemplazo generadas por un delegado (función estática).

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator, RegexOptions options)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patrón. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para generar cadenas de reemplazo basadas en las coincidencias. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opciones. |

### Valor devuelto

Cadenas de entrada con todas las coincidencias reemplazadas.

## Regex::Replace(const String\&, const String\&, const String\&, RegexOptions) método


Reemplaza todas las coincidencias de la expresión regular en la cadena con la cadena de reemplazo.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement, RegexOptions options)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | [Regex](../) patrón. |
| replacement | const [String](../../../system/string/)\& | Cadena de reemplazo. |
| options | [RegexOptions](../../regexoptions/) | [Regex](../) opciones. |

### Valor devuelto

Cadena de entrada con todas las coincidencias de la expresión regular reemplazadas por la cadena de reemplazo.

## Regex::Replace(const String\&, const String\&, const String\&) método


Reemplaza coincidencias de expresión regular.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const String &replacement)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| replacement | const [String](../../../system/string/)\& | Cadena de reemplazo. |

### Valor devuelto

[String](../../../system/string/) con todas las coincidencias reemplazadas.

## Regex::Replace(const String\&, const String\&, const MatchEvaluator\&) método


Reemplaza coincidencias de expresión regular.

```cpp
static String System::Text::RegularExpressions::Regex::Replace(const String &input, const String &pattern, const MatchEvaluator &evaluator)
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| evaluator | const [MatchEvaluator](../../matchevaluator/)\& | Delegado para generar la cadena de reemplazo para cada coincidencia. |

### Valor devuelto

[String](../../../system/string/) con todas las coincidencias reemplazadas.

## Ver también

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchEvaluator](../../matchevaluator/)
* Clase [String](../../../system/string/)
* Clase [Regex](../)
* Espacio de nombres [System::Text::RegularExpressions](../../)
* Biblioteca [Aspose.Slides](../../../)