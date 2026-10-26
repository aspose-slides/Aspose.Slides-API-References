---
title: Guid
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک Globally Unique IDentifier است. این نوع باید روی استاک تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 885
url: /fa/system/guid/
---
## کلاس Guid

نمایانگر یک Globally Unique IDentifier است. این نوع باید روی استک تخصیص داده شود و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Guid
```

## متدها

| متد | توضیح |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | مقایسه ریاضی GUIDهایی که توسط شیء جاری و شیء مشخص شده نمایانده شده‌اند را انجام می‌دهد. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | تعیین می‌کند آیا GUIDهایی که توسط شیء جاری و شیء مشخص شده نمایانده شده‌اند برابر هستند یا نه. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء جاری را برمی‌گرداند. |
|  [Guid](./guid/)() | شیئی را می‌سازد که GUIDی شامل تمامی صفرها را نشان می‌دهد. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | شیئی را می‌سازد که GUIDی را که به صورت آرایه‌ای از مقادیر عدد صحیح بدون علامت ۸ بیتی مشخص شده است، نمایان می‌کند. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | شیئی را می‌سازد که GUIDی را که به صورت یک نمای آرایه‌ای از مقادیر عدد صحیح بدون علامت ۸ بیتی مشخص شده است، نمایان می‌کند. |
|  [Guid](./guid/)(const [String](../string/)\&) | شیئی را می‌سازد که GUIDی را که به صورت رشته‌ای مشخص شده است، نمایان می‌کند. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | یک نمونه از کلاس [Guid](./) را از اجزای مشخص شده GUID می‌سازد. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | یک نمونه از کلاس [Guid](./) را از اجزای مشخص شده GUID می‌سازد. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | یک نمونه از کلاس [Guid](./) را از اعداد صحیح بدون علامت و بایت‌های مشخص شده می‌سازد. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | یک نمونه از کلاس [Guid](./) را از اعداد صحیح بدون علامت و بایت‌های مشخص شده می‌سازد. |
|  [Guid](./guid/)(const [Guid](./)\&) | شیئی را می‌سازد که همان GUID شیء مشخص شده را نمایان می‌کند. |
| static [Guid](./) [NewGuid](./newguid/)() | GUID جدیدی تولید می‌کند و شیء [Guid](./) که آن را نمایان می‌سازد برمی‌گرداند. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | تعیین می‌کند آیا GUIDهای نمایانده شده توسط شیء جاری و شیء مشخص شده برابر نیستند. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | مقدار GUID نمایانده شده توسط شیء [Guid](./) مشخص شده را به شیء جاری اختصاص می‌دهد. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | تعیین می‌کند آیا GUIDهای نمایانده شده توسط شیء جاری و شیء مشخص شده برابر هستند. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | نمایش رشته‌ای مشخص شده یک GUID را به شیء [Guid](./) معادل تبدیل می‌کند. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | GUID نمایانده شده توسط شیء جاری را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)() const | GUID نمایانده شده توسط شیء جاری را به نمایش رشته‌ای آن تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | GUID نمایانده شده توسط شیء جاری را با استفاده از فرمت رشته‌ای مشخص شده به نمایش رشته‌ای آن تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | GUID نمایانده شده توسط شیء جاری را با استفاده از فرمت رشته‌ای مشخص شده و Culture به نمایش رشته‌ای آن تبدیل می‌کند. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | سعی می‌کند رشته مشخص شده را به شیء [Guid](./) تبدیل کند. |
|  [~Guid](./~guid/)() | تخریب‌کننده. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Empty](./empty/) | GUIDی را نشان می‌دهد که مقدار آن صفر است. |

## موارد مرتبط

* Namespace [System](../)
* Library [Aspose.Slides](../../)