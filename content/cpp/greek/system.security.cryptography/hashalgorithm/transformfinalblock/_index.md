---
title: TransformFinalBlock()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επεξεργάζεται το τελευταίο μπλοκ δεδομένων και υπολογίζει το hash.
type: docs
weight: 79
url: /el/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Επεξεργάζεται το τελευταίο μπλοκ δεδομένων και υπολογίζει το hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων από. |
| inputOffset | int | Μετατόπιση buffer εισόδου. |
| inputCount | int | Αριθμός bytes για επεξεργασία. |

### Τιμή Επιστροφής

Το hash υπολογίζεται για ολόκληρη τη σειρά δεδομένων.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [HashAlgorithm](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)