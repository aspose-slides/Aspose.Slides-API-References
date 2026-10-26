---
title: GetRangeItemListLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena pasada desde la posición especificada a la colección de instancias de la clase RangeItemHeaderValue.
type: docs
weight: 79
url: /es/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) método

Convierte una cadena pasada desde la posición especificada a la colección de instancias de la clase RangeItemHeaderValue.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena a analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | Una instancia donde se asignará una colección analizada. |

### Valor de retorno

La longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ICollection](../../../system.collections.generic/icollection/)
* Clase [RangeItemHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)