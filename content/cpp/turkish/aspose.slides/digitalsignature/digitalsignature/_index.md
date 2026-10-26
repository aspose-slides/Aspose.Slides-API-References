---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sertifika ile yeni bir DigitalSignature nesnesi oluşturur.
type: docs
weight: 66
url: /tr/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature(System::SharedPtr\<System::Security::Cryptography::X509Certificates::X509Certificate2\>) yapıcı

Belirtilen sertifika ile yeni bir [DigitalSignature](../) nesnesi oluşturur.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Sunumu imzalamak için kullanılacak sertifika. |

## DigitalSignature::DigitalSignature(System::String, System::String) yapıcı

Belirtilen sertifika dosya yolu ve şifre ile yeni bir [DigitalSignature](../) nesnesi oluşturur.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Sertifika içeren dosyanın yolu. |
| password | [System::String](../../../system/string/) | Sertifikaya erişmek için gerekli şifre. |

## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Sınıf [DigitalSignature](../)
* Sınıf [String](../../../system/string/)
* İsimAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)