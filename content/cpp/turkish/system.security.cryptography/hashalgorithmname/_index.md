---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API Referansı
description: "Hash algoritmasının adını temsil eden dize. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 755
url: /tr/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) bir hash algoritmasının adını temsil eder. Bu tür, yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu türün nesnelerini yönetmek için [System::SmartPtr](../../system/smartptr/) sınıfını asla kullanmayın.

```cpp
class HashAlgorithmName
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | [HashAlgorithmName](./)'yi OID-değerinden oluştur. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | [MD5](../md5/)'yi temsil eden bir [HashAlgorithmName](./) alır. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Algoritma adının dize temsilini alır. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | [SHA1](../sha1/)'yi temsil eden bir [HashAlgorithmName](./) alır. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | [SHA256](../sha256/)'yi temsil eden bir [HashAlgorithmName](./) alır. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | [SHA384](../sha384/)'yi temsil eden bir [HashAlgorithmName](./) alır. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | [SHA512](../sha512/)'yi temsil eden bir [HashAlgorithmName](./) alır. |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | Yapıcı. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | Algoritma adının dize temsilini alır. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | [HashAlgorithmName](./)'yi OID-değerinden oluşturmaya çalış. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | [TimeSpan](../../system/timespan/) yapısını temsil eden bir [TypeInfo](../../system/typeinfo/) nesnesi döndürür. |
## Ayrıca

* Ad alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)