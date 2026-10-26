---
title: TransformBlock()
second_title: Aspose.Slides für C++ API Referenz
description: Verarbeitet einen Datenblock und kopiert die Daten in das Ausgabearray.
type: docs
weight: 53
url: /de/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method


Verarbeitet einen Block von Daten und kopiert Daten in das Ausgabearray.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) zum Lesen der Daten aus. |
| inputOffset | **int32_t** | Offset des Eingabepuffers. |
| inputCount | **int32_t** | Anzahl der zu verarbeitenden Bytes. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Ausgabepuffer, in den Daten kopiert werden; nullptr, um kein Kopieren durchzuführen. |
| outputOffset | **int32_t** | Offset des Ausgabepuffers. |

### Rückgabewert

Anzahl der geschriebenen Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ToBase64Transform](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)