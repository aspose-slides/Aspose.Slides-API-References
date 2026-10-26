---
title: CompareTo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara dos intervalos de caracteres con las reglas de comparación de cadenas especificadas.
type: docs
weight: 404
url: /es/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) función

Compara dos intervalos de caracteres con las reglas de comparación de cadenas especificadas.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El primer intervalo de caracteres |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El segundo intervalo de caracteres |
| comparisonType | [StringComparison](../../system/stringcomparison/) | El tipo de comparación de cadenas a realizar |

### Valor de retorno

Valor negativo si span < other, cero si son iguales, positivo si span > other

## Ver también

* Enum [StringComparison](../../system/stringcomparison/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)