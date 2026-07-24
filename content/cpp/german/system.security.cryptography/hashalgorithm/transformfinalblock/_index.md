---
title: TransformFinalBlock()
second_title: Aspose.Slides für C++ API Referenz
description: Verarbeitet den letzten Datenblock und berechnet den Hash.
type: docs
weight: 79
url: /de/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method

Verarbeitet den letzten Datenblock und berechnet den Hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Daten. |
| inputOffset | int | Offset des Eingabepuffers. |
| inputCount | int | Anzahl der zu verarbeitenden Bytes. |

### Rückgabewert

Für die gesamte Datenfolge berechneter Hash.

## Siehe auch

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klasse [HashAlgorithm](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)