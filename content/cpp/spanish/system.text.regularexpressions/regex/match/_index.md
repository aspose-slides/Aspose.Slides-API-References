---
title: Match()
second_title: Referencia de API de Aspose.Slides para C++
description: Coincide la expresión regular con la cadena.
type: docs
weight: 66
url: /es/system.text.regularexpressions/regex/match/
---
## Regex::Match(const String\&) method

Coincide la expresión regular con la cadena.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena objetivo. |

### Valor devuelto

[Match](../../match/) valor que contiene el estado de la coincidencia y las subcoincidencias.

## Regex::Match(const String\&, int, int) method

Coincide la expresión regular con la cadena.

```cpp
MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, int startat, int length=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena objetivo. |
| startat | int | Índice inicial. |
| length | int | Número de caracteres a examinar (0 para examinar toda la cadena). |

### Valor devuelto

[Match](../../match/) valor que contiene el estado de la coincidencia y las subcoincidencias.

## Regex::Match(const String\&, const String\&, RegexOptions, TimeSpan, int, int) method

Coincide la cadena y el patrón.

```cpp
static MatchPtr System::Text::RegularExpressions::Regex::Match(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| options | [RegexOptions](../../regexoptions/) | Opciones de coincidencia. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tiempo de espera. |
| startat | int | [Match](../../match/) posición inicial. |
| length | int | Número de caracteres a examinar (0 desactiva el límite). |

### Valor devuelto

Primera coincidencia encontrada.

## See Also

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchPtr](../../matchptr/)
* Class [String](../../../system/string/)
* Class [Regex](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)