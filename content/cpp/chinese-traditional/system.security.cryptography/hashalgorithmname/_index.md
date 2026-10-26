---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API 參考
description: "表示雜湊演算法名稱的字串。此類型應在堆疊上配置，並以值或引用方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 755
url: /zh-hant/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName 結構

[String](../../system/string/) 表示雜湊演算法的名稱。此類型應於堆疊上分配，並以值或引用方式傳遞給函式。切勿使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此類型的物件。

```cpp
class HashAlgorithmName
```

## Methods

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | 從 OID 值建立 [HashAlgorithmName](./)。 |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | 取得一個代表 [MD5](../md5/) 的 [HashAlgorithmName](./)。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 取得演算法名稱的字串表示。 |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | 取得一個代表 [SHA1](../sha1/) 的 [HashAlgorithmName](./)。 |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | 取得一個代表 [SHA256](../sha256/) 的 [HashAlgorithmName](./)。 |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | 取得一個代表 [SHA384](../sha384/) 的 [HashAlgorithmName](./)。 |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | 取得一個代表 [SHA512](../sha512/) 的 [HashAlgorithmName](./)。 |
| int [GetHashCode](./gethashcode/)() const |  |
| [HashAlgorithmName](./hashalgorithmname/)() |  |
| [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | 建構函式。 |
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
| [String](../../system/string/) [ToString](./tostring/)() const | 取得演算法名稱的字串表示。 |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | 嘗試從 OID 值建立 [HashAlgorithmName](./)。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | 傳回表示 [TimeSpan](../../system/timespan/) 結構的 [TypeInfo](../../system/typeinfo/) 物件。 |

## See Also

* 命名空間 [System::Security::Cryptography](../)
* 程式庫 [Aspose.Slides](../../)