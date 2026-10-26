---
title: TransformBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt een blok gegevens en kopieert de gegevens naar de uitvoerarray.
type: docs
weight: 53
url: /nl/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) methode


Verwerkt een blok gegevens en kopieert de gegevens naar de uitvoerarray.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om gegevens van te lezen. |
| inputOffset | **int32_t** | Offset van de invoerbuffer. |
| inputCount | **int32_t** | Aantal bytes om te verwerken. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Uitvoerbuffer om gegevens naar te kopiëren; nullptr om niet te kopiëren. |
| outputOffset | **int32_t** | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ToBase64Transform](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)