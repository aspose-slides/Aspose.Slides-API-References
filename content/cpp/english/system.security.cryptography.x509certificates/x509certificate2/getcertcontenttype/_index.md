---
title: GetCertContentType()
second_title: Aspose.Slides for C++ API Reference
description: Gets the type of certificate contained in the specified byte array.
type: docs
weight: 391
url: /system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) method


Gets the type of certificate contained in the specified byte array.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Certificate data. |

### Return Value

Type of X.509 certificate.

## X509Certificate2::GetCertContentType(const String\&) method


Gets the type of certificate contained in the specified file.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Certificate file name. |

### Return Value

Type of X.509 certificate.

## See Also

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)