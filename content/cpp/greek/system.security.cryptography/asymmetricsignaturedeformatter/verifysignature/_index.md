---
title: VerifySignature()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επαληθεύει την υπογραφή στα δεδομένα.
type: docs
weight: 27
url: /el/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) μέθοδος

Επαληθεύει την υπογραφή στα δεδομένα.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) υπογεγραμμένο με **rgbSignature**. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Υπογραφή που πρέπει να επαληθευτεί για τα δεδομένα. |

### Τιμή επιστροφής

Αληθές αν η επαλήθευση της υπογραφής είναι επιτυχής, ψευδές διαφορετικά.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) μέθοδος

Επαληθεύει την υπογραφή στα δεδομένα. Δεν έχει υλοποιηθεί.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | Αλγόριθμος για χρήση στην κατακερματοποίηση. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Υπογραφή που πρέπει να επαληθευτεί για τα δεδομένα. |

### Τιμή επιστροφής

Αληθές αν η επαλήθευση της υπογραφής είναι επιτυχής, ψευδές διαφορετικά.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureDeformatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)