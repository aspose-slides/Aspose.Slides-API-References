---
title: X500DistinguishedName()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/x500distinguishedname/x500distinguishedname/
---
## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<AsnEncodedData\>\&) constructor

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<AsnEncodedData> &encoded_distinguished_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoded_distinguished_name | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | [Object](../../../system/object/) 表示的可分辨名称。 |

## X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr\&) constructor

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const ByteArrayPtr &encoded_distinguished_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoded_distinguished_name | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 已编码的可分辨名称。 |

## X500DistinguishedName::X500DistinguishedName(const String\&) constructor

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 可分辨名称。 |

## X500DistinguishedName::X500DistinguishedName(const SharedPtr\<X500DistinguishedName\>\&) constructor

复制构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const SharedPtr<X500DistinguishedName> &distinguishedName)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| distinguishedName | const [SharedPtr](../../../system/sharedptr/)\<[X500DistinguishedName](../)\>\& | 用于复制数据的可分辨名称。 |

## X500DistinguishedName::X500DistinguishedName(const String\&, X500DistinguishedNameFlags) constructor

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X500DistinguishedName::X500DistinguishedName(const String &distinguished_name, X500DistinguishedNameFlags flags)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| distinguished_name | const [String](../../../system/string/)\& | 可分辨名称。 |
| flags | [X500DistinguishedNameFlags](../../x500distinguishednameflags/) | 按位组合的标志，用于指定名称构建属性。 |

## 另请参阅

* Enum [X500DistinguishedNameFlags](../../x500distinguishednameflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Class [X500DistinguishedName](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)