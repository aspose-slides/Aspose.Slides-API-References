---
title: DigitalSignature()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο πιστοποιητικό.
type: docs
weight: 66
url: /el/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) constructor

Δημιουργεί ένα νέο [DigitalSignature](../) αντικείμενο με το καθορισμένο πιστοποιητικό.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Πιστοποιητικό που θα χρησιμοποιηθεί για την υπογραφή της παρουσίασης. |

## DigitalSignature::DigitalSignature(System::String, System::String) constructor

Δημιουργεί ένα νέο [DigitalSignature](../) αντικείμενο με το καθορισμένο μονοπάτι αρχείου πιστοποιητικού και κωδικό πρόσβασης.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Διαδρομή προς το αρχείο με το πιστοποιητικό. |
| password | [System::String](../../../system/string/) | Κωδικός πρόσβασης που απαιτείται για την πρόσβαση στο πιστοποιητικό. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Κλάση [DigitalSignature](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)