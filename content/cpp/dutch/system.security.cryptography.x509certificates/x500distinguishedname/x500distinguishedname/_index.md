---
title: X500DistinguishedName()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor.
type: docs
weight: 1
url: /nl/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) die een distinguished name vertegenwoordigt. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Geëncodeerde distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor


Copy-constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Distinguished name om data van te kopiëren. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished name. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Bitgewijs gecombineerde vlaggen die de eigenschappen van het bouwen van de naam specificeren. |

## Zie ook

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)