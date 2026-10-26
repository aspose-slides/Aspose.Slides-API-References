---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert bytes tussen twee coderingen.
type: docs
weight: 378
url: /nl/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) methode


Converteert bytes tussen twee coderingen.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Broncodering. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Doelcode. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Te converteren bytes. |

### Retourwaarde

Geconverteerde bytes.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) methode


Converteert bytes tussen twee coderingen.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Broncodering. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Doelcode. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Te converteren bytes. |
| index | int | Begin van slice. |
| count | int | Grootte van slice. |

### Retourwaarde

Geconverteerde bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)