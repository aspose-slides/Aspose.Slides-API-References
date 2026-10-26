---
title: GetTransferCodingLength()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte una cadena pasada desde el índice especificado a una instancia de la clase TransferCodingHeaderValue.
type: docs
weight: 105
url: /es/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) método

Convierte una cadena pasada desde el índice especificado a una instancia de la clase [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [String](../../../system/string/) | Una cadena para analizar. |
| startIndex | **int32_t** | Una posición inicial para el análisis. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Una instancia donde se asignará un objeto analizado. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | El delegado que se usa para crear instancias de la clase [TransferCodingHeaderValue](../). |

### Valor devuelto

Devuelve la longitud de una subcadena analizada, de lo contrario 0.

## Ver también

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [TransferCodingHeaderValue](../)
* Espacio de nombres [System::Net::Http::Headers](../../)
* Biblioteca [Aspose.Slides](../../../)