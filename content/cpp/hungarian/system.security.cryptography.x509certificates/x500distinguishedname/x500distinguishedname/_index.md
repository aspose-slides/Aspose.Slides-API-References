---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API referencia
description: Konstruktor.
type: docs
weight: 1
url: /hu/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) a megkülönböztetett nevet ábrázolja. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Kódolt megkülönböztetett név. |

## X500DistinguishedName::X500DistinguishedName(const String\&) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Megkülönböztetett név. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) konstruktor

Másoló konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Megkülönböztetett név, amelyből az adat másolódik. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) konstruktor

Konstruktor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Megkülönböztetett név. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Bitenként kombinált jelzők, amelyek a névépítés tulajdonságait határozzák meg. |

## Lásd még

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)