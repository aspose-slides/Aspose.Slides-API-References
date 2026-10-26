---
title: TransformFinalBlock()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επεξεργάζεται το τελευταίο μπλοκ δεδομένων και υπολογίζει την τιμή εξόδου.
type: docs
weight: 14
url: /el/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Επεξεργάζεται το τελευταίο μπλοκ δεδομένων και υπολογίζει την τιμή εξόδου.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) για ανάγνωση δεδομένων από. |
| inputOffset | int | Μετατόπιση του buffer εισόδου. |
| inputCount | int | Αριθμός bytes προς επεξεργασία. |

### Τιμή Επιστροφής

Η έξοδος υπολογίζεται για ολόκληρη την ακολουθία εισόδου.

## Δείτε επίσης

* typedef [ArrayPtr](../../../system/arrayptr/)
* κλάση [ICryptoTransform](../)
* χώρος ονομάτων [System::Security::Cryptography](../../)
* βιβλιοθήκη [Aspose.Slides](../../../)