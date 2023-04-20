---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API Reference
description: "String representing the name of a hash algorithm. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 755
url: /cpp/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct


[String](../../system/string/) representing the name of a hash algorithm. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class HashAlgorithmName
```

## Methods

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | Create [HashAlgorithmName](./) from OID-value. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | Gets a [HashAlgorithmName](./) representing [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | Gets string representation of the algorithm name. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | Gets a [HashAlgorithmName](./) representing [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | Gets a [HashAlgorithmName](./) representing [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | Gets a [HashAlgorithmName](./) representing [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | Gets a [HashAlgorithmName](./) representing [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Constructor. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Gets string representation of the algorithm name. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | Try to create [HashAlgorithmName](./) from OID-value. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | Returns a [TypeInfo](../../system/typeinfo/) object that represent [TimeSpan](../../system/timespan/) structure. |
## See Also

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)