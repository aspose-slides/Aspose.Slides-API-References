---
title: X500DistinguishedName()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore.
type: docs
weight: 1
url: /it/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) che rappresenta il nome distinto. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nome distinto codificato. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nome distinto. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor


Costruttore di copia.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Nome distinto da cui copiare i dati. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor


Costruttore.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nome distinto. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Flag combinate a livello di bit che specificano le proprietà di costruzione del nome. |

## Vedi anche

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Classe [X500DistinguishedName](../)
* Classe [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Libreria [Aspose.Slides](../../../)