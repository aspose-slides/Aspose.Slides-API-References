---
title: TransformFinalBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt het laatste gegevensblok en berekent de uitvoerwaarde.
type: docs
weight: 14
url: /nl/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) methode

Verwerkt het laatste gegevensblok en berekent de uitgangswaarde.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om gegevens van te lezen. |
| inputOffset | int | Offset van de invoerbuffer. |
| inputCount | int | Aantal te verwerken bytes. |

### Retourwaarde

Uitvoer berekend voor de volledige invoersequentie.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)