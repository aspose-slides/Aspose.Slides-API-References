---
title: CreateSignature()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί την υπογραφή για τα καθορισμένα δεδομένα.
type: docs
weight: 1
url: /el/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) μέθοδος

Δημιουργεί την υπογραφή για τα καθορισμένα δεδομένα.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) για να υπολογίσετε το hash. |

### Τιμή Επιστροφής

Υπολογισμένη υπογραφή σε μορφή πίνακα byte.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) μέθοδος

Δημιουργεί την υπογραφή για την καθορισμένη τιμή κατακερματισμού.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Αλγόριθμος κατακερματισμού για χρήση κατά τη δημιουργία της υπογραφής. |

### Τιμή Επιστροφής

Υπολογισμένη υπογραφή σε μορφή πίνακα byte.

## Δείτε Επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [AsymmetricSignatureFormatter](../)
* Κλάση [HashAlgorithm](../../hashalgorithm/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)