---
title: X500DistinguishedName()
second_title: Referência da API Aspose.Slides para C++
description: Construtor.
type: docs
weight: 1
url: /pt/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) representando o nome distinto. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Nome distinto codificado. |

## X500DistinguishedName::X500DistinguishedName(const String\&) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nome distinto. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) construtor

Construtor de cópia.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Nome distinto de onde copiar os dados. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) construtor

Construtor.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Nome distinto. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Flags combinadas por operações bit a bit que especificam propriedades de construção de nome. |

## Veja Também

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Classe [X500DistinguishedName](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)