---
title: VerifySignature()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Επαληθεύει την υπογραφή του hash των δεδομένων.
type: docs
weight: 40
url: /el/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


Επαληθεύει την υπογραφή του hash των δεδομένων.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Hash που υπολογίστηκε για τα δεδομένα. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Υπογραφή που ελήφθη για τα δεδομένα. |

### Τιμή Επιστροφής

Αληθές αν η υπογραφή είναι έγκυρη, ψευδές αλλιώς.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [RSAPKCS1SignatureDeformatter](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)