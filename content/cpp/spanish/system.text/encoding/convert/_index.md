---
title: Convert()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte bytes entre dos codificaciones.
type: docs
weight: 378
url: /es/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) método

Convierte bytes entre dos codificaciones.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificación de origen. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificación de destino. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes a convertir. |

### Valor devuelto

Bytes convertidos.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) método

Convierte bytes entre dos codificaciones.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificación de origen. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificación de destino. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes a convertir. |
| index | int | Comienzo del fragmento. |
| count | int | Tamaño del fragmento. |

### Valor devuelto

Bytes convertidos.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Clase [Encoding](../)
* Espacio de nombres [System::Text](../../)
* Biblioteca [Aspose.Slides](../../../)