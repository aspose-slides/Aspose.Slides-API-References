---
title: CreateDecryptor()
second_title: Aspose.Slides για C++ API Reference
description: Δημιουργεί αποκρυπτογράφο με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου.
type: docs
weight: 196
url: /el/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() μέθοδος

Δημιουργεί αποκρυπτογράφο με παραμέτρους που σχετίζονται με το αντικείμενο αλγορίθμου.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Τιμή Επιστροφής

Νέο δημιουργημένο αντικείμενο αποκρυπτογράφο.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) μέθοδος

Δημιουργεί αποκρυπτογράφο με ρητές παραμέτρους.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Κλειδί για χρήση. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Αρχική τιμή για χρήση. |

### Τιμή Επιστροφής

Νέο δημιουργημένο αντικείμενο αποκρυπτογράφο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [ICryptoTransform](../../icryptotransform/)
* Κλάση [SymmetricAlgorithm](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)