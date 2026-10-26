---
title: X500DistinguishedName()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktor.
type: docs
weight: 1
url: /sv/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) som representerar ett distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodat distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const String\&) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) konstruktor


Kopieringskonstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Distinguished name att kopiera data från. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) konstruktor


Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Bitvis kombinerade flaggor som specificerar egenskaper för namnbyggnad. |

## Se även

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Klass [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Klass [X500DistinguishedName](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)