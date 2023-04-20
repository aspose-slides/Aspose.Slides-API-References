---
title: GetNameInfo()
second_title: Aspose.Slides for C++ API Reference
description: Gets subject or issuer name from certificate.
type: docs
weight: 248
url: /cpp/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method


Gets subject or issuer name from certificate.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Name formatting options. |
| for_issuer | **bool** | If true, returns issuer name, else returns subject name. |

### Return Value

Formatted issuer or subject name.

## See Also

* Enum [X509NameType](../../x509nametype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)