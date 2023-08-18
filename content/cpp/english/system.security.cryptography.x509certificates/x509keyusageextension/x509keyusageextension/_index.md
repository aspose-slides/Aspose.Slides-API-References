---
title: X509KeyUsageExtension()
second_title: Aspose.Slides for C++ API Reference
description: Default constructor.
type: docs
weight: 1
url: /system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() constructor


Default constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Encoded data of key usages. |
| critical | **bool** | Criticality sign. |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | Key usages. |
| critical | **bool** | Criticality sign. |

## See Also

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509KeyUsageExtension](../)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)