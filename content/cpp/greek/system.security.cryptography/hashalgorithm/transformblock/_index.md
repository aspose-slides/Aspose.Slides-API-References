---
title: TransformBlock()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επεξεργάζεται ένα μπλοκ δεδομένων και αντιγράφει τα δεδομένα στον πίνακα εξόδου.
type: docs
weight: 66
url: /el/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) μέθοδος

Επεξεργάζεται ένα μπλοκ δεδομένων και αντιγράφει τα δεδομένα στον πίνακα εξόδου.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων από. |
| inputOffset | int | Μετατόπιση buffer εισόδου. |
| inputCount | int | Αριθμός byte προς επεξεργασία. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer εξόδου για αντιγραφή δεδομένων· nullptr για να μη γίνει αντιγραφή. |
| outputOffset | int | Μετατόπιση buffer εξόδου. |

### Τιμή Επιστροφής

Αριθμός byte που γράφτηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)