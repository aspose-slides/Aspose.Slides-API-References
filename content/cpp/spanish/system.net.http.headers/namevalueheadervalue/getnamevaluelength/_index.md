---
title: GetNameValueLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena proporcionada desde el índice especificado a una instancia de la clase NameValueHeaderValue.
type: docs
weight: 118
url: /es/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) método

Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Una instancia donde se asignará un objeto analizado. |

### Valor devuelto

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) método

Convierte una cadena pasada desde el índice especificado a una instancia de la clase [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Una función que se usa para crear nuevas instancias de la clase [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Una instancia donde se asignará un objeto analizado. |

### Valor devuelto

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Clase [String](../../../system/string/)
* Clase [NameValueHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)