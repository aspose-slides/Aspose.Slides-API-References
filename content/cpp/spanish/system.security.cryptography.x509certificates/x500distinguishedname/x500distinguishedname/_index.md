---
title: X500DistinguishedName()
second_title: Referencia de API de Aspose.Slides para C++
description: Constructor.
type: docs
weight: 1
url: /es/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) que representa el nombre distinguido. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nombre distinguido codificado. |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nombre distinguido. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor


Copy constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Nombre distinguido del que copiar los datos. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor


Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nombre distinguido. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Banderas combinadas bit a bit que especifican las propiedades de construcción del nombre. |

## Ver también

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)