---
title: TransformBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt een blok gegevens en kopieert de gegevens naar de uitvoerarray.
type: docs
weight: 66
url: /nl/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) methode

Verwerkt een blok data en kopieert de data naar de uitvoerarray.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om data te lezen van. |
| inputOffset | int | Offset van de invoerbuffer. |
| inputCount | int | Aantal bytes om te verwerken. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Uitvoertbuffer om data naartoe te kopiëren; nullptr om niet te kopiëren. |
| outputOffset | int | Offset van de uitvoerbuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [HashAlgorithm](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)