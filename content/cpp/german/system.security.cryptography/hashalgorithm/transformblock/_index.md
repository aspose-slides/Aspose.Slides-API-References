---
title: TransformBlock()
second_title: Aspose.Slides für C++ API Referenz
description: Verarbeitet einen Datenblock und kopiert die Daten in das Ausgabearray.
type: docs
weight: 66
url: /de/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) Methode

Verarbeitet einen Datenblock und kopiert die Daten in das Ausgabearray.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen der Daten. |
| inputOffset | int | Versatz des Eingabepuffers. |
| inputCount | int | Anzahl der zu verarbeitenden Bytes. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ausgabepuffer, in den die Daten kopiert werden; nullptr, um kein Kopieren durchzuführen. |
| outputOffset | int | Versatz des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## Siehe auch

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klasse [HashAlgorithm](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)