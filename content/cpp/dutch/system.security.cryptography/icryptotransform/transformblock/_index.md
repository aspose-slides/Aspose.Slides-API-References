---
title: TransformBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt een blok gegevens en kopieert de gegevens naar de uitvoer-array.
type: docs
weight: 1
url: /nl/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) methode

Verwerkt een gegevensblok en kopieert de gegevens naar de uitvoer-array.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om gegevens van te lezen. |
| inputOffset | int | Offset van inputBuffer. |
| inputCount | int | Aantal bytes om te verwerken. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Output buffer om gegevens naartoe te kopiëren; nullptr om niets te kopiëren. |
| outputOffset | int | Offset van outputBuffer. |

### Retourwaarde

Aantal geschreven bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)