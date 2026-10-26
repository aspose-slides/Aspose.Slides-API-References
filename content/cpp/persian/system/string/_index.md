---
title: String
second_title: مرجع API Aspose.Slides برای C++
description: "کلاس String که در سرتاسر کتابخانه استفاده می‌شود. به عنوان جایگزینی برای C# System.String هنگام ترجمه کد استفاده می‌شود. به دلیل بهینه‌سازی، به عنوان زیرکلاس Object در نظر گرفته نمی‌شود. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا ارجاع عبور داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1275
url: /fa/system/string/
---
## کلاس String


[String](./) class used across the library. Is a substitute for C# [System.String](./) when translating code. For optimization reasons, isn't considered an [Object](../object/) subclass. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class String
```

## متدها

| متد | توضیح |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) یک نوع مقدار در سمت C++ است که به‌صورت ضمنی (بدون ارث‌بری) برخی رابط‌ها را پیاده‌سازی می‌کند. |
| const UChar * [begin](./begin/)() const | نشانگر به ابتدای بافر رشته واقعی را بر می‌گرداند. هرگز چیزی را بازتخصیص نمی‌دهد. تضمین نمی‌کند که بافر به‌صورت null خاتمه یابد. |
| [String](./) [Clone](./clone/)() const | کپی‌ای از رشتهٔ فعلی ایجاد می‌کند. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | مقایسهٔ کمتر-مساوی-بزرگ دو زیررشته را انجام می‌دهد. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقایسهٔ کمتر-مساوی-بزرگ دو زیررشته را انجام می‌دهد. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته را با حالت ترتیبی انجام می‌دهد. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | مقایسهٔ کمتر-مساوی-بزرگ دو رشته را با حالت ترتیبی انجام می‌دهد. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | دو رشته را به سبک «کمتر-مساوی-بیشتر» مقایسه می‌کند. از فرهنگ فعلی استفاده می‌کند. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | رشته‌ها را به هم می‌چسباند. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | رشته‌ها را به هم می‌چسباند. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | رشته‌ها را به هم می‌چسباند. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | رشته‌ها را به هم می‌چسباند. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | بررسی می‌کند که آیا str زیررشته‌ای از رشتهٔ فعلی است. |
| **bool** [Contains](./contains/)(char16_t) const | بررسی می‌کند که آیا رشته حاوی کاراکتر داده‌شده است. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | کپی‌ای از رشته ایجاد می‌کند. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | کاراکترهای رشته را در عناصر موجود آرایه کپی می‌کند. هیچ تغییر اندازه‌ای انجام نمی‌شود. |
| const UChar * [end](./end/)() const | نشانگر به انتهای بافر رشته واقعی را بر می‌گرداند. هرگز چیزی را بازتخصیص نمی‌دهد. تضمین نمی‌کند که بافر به‌صورت null خاتمه یابد. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص‌شده پایان می‌یابد. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص‌شده پایان می‌یابد. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | بررسی می‌کند که آیا رشته با زیررشتهٔ مشخص‌شده پایان می‌یابد. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) مقایسهٔ برابری. چندین حالت ارائه‌شده توسط شمارش‌گر StringComparison پشتیبانی می‌شود. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) مقایسهٔ برابری. از حالت مقایسهٔ [System::StringComparison::Ordinal](../stringcomparison/) استفاده می‌کند. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | مقایسهٔ مساوی دو رشته را با حالت مقایسهٔ Ordial انجام می‌دهد. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | مقایسهٔ مساوی دو رشته را انجام می‌دهد. |
| int [FastToAscii](./fasttoascii/)(char, int) const | سعی می‌کند یک [String](./) را به رشتهٔ ASCII تبدیل کند. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | رشته را به سبک C# قالب‌بندی می‌کند. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | رشته را به سبک C# قالب‌بندی می‌کند. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | رشته را به سبک C# قالب‌بندی می‌کند. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | رشته را به سبک C# قالب‌بندی می‌کند. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | رشته را به سبک C# قالب‌بندی می‌کند. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | [String](./) را از رشتهٔ ASCII ایجاد می‌کند. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | [String](./) را از رشتهٔ ASCII ایجاد می‌کند. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | [String](./) را از رشتهٔ ASCII ایجاد می‌کند. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | [String](./) را از رشتهٔ utf16 ایجاد می‌کند. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | [String](./) را از رشتهٔ utf32 ایجاد می‌کند. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | [String](./) را از رشتهٔ utf8 ایجاد می‌کند. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | [String](./) را از رشتهٔ utf8 ایجاد می‌کند. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | [String](./) را از رشتهٔ utf8 ایجاد می‌کند. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | [String](./) را از رشتهٔ utf8 ایجاد می‌کند. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | [String](./) را از widestring ایجاد می‌کند. |
| int [get_Length](./get_length/)() const | طول رشته را بر می‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | هش رشتهٔ موجود را محاسبه می‌کند. در ICU پیاده‌سازی شده است و با هش‌های C# مطابقت ندارد. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | جستجوی پیش‌رو زیررشته. |
| int [IndexOf](./indexof/)(char_t, int) const | جستجوی پیش‌رو کاراکتری. |
| int [IndexOf](./indexof/)(char_t, int, int) const | جستجوی پیش‌رو کاراکتر در زیررشته. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | جستجوی پیش‌رو زیررشته. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | جستجوی پیش‌رو زیررشته. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | جستجوی پیش‌رو زیررشته. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | جستجوی پیش‌رو زیررشته. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | جستجوی پیش‌رو کاراکتری. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | به‌طور متوالی به دنبال تمام کاراکترهای str در این رشته می‌گردد. اگر کاراکتر اول پیدا شود، موقعیت آن بازگردانده می‌شود، در غیر این صورت به دنبال دومین کاراکتر و ادامه می‌یابد. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | به‌دنبال هر یک از کاراکترهای عبورده‌شده در سراسر رشته می‌گردد. اولین کاراکتر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس دومین کاراکتر و ادامه. شاخص اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را بر می‌گرداند. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | در زیررشته به‌دنبال هر یک از کاراکترهای عبورده‌شده می‌گردد. اولین کاراکتر زیررشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس دومین کاراکتر و ادامه. شاخص اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را بر می‌گرداند. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | در زیررشته به‌دنبال هر یک از کاراکترهای عبورده‌شده می‌گردد. اولین کاراکتر زیررشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس دومین کاراکتر و ادامه. شاخص اولین کاراکتری که با هر یک از کاراکترهای هدف مطابقت دارد را بر می‌گرداند. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | زیررشته را در موقعیت مشخص وارد می‌کند. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء رشته از نوعی است که توسط [TypeInfo](../typeinfo/) عبورده شده مشخص شده است. |
| **bool** [IsAsciiString](./isasciistring/)() const | نشان می‌دهد آیا یک [String](./) فقط شامل نمادهای ASCII است. |
| **bool** [IsEmpty](./isempty/)() const | بررسی می‌کند که آیا رشته هم غیر null است و هم خالی. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | بررسی می‌کند که آیا رشتهٔ یونیکد با استفاده از فرم نرمال‌سازی مشخص‌شده نرمال‌سازی شده است. |
| **bool** [IsNull](./isnull/)() const | بررسی می‌کند که آیا رشته به‌عنوان null در نظر گرفته می‌شود. [String](./) زمانی null است که از سازندهٔ [String()](./string/) ساخته شده باشد، منتقل، کپی یا از رشتهٔ null اختصاص داده شده باشد یا متد [reset()](./reset/) فراخوانی شده باشد. |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | بررسی می‌کند که آیا رشته خالی است یا به‌عنوان null در نظر گرفته می‌شود. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | بررسی می‌کند که آیا رشتهٔ عبورده‌شده null یا خالی است. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | نشان می‌دهد آیا رشتهٔ مشخص شده null، خالی یا تنها شامل کاراکترهای فضای سفید است. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | آرایه را با استفاده از رشته به‌عنوان جداساز ترکیب می‌کند. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | آرایه را با استفاده از رشته به‌عنوان جداساز ترکیب می‌کند. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | آرایه را با استفاده از رشته به‌عنوان جداساز ترکیب می‌کند. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | آرایه را با استفاده از رشته به‌عنوان جداساز ترکیب می‌کند. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | جستجوی پس‌رو زیررشته. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | جستجوی پس‌رو زیررشته. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | جستجوی پس‌رو زیررشته. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | جستجوی پس‌رو زیررشته. |
| int [LastIndexOf](./lastindexof/)(char_t) const | جستجوی پس‌رو کاراکتر. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | جستجوی پس‌رو کاراکتر. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | جستجوی پس‌رو کاراکتر. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | به‌صورت پس‌رو به دنبال هر یک از کاراکترهای عبورده‌شده در کل رشته می‌گردد. کاراکتر آخر رشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس قبلی و ادامه. شاخص اولین مطابقت یافت‌شده را بر می‌گرداند. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | به‌صورت پس‌رو به دنبال هر یک از کاراکترهای عبورده‌شده در زیررشته می‌گردد. کاراکتر آخر زیررشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس قبلی و ادامه. شاخص اولین مطابقت یافت‌شده را بر می‌گرداند. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | به‌صورت پس‌رو به دنبال هر یک از کاراکترهای عبورده‌شده در زیررشته می‌گردد. کاراکتر آخر زیررشته را با تمام کاراکترهای anyOf مقایسه می‌کند، سپس قبلی و ادامه. شاخص اولین مطابقت یافت‌شده را بر می‌گرداند. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | رشتهٔ یونیکد را با استفاده از فرم نرمال‌سازی مشخص‌شده نرمال‌سازی می‌کند. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | رشته را به بازهٔ فقط-خواندنی تبدیل می‌کند. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | عملگر مقایسهٔ نامساوی. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | بررسی می‌کند که آیا رشته null نیست. همان منطق فراخوانی [IsNull()](./isnull/) را اعمال می‌کند. |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | عملگر الحاق [String](./). |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) الحاق با رشتهٔ ثابت یا اشاره‌گر رشتهٔ کاراکتری. |
| [String](./) [operator+](./operator_plus/)(char_t) const | کاراکتر را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(int) const | نمایش رشته‌ای مقدار عدد صحیح را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | نمایش رشته‌ای مقدار عدد صحیح بدون علامت را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(**double**) const | نمایش رشته‌ای مقدار عدد اعشاری را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | نمایش رشته‌ای مقدار عدد صحیح 64 بیتی را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | نمایش رشته‌ای شیء نوع مرجع را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | نمایش رشته‌ای شیء نوع مرجع را به انتهای رشته اضافه می‌کند. |
| [String](./) [operator+](./operator_plus/)(T) const | نمایش رشته‌ای مقدار منطقی را به انتهای رشته اضافه می‌کند. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | عملگر انتساب الحاق. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | عملگر انتساب الحاق. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | عملگر انتساب الحاق. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | عملگر انتساب الحاق. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | عملگر انتساب الحاقی. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | عملگر انتساب الحاقی. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | رشته‌ها را به ترتیب مقایسه می‌کند. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | عملگر انتساب. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | عملگر انتساب جابجایی. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | عملگر مقایسه مساوی. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | بررسی می‌کند آیا رشته null است. همان منطق فراخوانی [IsNull()](./isnull/) را اعمال می‌کند. |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | رشته‌ها را به ترتیب مقایسه می‌کند. |
| char_t [operator[]](./operator[]/)(int) const | کاراکتر را در موقعیت مشخص دریافت می‌کند. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | پدینگ را به سمت چپ رشته اصلی اضافه می‌کند. |
| [String](./) [PadRight](./padright/)(int, char_t) const | پدینگ را به سمت راست رشته اصلی اضافه می‌کند. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | تکرارگر معکوس را به آخرین کاراکتر (در صورت وجود) بافر رشته واقعی باز می‌گرداند. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | همه چیز به جز زیررشته را از رشته جاری استخراج می‌کند. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | تکرارگر معکوس را به قبل از اولین کاراکتر (در صورت وجود) بافر رشته واقعی باز می‌گرداند. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | تمام رخدادهای کاراکتر را در رشته جایگزین می‌کند. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | تمام رخدادهای lookup را در این رشته جایگزین می‌کند. |
| [String](./)\& [reset](./reset/)() | رشته را به null تنظیم می‌کند. مشابه عبارت 'string_variable_name = null' در C# است. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | کاراکتر را در موقعیت مشخص تنظیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس کاراکتر تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس کاراکتر تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس یکی از دو کاراکتر تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس یکی از کاراکترهای مشخص شده تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس یکی از کاراکترهای مشخص شده تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس زیررشته تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس زیررشته تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس زیررشته تقسیم می‌کند. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | رشته را بر اساس زیررشته تقسیم می‌کند. در حال حاضر، فقط آرایه جداسازهای صفر یا یک عنصر را پشتیبانی می‌کند. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | بررسی می‌کند آیا رشته با زیررشته مشخص شروع می‌شود. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | بررسی می‌کند آیا رشته با زیررشته مشخص شروع می‌شود. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | بررسی می‌کند آیا رشته با زیررشته مشخص شروع می‌شود. |
|  [String](./string/)() | سازنده‌ی پیش‌فرض. شیء رشته‌ای را ایجاد می‌کند که به عنوان null در نظر گرفته می‌شود. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | رشته را بر اساس literal رشته‌ای می‌سازد. literal را به عنوان رشته‌ای با پایان null در نظر می‌گیرد و طول رشته هدف را بر اساس اندازه literal محاسبه می‌کند. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | رشته را بر اساس اشاره‌گر رشته کاراکتری می‌سازد. رشته‌ی اشاره‌شده را به عنوان رشته‌ی پایان‌دار با null در نظر می‌گیرد و طول رشته هدف را بر اساس کاراکتر null محاسبه می‌کند. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | رشته را بر اساس literal رشته‌ای می‌سازد. literal را به عنوان رشته‌ای با پایان null در UTF-8 در نظر می‌گیرد و طول رشته هدف را بر اساس اندازه literal محاسبه می‌کند. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | رشته را بر اساس اشاره‌گر رشته کاراکتری می‌سازد. رشته‌ی اشاره‌شده را به عنوان رشته‌ی پایان‌دار با null در UTF-8 در نظر می‌گیرد و طول رشته هدف را بر اساس کاراکتر null محاسبه می‌کند. |
|  [String](./string/)(const char16_t *, int) | رشته را از اشاره‌گر رشته کاراکتری و طول صریح می‌سازد. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | یک نمونه جدید از کلاس [System.String](./) را با کاراکترهای یونیکد مشخص در span فقط-خواندنی داده‌شده مقداردهی می‌کند. |
|  [String](./string/)(const char *, int) | رشته را از اشاره‌گر رشته کاراکتری و طول صریح می‌سازد. |
|  [String](./string/)(const char16_t *, int, int) | رشته را از اشاره‌گر رشته کاراکتری، از موقعیت شروع و با طول مشخص می‌سازد. |
| explicit  [String](./string/)(const char16_t, int) | سازنده‌ی پرکننده. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | سازنده‌ی nullptr. به عنوان قالب تعریف شده تا اولویت‌ها با سایر سازنده‌های قالب حل شود. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | رشته را بر اساس literal رشتهٔ wide می‌سازد. literal را به عنوان رشته‌ای با پایان null در نظر می‌گیرد و طول رشته هدف را بر اساس اندازه literal محاسبه می‌کند. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | رشته را بر اساس اشاره‌گر رشتهٔ wide می‌سازد. رشته‌ی اشاره‌شده را به عنوان رشته‌ای با پایان null در نظر می‌گیرد و طول رشته هدف را بر اساس کاراکتر null محاسبه می‌کند. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند. |
| explicit  [String](./string/)(const **wchar_t** *, int) | رشته را از اشاره‌گر رشتهٔ wide و طول صریح می‌سازد. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند. |
| explicit  [String](./string/)(const **wchar_t**, int) | سازنده‌ی پرکننده. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند. |
|  [String](./string/)(const [String](./)\&) | سازنده‌ی کپی. |
|  [String](./string/)([String](./)\&&) | سازنده‌ی جابجایی. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | کلیه آرایه کاراکتر را به رشته تبدیل می‌کند. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | زیرمحدوده‌ای از آرایه کاراکتر را به رشته تبدیل می‌کند. اگر پارامترها خارج از محدوده آرایه باشند، رشته‌ای خالی ساخته می‌شود. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | UnicodeString را در [String](./) می‌پیچد. |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | سازنده‌ی جابجایی. |
| explicit  [String](./string/)(const std::wstring\&) | [String](./) را از widestring می‌سازد. |
| explicit  [String](./string/)(const std::u16string\&) | [String](./) را از رشتهٔ utf16 می‌سازد. |
| explicit  [String](./string/)(const std::string\&) | [String](./) را از رشتهٔ std::string به قالب UTF-8 می‌سازد. |
| explicit  [String](./string/)(const std::u32string\&) | [String](./) را از رشتهٔ std::u32string می‌سازد. |
| [String](./) [Substring](./substring/)(**int32_t**) const | زیررشته را استخراج می‌کند. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | زیررشته را استخراج می‌کند. |
| std::string [ToAsciiString](./toasciistring/)() const | رشته را به std::string تبدیل می‌کند. از رمزگذاری ASCII استفاده می‌کند. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | رشته یا زیررشته را به آرایه‌ای از بایت‌ها تبدیل می‌کند. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | رشته یا زیررشته را به آرایه‌ای از کاراکترها تبدیل می‌کند. |
| [String](./) [ToLower](./tolower/)() const | تمام کاراکترهای رشته را به حروف کوچک تبدیل می‌کند. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | تمام کاراکترهای رشته را به حروف کوچک تبدیل می‌کند با فرهنگ خاص. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | تمام کاراکترهای رشته را به حروف کوچک تبدیل می‌کند با فرهنگ بی‌تغییر. |
| [String](./) [ToString](./tostring/)() const | Wrapper برای کار با کلاس [String](./) در زمینه‌ای که [ToString()](./tostring/) روی اشیای نوع مقدار فراخوانی می‌شود. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Wrapper برای کار با کلاس [String](./) در زمینه‌ای که [ToString()](./tostring/) روی اشیای نوع مقدار فراخوانی می‌شود. |
| std::u16string [ToU16Str](./tou16str/)() const | رشته را به std::u16string تبدیل می‌کند. |
| std::u32string [ToU32Str](./tou32str/)() const | رشته را به std::u32string تبدیل می‌کند. |
| [String](./) [ToUpper](./toupper/)() const | تمام کاراکترهای رشته را به حروف بزرگ تبدیل می‌کند. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | تمام کاراکترهای رشته را به حروف بزرگ تبدیل می‌کند با فرهنگ خاص. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | تمام کاراکترهای رشته را به حروف بزرگ تبدیل می‌کند با فرهنگ بی‌تغییر. |
| std::string [ToUtf8String](./toutf8string/)() const | رشته را به std::string تبدیل می‌کند. از رمزگذاری UTF-8 استفاده می‌کند. |
| std::wstring [ToWCS](./towcs/)() const | رشته را به std::wstring تبدیل می‌کند. |
| [String](./) [Trim](./trim/)() const | تمام کاراکترهای فضای سفید را از ابتداء و انتهای رشته حذف می‌کند. |
| [String](./) [Trim](./trim/)(char_t) const | تمام رخدادهای کاراکتر داده‌شده را از ابتداء و انتهای رشته حذف می‌کند. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | تمام رخدادهای کاراکترهای داده‌شده را از ابتداء و انتهای رشته حذف می‌کند. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | تمام رخدادهای کاراکترهای داده‌شده را از ابتداء و انتهای رشته حذف می‌کند. |
| [String](./) [TrimEnd](./trimend/)() const | تمام کاراکترهای فضای سفید را از انتهای رشته حذف می‌کند. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | تمام رخدادهای کاراکتر داده‌شده را از انتهای رشته حذف می‌کند. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | تمام رخدادهای کاراکترهای داده‌شده را از انتهای رشته حذف می‌کند. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | تمام رخدادهای کاراکترهای داده‌شده را از انتهای رشته حذف می‌کند. |
| [String](./) [TrimStart](./trimstart/)() const | تمام کاراکترهای فضای سفید را از ابتداء رشته حذف می‌کند. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | تمام رخدادهای کاراکتر داده‌شده را از ابتداء رشته حذف می‌کند. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | تمام رخدادهای کاراکترهای داده‌شده را از ابتداء رشته حذف می‌کند. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | تمام رخدادهای کاراکترهای داده‌شده را از ابتداء رشته حذف می‌کند. |
| const UChar * [u_str](./u_str/)() const | بافر null-terminated سبک ICU را باز می‌گرداند. ممکن است رشته را مجدداً تخصیص دهد. |
|  [~String](./~string/)() | مخرب. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Empty](./empty/) | رشته خالی. |
| static [Null](./null/) | رشته null. |

## تایپ‌دِف‌ها

| تایپ‌دِف | توضیح |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | نوع تکرارگر معکوس. |

## یادداشت‌ها

```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // یک رشته را از آرایهٔ حروف ایجاد کرده و چاپ می‌کند.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // یک رشته را از آرایهٔ بایت‌ها ایجاد کرده و چاپ می‌کند.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // رشته زیر را برش (Trim) داده و چاپ می‌کند.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // تعداد کلمات موجود در رشته را چاپ می‌کند.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
hello
world
"این رشته حاوی فاصله‌ها در ابتدا و انتهای آن است."
تعداد کلمات: 11
*/
```

## موارد مرتبط

* فضای‌نامی [System](../)
* کتابخانه [Aspose.Slides](../../)