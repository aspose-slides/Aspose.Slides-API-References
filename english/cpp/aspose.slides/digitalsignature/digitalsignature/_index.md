---
title: DigitalSignature()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new DigitalSignature object with the specified certificate.
type: docs
weight: 66
url: /cpp/aspose.slides/digitalsignature/digitalsignature/
---
## DigitalSignature::DigitalSignature([System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\>) constructor


Creates a new [DigitalSignature](../) object with the specified certificate.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::SharedPtr<System::Security::Cryptography::X509Certificates::X509Certificate2> certificate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | [System::SharedPtr](../../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)\> | Certificate that will be used to sign the presentation. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509Certificate2](../../../system.security.cryptography.x509certificates/x509certificate2/)
* Class [DigitalSignature](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## DigitalSignature::DigitalSignature([System::String](../../../system/string/), [System::String](../../../system/string/)) constructor


Creates a new [DigitalSignature](../) object with the specified certificate file path and password.

```cpp
Aspose::Slides::DigitalSignature::DigitalSignature(System::String filePath, System::String password)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | [System::String](../../../system/string/) | Path to the file with certificate. |
| password | [System::String](../../../system/string/) | Password required to access certificate. |

## See Also

* Class [String](../../../system/string/)
* Class [DigitalSignature](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
