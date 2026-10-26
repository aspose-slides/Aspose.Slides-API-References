---
title: HashAlgorithmName
second_title: Aspose.Slides C++ API 参考
description: "表示哈希算法名称的字符串。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 755
url: /zh/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName 结构体


[String](../../system/string/) 表示哈希算法的名称。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class HashAlgorithmName
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | 从 OID 值创建 [HashAlgorithmName](./)。 |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | 获取一个 [HashAlgorithmName](./)，表示 [MD5](../md5/)。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 获取算法名称的字符串表示。 |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | 获取一个 [HashAlgorithmName](./)，表示 [SHA1](../sha1/)。 |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | 获取一个 [HashAlgorithmName](./)，表示 [SHA256](../sha256/)。 |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | 获取一个 [HashAlgorithmName](./)，表示 [SHA384](../sha384/)。 |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | 获取一个 [HashAlgorithmName](./)，表示 [SHA512](../sha512/)。 |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | 构造函数。 |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | 获取算法名称的字符串表示。 |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | 尝试从 OID 值创建 [HashAlgorithmName](./)。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | 返回一个表示 [TimeSpan](../../system/timespan/) 结构的 [TypeInfo](../../system/typeinfo/) 对象。 |

## 另请参阅

* 命名空间 [System::Security::Cryptography](../)
* 库 [Aspose.Slides](../../)