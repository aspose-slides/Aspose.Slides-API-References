---
title: Matches()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene todas las coincidencias de la expresión regular en la cadena dada mediante coincidencias repetidas.
type: docs
weight: 79
url: /es/system.text.regularexpressions/regex/matches/
---
## Regex::Matches(const String\&, int) método

Obtiene todas las coincidencias de la expresión regular en la cadena dada mediante coincidencias repetidas.

```cpp
MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, int startat=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| startat | int | [Index](../../../system/index/) para iniciar la coincidencia en. |

### Valor de retorno

Colección de todas las coincidencias encontradas.

## Regex::Matches(const String\&, const String\&, RegexOptions, TimeSpan, int, int) método

Obtiene todas las coincidencias entre la cadena y el patrón.

```cpp
static MatchCollectionPtr System::Text::RegularExpressions::Regex::Matches(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout, int startat=0, int length=0)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| options | [RegexOptions](../../regexoptions/) | Opciones de coincidencia. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tiempo de espera. |
| startat | int | [Match](../../match/) posición inicial. |
| length | int | Número de caracteres a inspeccionar (0 desactiva el límite). |

### Valor de retorno

Todas las coincidencias encontradas mediante coincidencias repetidas.

## Ver también

* Enum [RegexOptions](../../regexoptions/)
* Typedef [MatchCollectionPtr](../../matchcollectionptr/)
* Clase [String](../../../system/string/)
* Clase [Regex](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Text::RegularExpressions](../../)
* Biblioteca [Aspose.Slides](../../../)