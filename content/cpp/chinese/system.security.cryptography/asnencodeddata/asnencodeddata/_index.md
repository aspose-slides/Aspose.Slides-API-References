---
title: AsnEncodedData()
second_title: Aspose.Slides C++ API 参考
description: 拷贝构造函数。
type: docs
weight: 1
url: /zh/system.security.cryptography/asnencodeddata/asnencodeddata/
---
## AsnEncodedData::AsnEncodedData(const SharedPtr\<AsnEncodedData\>\&) 构造函数


拷贝构造函数。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<AsnEncodedData> &asn_encoded_data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| asn_encoded_data | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../)\>\& | [Object](../../../system/object/) 用于从中复制数据。 |

## AsnEncodedData::AsnEncodedData(const ByteArrayPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const ByteArrayPtr &raw_data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 原始字节格式的编码数据。 |

## AsnEncodedData::AsnEncodedData(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../oid/)\>\& | [Object](../../../system/object/) 标识已编码数据的标识符。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 原始字节格式的编码数据。 |

## AsnEncodedData::AsnEncodedData(const String\&, const ByteArrayPtr\&) 构造函数


构造函数。

```cpp
System::Security::Cryptography::AsnEncodedData::AsnEncodedData(const String &oid, const ByteArrayPtr &raw_data)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) 标识已编码数据的标识符。 |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 原始字节格式的编码数据。 |

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ByteArrayPtr](../../../system/bytearrayptr/)
* 类 [AsnEncodedData](../)
* 类 [Oid](../../oid/)
* 类 [String](../../../system/string/)
* 命名空间 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)