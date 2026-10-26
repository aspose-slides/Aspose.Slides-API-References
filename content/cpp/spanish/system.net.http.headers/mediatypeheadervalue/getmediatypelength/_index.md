---
title: GetMediaTypeLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena proporcionada a partir del índice especificado en una instancia de la clase MediaTypeHeaderValue.
type: docs
weight: 144
url: /es/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) method

Convierte una cadena proporcionada a partir del índice especificado en una instancia de la clase [MediaTypeHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | El delegado que se utiliza para crear instancias de la clase [MediaTypeHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | Una instancia donde se asignará el objeto analizado. |

### Valor de retorno

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [MediaTypeHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)