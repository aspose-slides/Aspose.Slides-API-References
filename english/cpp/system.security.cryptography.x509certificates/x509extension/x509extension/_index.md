---
title: X509Extension()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /cpp/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\&, **bool**) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Encoded data associated with certificate. |
| critical | **bool** | Criticality sign. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X509Extension](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)
## X509Extension::X509Extension(const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, **bool**) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identifier associated with extension. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Raw data associated with certificate. |
| critical | **bool** | Criticality sign. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Oid](../../../system.security.cryptography/oid/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Extension](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)
## X509Extension::X509Extension(const [String](../../../system/string/)\&, const [ByteArrayPtr](../../../system/bytearrayptr/)\&, **bool**) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifier associated with extension. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Raw data associated with certificate. |
| critical | **bool** | Criticality sign. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [X509Extension](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)
