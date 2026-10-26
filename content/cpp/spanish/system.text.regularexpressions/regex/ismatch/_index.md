---
title: IsMatch()
second_title: Referencia de API de Aspose.Slides para C++
description: Coincide la expresión regular con la cadena.
type: docs
weight: 53
url: /es/system.text.regularexpressions/regex/ismatch/
---
## Regex::IsMatch(const String\&, int) método

Coincide la expresión regular con la cadena.

```cpp
bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, int startat=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena objetivo. |
| startat | int | Índice inicial. |

### Valor de retorno

Verdadero si la cadena coincide con la expresión regular, falso en caso contrario.

## Regex::IsMatch(const String\&, const String\&, RegexOptions, TimeSpan, int) método

Comprueba si la cadena coincide con el patrón.

```cpp
static bool System::Text::RegularExpressions::Regex::IsMatch(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| options | [RegexOptions](../../regexoptions/) | Opciones de coincidencia. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tiempo de espera. |
| startat | int | [Match](../../match/) posición inicial. |

### Valor de retorno

Verdadero si se encuentra una coincidencia, falso en caso contrario.

## Ver también

* Enum [RegexOptions](../../regexoptions/)
* Clase [String](../../../system/string/)
* Clase [Regex](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Text::RegularExpressions](../../)
* Library [Aspose.Slides](../../../)