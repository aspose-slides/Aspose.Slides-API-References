---
title: TransformFinalBlock()
second_title: Aspose.Slides für C++ API-Referenz
description: Verarbeitet den letzten Datenblock und berechnet den Ausgabewert.
type: docs
weight: 14
url: /de/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) Methode

Verarbeitet den letzten Datenblock und berechnet den Ausgabewert.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Daten. |
| inputOffset | int | Offset des Eingabepuffers. |
| inputCount | int | Anzahl der zu verarbeitenden Bytes. |

### Rückgabewert

Ausgabe, die für die gesamte Eingabesequenz berechnet wird.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)