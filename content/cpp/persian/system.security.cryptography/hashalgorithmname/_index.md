---
title: HashAlgorithmName
second_title: مرجع API Aspose.Slides برای C++
description: "رشته‌ای که نام یک الگوریتم هش را نشان می‌دهد. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 755
url: /fa/system.security.cryptography/hashalgorithmname/
---
## ساختار HashAlgorithmName


[String](../../system/string/) نمایانگر نام یک الگوریتم هش است. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع منتقل شود. هرگز از کلاس [System::SmartPtr](../../system/smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class HashAlgorithmName
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | ایجاد [HashAlgorithmName](./) از مقدار OID. |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | یک [HashAlgorithmName](./) دریافت می‌کند که [MD5](../md5/) را نمایان می‌سازد. |
| [String](../../system/string/) [get_Name](./get_name/)() const | نمایش رشته‌ای نام الگوریتم را دریافت می‌کند. |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | یک [HashAlgorithmName](./) دریافت می‌کند که [SHA1](../sha1/) را نمایان می‌سازد. |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | یک [HashAlgorithmName](./) دریافت می‌کند که [SHA256](../sha256/) را نمایان می‌سازد. |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | یک [HashAlgorithmName](./) دریافت می‌کند که [SHA384](../sha384/) را نمایان می‌سازد. |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | یک [HashAlgorithmName](./) دریافت می‌کند که [SHA512](../sha512/) را نمایان می‌سازد. |
| int [GetHashCode](./gethashcode/)() const |  |
|  [HashAlgorithmName](./hashalgorithmname/)() |  |
|  [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | سازنده. |
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
| [String](../../system/string/) [ToString](./tostring/)() const | نمایش رشته‌ای نام الگوریتم را دریافت می‌کند. |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | سعی کنید [HashAlgorithmName](./) را از مقدار OID ایجاد کنید. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | یک شیء [TypeInfo](../../system/typeinfo/) را برمی‌گرداند که ساختار [TimeSpan](../../system/timespan/) را نشان می‌دهد. |
## ارجاع

* فضای نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)