---
title: Regex
second_title: Aspose.Slides برای مرجع API C++
description: "عبارت منظم که نحو شبیه C# را دنبال می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 92
url: /fa/system.text.regularexpressions/regex/
---
## Regex کلاس

عبارت منظم که نحو شبیه C# را دنبال می‌کند. اشیاء این کلاس باید فقط با استفاده از توابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Regex : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | کاراکترهای خاص را برای استفاده از رشته به‌عنوان بخشی از الگو فرار می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [TimeSpan](../../system/timespan/) [get_MatchTimeout](./get_matchtimeout/)() | زمان‌ساز مطابقت را دریافت می‌کند. |
| [RegexOptions](../regexoptions/) [get_Options](./get_options/)() | گزینه‌های regex را دریافت می‌کند. |
| **bool** [get_RightToLeft](./get_righttoleft/)() | بررسی می‌کند که آیا مطابقت در حالت راست به چپ انجام می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, int) | regex را با رشته مطابقت می‌دهد. |
| static **bool** [IsMatch](./ismatch/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int) | بررسی می‌کند که آیا رشته با الگو مطابقت دارد. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) sentinel استفاده کنید. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&) | regex را با رشته مطابقت می‌دهد. |
| [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, int, int) | regex را با رشته مطابقت می‌دهد. |
| static [MatchPtr](../matchptr/) [Match](./match/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | رشته و الگو را مطابقت می‌دهد. |
| [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, int) | تمام تطابق‌های regex در رشتهٔ داده‌شده را با تطبیق مکرر دریافت می‌کند. |
| static [MatchCollectionPtr](../matchcollectionptr/) [Matches](./matches/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/), int, int) | تمام تطابق‌ها بین رشته و الگو را دریافت می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
|  [Regex](./regex/)() | یک regexp خالی می‌سازد. |
|  [Regex](./regex/)(const [String](../../system/string/)\&) | سازنده. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | سازنده. |
|  [Regex](./regex/)(const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | سازنده. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تمام تطابق‌های regex در رشته را با رشتهٔ جایگزین جایگزین می‌کند. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *) | تمام تطابق‌های regex در رشته را با رشتهٔ جایگزین جایگزین می‌کند. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const char_t *, const char_t *) | تمام تطابق‌های regex در رشته را با رشتهٔ جایگزین جایگزین می‌کند. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const char_t *) | تمام تطابق‌های regex در رشته را با رشتهٔ جایگزین جایگزین می‌کند. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | تمام تطابق‌ها در رشته را با رشته‌های جایگزین تولید شده توسط delegate جایگزین می‌کند. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int) | تمام تطابق‌ها در رشته را با رشته‌های جایگزین تولید شده توسط delegate جایگزین می‌کند. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, int, int) | تمام تطابق‌ها در رشته را با رشته‌های جایگزین تولید شده توسط delegate جایگزین می‌کند. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&, [RegexOptions](../regexoptions/)) | تمام تطابق‌ها در رشته را با رشته‌های جایگزین تولید شده توسط delegate جایگزین می‌کند (تابع استاتیک). |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/)) | تمام تطابق‌های regex در رشته را با رشتهٔ جایگزین جایگزین می‌کند. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) | زیررشته‌ها را در رشته جایگزین می‌کند. پیاده‌سازی نشده. |
| [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | زیررشته‌ها را در رشته جایگزین می‌کند. پیاده‌سازی نشده. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | تطابق‌های regex را جایگزین می‌کند. |
| static [String](../../system/string/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [MatchEvaluator](../matchevaluator/)\&) | تطابق‌های regex را جایگزین می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&) | رشته را بر اساس تطابق‌های regex تقسیم می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int) | رشته را بر اساس تطابق‌های regex تقسیم می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, int, int) | رشتهٔ ورودی را حداکثر تعداد مشخص‌شده بار به آرایه‌ای از زیررشته‌ها تقسیم می‌کند، در موقعیت‌هایی که توسط عبارت منظم مشخص‌شده در سازنده [Regex](./) تعریف شده‌اند. جستجوی الگوی عبارت منظم از موقعیت کاراکتر مشخص‌شده‌ای در رشته ورودی شروع می‌شود. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | رشته را بر اساس regexp تقسیم می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [Split](./split/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [RegexOptions](../regexoptions/), [TimeSpan](../../system/timespan/)) | رشته را بر اساس regexp تقسیم می‌کند. |
| [String](../../system/string/) [ToString](./tostring/)() const override | regex را به رشته تبدیل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| static [String](../../system/string/) [Unescape](./unescape/)(const [String](../../system/string/)\&) | کاراکترهای خاص فرار شده در رشتهٔ استفاده‌شده به‌عنوان بخشی از الگو را باز می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیانیه lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) sentinel استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیلاً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## فیلدها

| Field | Description |
| --- | --- |
| static [InfiniteMatchTimeout](./infinitematchtimeout/) | مقدار ویژه زمان‌ساز برای غیرفعال کردن قطع مطابقت توسط زمان‌ساز. |

## همچنین ببینید

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Slides](../../)