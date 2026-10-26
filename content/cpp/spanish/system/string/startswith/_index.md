---
title: StartsWith()
second_title: Referencia de API de Aspose.Slides para C++
description: Comprueba si la cadena comienza con la subcadena especificada.
type: docs
weight: 469
url: /es/system/string/startswith/
---
## String::StartsWith(const String\&) const método

Comprueba si la cadena comienza con la subcadena especificada.

```cpp
bool System::String::StartsWith(const String &value) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../)\& | Cadena de búsqueda. |

### Valor devuelto

true si la cadena comienza con la subcadena especificada, false en caso contrario.

## String::StartsWith(const String\&, System::StringComparison) const método

Comprueba si la cadena comienza con la subcadena especificada.

```cpp
bool System::String::StartsWith(const String &value, System::StringComparison comparisonType) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../)\& | Cadena de búsqueda. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | modo [Comparison](../../comparison/), vea [System::StringComparison](../../stringcomparison/) para más detalles. |

### Valor devuelto

true si la cadena comienza con la subcadena especificada, false en caso contrario.

## String::StartsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const método

Comprueba si la cadena comienza con la subcadena especificada.

```cpp
bool System::String::StartsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../)\& | Cadena de búsqueda. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas y minúsculas. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al realizar la comparación de cadenas. |

### Valor devuelto

true si la cadena comienza con la subcadena especificada, false en caso contrario.

## See Also

* Enumeración [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)