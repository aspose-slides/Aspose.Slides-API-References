---
title: X509Extension()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktor.
type: docs
weight: 1
url: /sv/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Kodad data associerad med certifikat. |
| critical | **bool** | Kritikalitetstecken. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identifier associerad med tillägget. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Rådata associerad med certifikat. |
| critical | **bool** | Kritikalitetstecken. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identifier associerad med tillägget. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Rådata associerad med certifikat. |
| critical | **bool** | Kritikalitetstecken. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Klass [X509Extension](../)
* Klass [Oid](../../../system.security.cryptography/oid/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)