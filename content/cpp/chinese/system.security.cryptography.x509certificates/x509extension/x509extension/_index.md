---
title: X509Extension()
second_title: Aspose.Slides for C++ API 参考
description: 构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) 构造函数

构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | 与证书关联的编码数据。 |
| critical | **bool** | 关键性标志。 |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) 标识符与扩展关联。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 与证书关联的原始数据。 |
| critical | **bool** | 关键性标志。 |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) 构造函数


构造函数。

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 标识符与扩展关联。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 与证书关联的原始数据。 |
| critical | **bool** | 关键性标志。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* 类 [X509Extension](../)
* 类 [Oid](../../../system.security.cryptography/oid/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Security::Cryptography::X509Certificates](../../)
* 库 [Aspose.Slides](../../../)