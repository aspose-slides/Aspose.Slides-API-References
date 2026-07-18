---
title: TransformBlock()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επεξεργάζεται μπλοκ δεδομένων και αντιγράφει τα δεδομένα σε πίνακα εξόδου.
type: docs
weight: 1
url: /el/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) μέθοδος


Processes block of data and copies data to output array.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων από. |
| inputOffset | int | Μετατόπιση του buffer εισόδου. |
| inputCount | int | Αριθμός byte προς επεξεργασία. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer εξόδου για αντιγραφή δεδομένων· nullptr για να μην γίνει αντιγραφή. |
| outputOffset | int | Μετατόπιση του buffer εξόδου. |

### Return Value

Αριθμός byte που γράφτηκαν.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICryptoTransform](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)