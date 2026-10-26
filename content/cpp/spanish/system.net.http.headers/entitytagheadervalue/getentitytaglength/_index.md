---
title: GetEntityTagLength()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte una cadena pasada desde el índice especificado a una instancia de la clase EntityTagHeaderValue.
type: docs
weight: 118
url: /es/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) método

Convierte una cadena pasada desde el índice especificado a una instancia de la clase [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Una instancia donde se asignará un objeto analizado. |

### Valor de retorno

La longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [EntityTagHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)