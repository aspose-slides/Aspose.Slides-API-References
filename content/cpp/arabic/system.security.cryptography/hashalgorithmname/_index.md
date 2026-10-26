---
title: HashAlgorithmName
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "سلسلة تمثل اسم خوارزمية التجزئة. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم الفئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 755
url: /ar/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName struct

[String](../../system/string/) تمثل اسم خوارزمية تجزئة. ينبغي تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../../system/smartptr/) لإدارة كائنات هذا النوع.

```cpp
class HashAlgorithmName
```

## Methods

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | إنشاء [HashAlgorithmName](./) من قيمة OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | يحصل على [HashAlgorithmName](./) يمثل [MD5](../md5/). |
| [String](../../system/string/) [get_Name](./get_name/)() const | يحصل على تمثيل نصي لاسم الخوارزمية. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | يحصل على [HashAlgorithmName](./) يمثل [SHA1](../sha1/). |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | يحصل على [HashAlgorithmName](./) يمثل [SHA256](../sha256/). |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | يحصل على [HashAlgorithmName](./) يمثل [SHA384](../sha384/). |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | يحصل على [HashAlgorithmName](./) يمثل [SHA512](../sha512/). |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | منشئ. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | يحصل على تمثيل نصي لاسم الخوارزمية. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | حاول إنشاء [HashAlgorithmName](./) من قيمة OID. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | يرجع كائن [TypeInfo](../../system/typeinfo/) الذي يمثل بنية [TimeSpan](../../system/timespan/). |

## انظر أيضًا

* نطاق الاسم [System::Security::Cryptography](../)
* مكتبة [Aspose.Slides](../../)