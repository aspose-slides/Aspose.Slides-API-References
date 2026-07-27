---
title: Split()
second_title: Referencia de API de Aspose.Slides para C++
description: Divide la cadena por coincidencias de expresiones regulares.
type: docs
weight: 105
url: /es/system.text.regularexpressions/regex/split/
---
## Regex::Split(const String\&) método

Divide la cadena por coincidencias de expresiones regulares.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) a dividir. |

### Valor devuelto

[Array](../../../system/array/) de subcadenas entre coincidencias.

## Regex::Split(const String\&, int) método

Divide la cadena por coincidencias de expresiones regulares.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | [String](../../../system/string/) a dividir. |
| count | int | Límite del número de subcadenas. |

### Valor devuelto

[Array](../../../system/array/) de subcadenas entre coincidencias.

## Regex::Split(const String\&, int, int) método

Divide una cadena de entrada un número máximo especificado de veces en una matriz de subcadenas, en las posiciones definidas por una expresión regular especificada en el constructor [Regex](../). La búsqueda del patrón de expresión regular comienza en una posición de carácter especificada en la cadena de entrada.

```cpp
ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, int count, int startat)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | La cadena a dividir. |
| count | int | El número máximo de veces que puede ocurrir la división. |
| startat | int | La posición de carácter en la cadena de entrada donde comenzará la búsqueda. |

### Valor devuelto

Una matriz de cadenas.

## Regex::Split(const String\&, const String\&, RegexOptions, TimeSpan) método

Divide la cadena por expresión regular.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| options | [RegexOptions](../../regexoptions/) | Opciones de coincidencia. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tiempo de espera. |

### Valor devuelto

[Array](../../../system/array/) de cadenas entre coincidencias.

## Regex::Split(const String\&, const String\&, int, RegexOptions, TimeSpan) método

Divide la cadena por expresión regular.

```cpp
static ArrayPtr<String> System::Text::RegularExpressions::Regex::Split(const String &input, const String &pattern, int count, RegexOptions options=RegexOptions::None, TimeSpan matchTimeout=InfiniteMatchTimeout)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../../system/string/)\& | Cadena de entrada. |
| pattern | const [String](../../../system/string/)\& | Patrón de expresión regular. |
| count | int | [Match](../../match/) límite de número. |
| options | [RegexOptions](../../regexoptions/) | Opciones de coincidencia. |
| matchTimeout | [TimeSpan](../../../system/timespan/) | Tiempo de espera. |

### Valor devuelto

[Array](../../../system/array/) de cadenas entre coincidencias.

## Ver también

* Enum [RegexOptions](../../regexoptions/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [String](../../../system/string/)
* Clase [Regex](../)
* Clase [TimeSpan](../../../system/timespan/)
* Espacio de nombres [System::Text::RegularExpressions](../../)
* Biblioteca [Aspose.Slides](../../../)