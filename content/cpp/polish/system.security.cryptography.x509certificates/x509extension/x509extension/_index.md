---
title: X509Extension()
second_title: Aspose.Slides dla referencji API C++
description: Konstruktor.
type: docs
weight: 1
url: /pl/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Zakodowane dane powiązane z certyfikatem. |
| critical | **bool** | Znacznik krytyczności. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) identyfikator powiązany z rozszerzeniem. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Surowe dane powiązane z certyfikatem. |
| critical | **bool** | Znacznik krytyczności. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) identyfikator powiązany z rozszerzeniem. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Surowe dane powiązane z certyfikatem. |
| critical | **bool** | Znacznik krytyczności. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klasa [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Klasa [X509Extension](../)
* Klasa [Oid](../../../system.security.cryptography/oid/)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Security::Cryptography::X509Certificates](../../)
* Biblioteka [Aspose.Slides](../../../)