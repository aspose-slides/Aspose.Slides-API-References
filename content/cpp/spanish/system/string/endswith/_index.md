---
title: EndsWith()
second_title: Referencia de la API de Aspose.Slides para C++
description: Comprueba si la cadena termina con la subcadena especificada.
type: docs
weight: 482
url: /es/system/string/endswith/
---
## String::EndsWith(const String\&) const method


Comprueba si la cadena termina con la subcadena especificada.

```cpp
bool System::String::EndsWith(const String &value) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Cadena a buscar. |

### Return Value

true si la cadena termina con la subcadena especificada, false en caso contrario.

## String::EndsWith(const String\&, System::StringComparison) const method


Comprueba si la cadena termina con la subcadena especificada.

```cpp
bool System::String::EndsWith(const String &value, System::StringComparison comparisonType) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Cadena a buscar. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | modo [Comparison](../../comparison/), vea [System::StringComparison](../../stringcomparison/) para obtener más información. |

### Return Value

true si la cadena termina con la subcadena especificada, false en caso contrario.

## String::EndsWith(const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) const method


Comprueba si la cadena termina con la subcadena especificada.

```cpp
bool System::String::EndsWith(const String &value, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &culture=nullptr) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Cadena a buscar. |
| ignoreCase | **bool** | Especifica si la comparación es insensible a mayúsculas. |
| culture | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura a usar al realizar la comparación de cadenas. |

### Return Value

true si la cadena termina con la subcadena especificada, false en caso contrario.

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)