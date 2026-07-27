---
title: GetCacheControlLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena pasada desde el índice especificado a una instancia de la clase CacheControlHeaderValue.
type: docs
weight: 456
url: /es/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) método

Convierte una cadena pasada desde el índice especificado a una instancia de la clase [CacheControlHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena a analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | Un valor que debe añadirse al objeto analizado. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | Una instancia donde se asignará un objeto analizado. |

### Valor de retorno

La longitud de una subcadena analizada, o 0 en caso contrario.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [CacheControlHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)