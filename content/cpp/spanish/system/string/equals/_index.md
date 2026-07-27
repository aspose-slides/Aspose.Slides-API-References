---
title: Equals()
second_title: Referencia de API de Aspose.Slides para C++
description: Comparación de igualdad de cadenas. Se admiten varios modos proporcionados por la enumeración StringComparison.
type: docs
weight: 391
url: /es/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const método

[String](../) comparación de igualdad. Se admiten varios modos proporcionados por la enumeración StringComparison.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar con el actual. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo (ver [System::StringComparison](../../stringcomparison/) para obtener más detalles). |

### Valor devuelto

true si las cadenas coinciden usando el tipo de comparación seleccionado, false en caso contrario.

## String::Equals(const String\&) const método

[String](../) comparación de igualdad. Usa el modo de comparación [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para comparar con el actual. |

### Valor devuelto

true si las cadenas coinciden, false en caso contrario.

## String::Equals(const String\&, const String\&) método

Compara dos cadenas usando el modo de comparación Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |

### Valor devuelto

true si las cadenas coinciden, false en caso contrario.

## String::Equals(const String\&, const String\&, System::StringComparison) método

Compara dos cadenas para igualdad.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| strA | const [String](../)\& | Primera cadena a comparar. |
| strB | const [String](../)\& | Segunda cadena a comparar. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) modo. |

### Valor devuelto

true si las cadenas coinciden, false en caso contrario.

## Ver también

* Enumeración [StringComparison](../../stringcomparison/)
* Clase [String](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)