---
title: X500DistinguishedName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) représentant le nom distinctif. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nom distinctif encodé. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nom distinctif. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructeur

Constructeur de copie.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Nom distinctif à copier les données depuis. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructeur

Constructeur.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nom distinctif. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Indicateurs combinés par opérateur binaire spécifiant les propriétés de construction du nom. |

## Voir aussi

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Classe [X500DistinguishedName](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../../)
* Bibliothèque [Aspose.Slides](../../../)