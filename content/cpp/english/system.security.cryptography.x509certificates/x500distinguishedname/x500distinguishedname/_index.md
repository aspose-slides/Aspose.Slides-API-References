---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API Reference
description: Constructor.
type: docs
weight: 1
url: /system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) representing distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Encoded distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor


Copy constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Distinguished name to copy data from. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Bitwise-combined flags specifying name building properties. |

## See Also

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)