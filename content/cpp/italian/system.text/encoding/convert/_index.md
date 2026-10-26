---
title: Convert()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte byte tra due codifiche.
type: docs
weight: 378
url: /it/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metodo

Converte byte tra due codifiche.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codifica di origine. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codifica di destinazione. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte da convertire. |

### Valore di ritorno

Byte convertiti.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metodo

Converte byte tra due codifiche.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codifica di origine. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Codifica di destinazione. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte da convertire. |
| index | int | Inizio della porzione. |
| count | int | Dimensione della porzione. |

### Valore di ritorno

Byte convertiti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)