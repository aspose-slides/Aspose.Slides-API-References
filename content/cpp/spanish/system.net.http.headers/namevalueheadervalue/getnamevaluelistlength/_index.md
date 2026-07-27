---
title: GetNameValueListLength()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte una cadena pasada desde el índice especificado a la colección de instancias de la clase NameValueHeaderValue-class y devuelve la longitud de una subcadena analizada.
type: docs
weight: 131
url: /es/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) método


Convierte una cadena pasada desde el índice especificado a la colección de instancias de la clase NameValueHeaderValue-class y devuelve la longitud de una subcadena analizada.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| delimiter | char16_t | Una cadena que se usa para delimitar elementos en la cadena especificada. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | El parámetro de salida donde se asignará una colección analizada. |

### Valor de retorno

La longitud de una subcadena analizada.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [ObjectCollection](../../objectcollection/)
* Clase [NameValueHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)