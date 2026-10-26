---
title: TextInfo
second_title: مرجع API Aspose.Slides برای C++
description: "خواص متن مخصوص به محل را تعریف می‌کند. عملیات تنظیم فقط برای اشیائی که فقط-خواندنی نیستند فعال است. اشیاء این کلاس باید فقط با تابع System::MakeObject() اختصاص داده شوند. هرگز نمونهٔ این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های تأیید می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بسته‌بندی کنید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 365
url: /fa/system.globalization/textinfo/
---
## کلاس TextInfo

خصائص متن خاص بɭمحلی را تعریف می‌کند. عملیات تنظیم فقط برای اشیائی که فقط-خواندنی نیستند فعال است. اشیاء این کلاس باید فقط با تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های تأیید می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بسته‌بندی کنید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class TextInfo : public System::ICloneable
```

## متدها

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | یک نسخه‌برداری از شیء جاری ایجاد می‌کند و یک اشاره‌گر به‌اشتراک‌گذاری شده به آن بر می‌گرداند. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفاهیم C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual int [get_ANSICodePage](./get_ansicodepage/)() const | کدصفحه ANSI را دریافت می‌کند. |
| [String](../../system/string/) [get_CultureName](./get_culturename/)() const | نام فرهنگ را دریافت می‌کند. |
| virtual int [get_EBCDICCodePage](./get_ebcdiccodepage/)() const | کدصفحه EBCDIC را دریافت می‌کند. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | بررسی می‌کند که آیا قالب فقط برای خواندن است یا خیر. |
| **bool** [get_IsRightToLeft](./get_isrighttoleft/)() const | بررسی می‌کند که آیا متن از چپ به راست نوشته شده است یا خیر. |
| int [get_LCID](./get_lcid/)() const | شناسهٔ مکان (Locale) را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_ListSeparator](./get_listseparator/)() const | جداساز فهرست را دریافت می‌کند. |
| virtual int [get_MacCodePage](./get_maccodepage/)() const | کدصفحه Macintosh را دریافت می‌کند. |
| virtual int [get_OEMCodePage](./get_oemcodepage/)() const | کدصفحه OEM را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف شده توسط targetType است یا نه. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C#. مستقیماً صدا بزنید یا از شیء امنیتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [TextInfo](./)\& [operator=](./operator_equal/)(const [TextInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static [TextInfoPtr](../textinfoptr/) [ReadOnly](./readonly/)(const [TextInfoPtr](../textinfoptr/)\&) | نسخهٔ فقط-خواندنی فرهنگ را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr بر اساس ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده ارجاع به‌اشتراک‌گذاری را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_ListSeparator](./set_listseparator/)([String](../../system/string/)) | جداساز فهرست را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای به‌اشتراک‌گذاری) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع به‌اشتراک‌گذاری را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع به‌اشتراک‌گذاری را افزایش می‌دهد. نباید به‌طور مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع به‌اشتراک‌گذاری را کاهش داده و بازمی‌گرداند. نباید به‌طور مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [TextInfo](./textinfo/)(const [TextInfo](./)\&) | اطلاعات RTTI. |
| virtual char_t [ToLower](./tolower/)(char_t) const | کاراکتر را به حروف کوچک تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToLower](./tolower/)([String](../../system/string/)) const | رشته را به حروف کوچک تبدیل می‌کند. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| [String](../../system/string/) [ToTitleCase](./totitlecase/)([String](../../system/string/)) const | رشته را به حالت عنوان (Title case) تبدیل می‌کند (به‌جز مخفف‌هایی که از پیش به حروف بزرگ هستند). |
| virtual char_t [ToUpper](./toupper/)(char_t) const | کاراکتر را به حروف بزرگ تبدیل می‌کند. |
| virtual [String](../../system/string/) [ToUpper](./toupper/)([String](../../system/string/)) const | رشته را به حروف بزرگ تبدیل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای آزادسازی قفل در عبارت lock() در C#. مستقیماً صدا بزنید یا از شیء امنیتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم صدا زده شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [ICloneable](../../system/icloneable/)
* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)