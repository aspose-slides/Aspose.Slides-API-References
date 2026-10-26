---
title: X509Extension()
second_title: Aspose.Slides C++ API referenciája
description: Konstruktor.
type: docs
weight: 1
url: /hu/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | A tanúsítvánnyal kapcsolatos kódolt adat. |
| critical | **bool** | Kritikus jel. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) azonosító, amely a kiegészítőhöz tartozik. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítvánnyal kapcsolatos nyers adat. |
| critical | **bool** | Kritikus jel. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) azonosító, amely a kiegészítőhöz tartozik. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | A tanúsítvánnyal kapcsolatos nyers adat. |
| critical | **bool** | Kritikus jel. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Osztály [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Osztály [X509Extension](../)
* Osztály [Oid](../../../system.security.cryptography/oid/)
* Osztály [String](../../../system/string/)
* Névtér [System::Security::Cryptography::X509Certificates](../../)
* Könyvtár [Aspose.Slides](../../../)