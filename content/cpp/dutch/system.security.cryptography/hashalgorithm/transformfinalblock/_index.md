---
title: TransformFinalBlock()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwerkt het laatste blok gegevens en berekent de hash.
type: docs
weight: 79
url: /nl/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) methode

Verwerkt het laatste blok gegevens en berekent de hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) om gegevens te lezen. |
| inputOffset | int | Offset van de invoerbuffer. |
| inputCount | int | Aantal bytes om te verwerken. |

### Retourwaarde

Hash berekend voor de volledige gegevensreeks.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [HashAlgorithm](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)