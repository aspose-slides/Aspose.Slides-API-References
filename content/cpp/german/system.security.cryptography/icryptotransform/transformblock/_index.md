---
title: TransformBlock()
second_title: Aspose.Slides für C++ API-Referenz
description: Verarbeitet einen Datenblock und kopiert die Daten in das Ausgabearray.
type: docs
weight: 1
url: /de/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) Methode


Verarbeitet einen Datenblock und kopiert die Daten in das Ausgabearray.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen von Daten. |
| inputOffset | int | Versatz des Eingabepuffers. |
| inputCount | int | Anzahl der zu verarbeitenden Bytes. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ausgabepuffer, in den Daten kopiert werden; nullptr, um nicht zu kopieren. |
| outputOffset | int | Versatz des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)