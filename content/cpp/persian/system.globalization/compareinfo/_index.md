---
title: CompareInfo
second_title: مرجع API Aspose.Slides برای C++
description: "مقایسهٔ رشته‌ای حساس به فرهنگ را انجام می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 40
url: /fa/system.globalization/compareinfo/
---
## CompareInfo کلاس

مقایسهٔ رشته‌ای حساس به فرهنگ را فراهم می‌کند. شی‌های این کلاس فقط باید با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class CompareInfo : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | رشته‌ها را مقایسه می‌کند. پیاده‌سازی نشده. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | رشته‌ها را مقایسه می‌کند. فقط حالت‌های Ordinal و OrdinalIgnoreCase پشتیبانی می‌شوند. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int) const | بخشی از یک رشته را با بخشی از رشتهٔ دوم مقایسه می‌کند. پیاده‌سازی نشده. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | بخش انتهایی یک رشته را با بخش انتهایی رشتهٔ دوم با استفاده از روش‌های مقایسهٔ رشته‌ای مقایسه می‌کند. پیاده‌سازی نشده. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, const [String](../../system/string/)\&, int) const | بخش انتهایی یک رشته را با بخش انتهایی رشتهٔ دوم مقایسه می‌کند. پیاده‌سازی نشده. |
| virtual int [Compare](./compare/)(const [String](../../system/string/)\&, int, int, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | بخشی از یک رشته را با بخشی از رشتهٔ دوم با استفاده از روش‌های مقایسهٔ رشته‌ای مقایسه می‌کند. پیاده‌سازی نشده. |
| [CompareInfo](./compareinfo/)(const [CompareInfo](./)\&) | اطلاعات RTTI. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| int [get_LCID](./get_lcid/)() const | شناسهٔ LCID فرهنگ مرتبط با مقایسه‌کننده را دریافت می‌کند. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | نام فرهنگ مرتبط با مقایسه‌کننده را دریافت می‌کند. |
| [SortVersionPtr](../sortversionptr/) [get_Version](./get_version/)() const | اطلاعات دربارهٔ نسخهٔ مرتب‌سازی را دریافت می‌کند. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | [CompareInfo](./) مرتبط با فرهنگ مشخص را دریافت می‌کند و از روش‌های مقایسهٔ رشته‌ای در اسمبلی مشخص استفاده می‌کند. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Reflection::Assembly](../../system.reflection/assembly/)\>\&) | [CompareInfo](./) مرتبط با فرهنگ مشخص را دریافت می‌کند و از روش‌های مقایسهٔ رشته‌ای در اسمبلی مشخص استفاده می‌کند. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(int) | [CompareInfo](./) مرتبط با فرهنگ مشخص را دریافت می‌کند. |
| static [CompareInfoPtr](../compareinfoptr/) [GetCompareInfo](./getcompareinfo/)(const [String](../../system/string/)\&) | [CompareInfo](./) مرتبط با فرهنگ مشخص را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را دریافت می‌کند. |
| virtual int [GetHashCode](./gethashcode/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | کد هش رشته را بر اساس گزینه‌های مقایسهٔ مشخص دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override | همتای متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | شی [SortKey](../sortkey/) برای رشتهٔ مشخص با استفاده از گزینه‌های مقایسهٔ مشخص را دریافت می‌کند. |
| virtual [SortKeyPtr](../sortkeyptr/) [GetSortKey](./getsortkey/)(const [String](../../system/string/)\&) const | شی [SortKey](../sortkey/) برای رشتهٔ مشخص را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. همتای فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | به دنبال زیررشته می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | به دنبال زیررشته می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | به دنبال زیررشته می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | به دنبال کاراکتر مشخص می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | به دنبال زیررشته می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t) const | به دنبال کاراکتر مشخص می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | به دنبال زیررشته می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | به دنبال کاراکتر مشخص می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | به دنبال کاراکتر مشخص می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, int) const | به دنبال کاراکتر مشخص می‌گردد. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | به دنبال زیررشته می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual int [IndexOf](./indexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | به دنبال کاراکتر مشخص می‌گردد. فقط حالت Ordinal پشتیبانی می‌شود. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی یک نمونه از نوع توصیف‌شده توسط targetType است. همتای عملگر 'is' در C#. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | بررسی می‌کند که آیا رشتهٔ مشخص با پیشوند مشخص شروع می‌شود با استفاده از گزینه‌های مقایسهٔ مشخص. |
| virtual **bool** [IsPrefix](./isprefix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | بررسی می‌کند که آیا رشتهٔ مشخص با پیشوند مشخص شروع می‌شود. |
| static **bool** [IsSortable](./issortable/)(char16_t) | بررسی می‌کند که آیا کاراکتر مشخص مرتب‌پذیر است. |
| static **bool** [IsSortable](./issortable/)(const [String](../../system/string/)\&) | بررسی می‌کند که آیا رشتهٔ مشخص مرتب‌پذیر است. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | بررسی می‌کند که آیا رشتهٔ مشخص با پسوند مشخص خاتمه می‌یابد با استفاده از گزینه‌های مقایسهٔ مشخص. |
| virtual **bool** [IsSuffix](./issuffix/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | بررسی می‌کند که آیا رشتهٔ مشخص با پسوند مشخص خاتمه می‌یابد. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) const | آخرین رخداد زیررشتهٔ مشخص را جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int, [CompareOptions](../compareoptions/)) const | آخرین رخداد زیررشتهٔ مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int, [CompareOptions](../compareoptions/)) const | آخرین رخداد کاراکتر مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) const | آخرین رخداد رشتهٔ مشخص را جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, [CompareOptions](../compareoptions/)) const | آخرین رخداد رشتهٔ مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, [CompareOptions](../compareoptions/)) const | آخرین رخداد کاراکتر مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int) const | آخرین رخداد رشتهٔ مشخص را جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int) const | آخرین رخداد کاراکتر مشخص را جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [CompareOptions](../compareoptions/)) const | آخرین رخداد رشتهٔ مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, [CompareOptions](../compareoptions/)) const | آخرین رخداد کاراکتر مشخص را با استفاده از گزینه‌های مقایسهٔ مشخص جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t) const | آخرین رخداد کاراکتر مشخص را جستجو می‌کند. |
| virtual int [LastIndexOf](./lastindexof/)(const [String](../../system/string/)\&, char16_t, int, int) const | آخرین رخداد کاراکتر مشخص را جستجو می‌کند. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء سرنگی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | همتای متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [CompareInfo](./)\& [operator=](./operator_equal/)(const [CompareInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص دادن. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | آبجکت نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | همتای متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت C# lock() را آزاد می‌کند. مستقیماً فراخوانی کنید یا از شیء سرنگی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)