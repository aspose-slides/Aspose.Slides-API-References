---
title: CreateEncryptor()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί κρυπτοποιητή με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου.
type: docs
weight: 183
url: /el/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() μέθοδος

Δημιουργεί κρυπτοποιητή με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### Τιμή Επιστροφής

Νέο δημιουργημένο αντικείμενο κρυπτοποιητή.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) μέθοδος

Δημιουργεί κρυπτοποιητή με ρητές παραμέτρους.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Κλειδί προς χρήση. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Αρχική τιμή προς χρήση. |

### Τιμή Επιστροφής

Νέο δημιουργημένο αντικείμενο κρυπτοποιητή.

## Δείτε επίσης

* Τύπος Ορισμού [SharedPtr](../../../system/sharedptr/)
* Τύπος Ορισμού [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICryptoTransform](../../icryptotransform/)
* Κλάση [SymmetricAlgorithm](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)