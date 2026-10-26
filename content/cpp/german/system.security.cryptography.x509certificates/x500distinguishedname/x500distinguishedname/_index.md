---
title: X500DistinguishedName()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) repräsentiert den Distinguished Name. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kodierter Distinguished Name. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished Name. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor

Kopierkonstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Distinguished Name, von dem Daten kopiert werden. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Distinguished Name. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Bitweise kombinierte Flags, die Eigenschaften des Namensaufbaus spezifizieren. |

## Siehe auch

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)