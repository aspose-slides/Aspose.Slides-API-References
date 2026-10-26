---
title: X500DistinguishedName()
second_title: Справочник API Aspose.Slides для C++
description: Конструктор.
type: docs
weight: 1
url: /ru/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) представляющий отличительное имя. |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Закодированное отличительное имя. |

## X500DistinguishedName::X500DistinguishedName(const String\&) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Отличительное имя. |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) конструктор

Конструктор копирования.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | Отличительное имя, из которого копируются данные. |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) конструктор

Конструктор.

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | Отличительное имя. |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | Битовыми комбинациями флагов, определяющих свойства построения имени. |

## См. также

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)