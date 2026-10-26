---
title: GetProductLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena pasada desde el índice especificado a una instancia de la clase ProductHeaderValue.
type: docs
weight: 105
url: /es/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) método


Convierte una cadena pasada desde el índice especificado a una instancia de la clase [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Una instancia donde se asignará el objeto analizado. |

### Valor de retorno

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ProductHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)