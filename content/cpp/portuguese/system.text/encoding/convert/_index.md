---
title: Convert()
second_title: Referência da API Aspose.Slides para C++
description: Converte bytes entre duas codificações.
type: docs
weight: 378
url: /pt/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) método


Converte bytes entre duas codificações.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificação de origem. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificação de destino. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes a serem convertidos. |

### Valor de Retorno

Bytes convertidos.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) método


Converte bytes entre duas codificações.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificação de origem. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codificação de destino. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytes a serem convertidos. |
| index | int | Início da fatia. |
| count | int | Tamanho da fatia. |

### Valor de Retorno

Bytes convertidos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Classe [Encoding](../)
* Espaço de nomes [System::Text](../../)
* Library [Aspose.Slides](../../../)