---
title: TransformBlock()
second_title: Aspose.Slides για C++ API Reference
description: Επεξεργάζεται ένα μπλοκ δεδομένων και αντιγράφει τα δεδομένα στον πίνακα εξόδου.
type: docs
weight: 53
url: /el/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) μέθοδος

Επεξεργάζεται ένα μπλοκ δεδομένων και αντιγράφει τα δεδομένα στον πίνακα εξόδου.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων από. |
| inputOffset | **int32_t** | Μετατόπιση του buffer εισόδου. |
| inputCount | **int32_t** | Αριθμός bytes προς επεξεργασία. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer εξόδου για αντιγραφή δεδομένων· nullptr για απουσία αντιγραφής. |
| outputOffset | **int32_t** | Μετατόπιση buffer εξόδου. |

### Τιμή επιστροφής

Αριθμός bytes που γράφτηκαν.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ToBase64Transform](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)