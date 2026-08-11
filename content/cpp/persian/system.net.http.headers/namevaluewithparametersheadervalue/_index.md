---
title: NameValueWithParametersHeaderValue
second_title: Aspose.Slides برای مرجع API C++
description: "نمایش می‌دهد یک جفت کلید/مقدار با پارامترها برای استفاده در هدرها. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 183
url: /fa/system.net.http.headers/namevaluewithparametersheadervalue/
---
## کلاس NameValueWithParametersHeaderValue

نمایش می‌دهد یک جفت کلید/مقدار با پارامترها برای استفاده در هدرها. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا (assertion) می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class NameValueWithParametersHeaderValue : public System::Net::Http::Headers::NameValueHeaderValue
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | اشیاء را با استفاده از قوانین C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قوانین C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند مطابق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند مطابق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\> [Find](../namevalueheadervalue/find/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, [String](../../system/string/)) | نمونهٔ کلاس NameValueHeaderValue را در یک مجموعه بر اساس نام مشخص شده پیدا می‌کند. |
| [String](../../system/string/) [get_Name](../namevalueheadervalue/get_name/)() | نام نمونهٔ فعلی را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | پارامترها را از نمونهٔ فعلی برمی‌گرداند. |
| [String](../../system/string/) [get_Value](../namevalueheadervalue/get_value/)() | مقدار نمونهٔ فعلی را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| static **int32_t** [GetHashCode](../namevalueheadervalue/gethashcode/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | کد هش همهٔ آیتم‌های مجموعه را برمی‌گرداند. |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | رشتهٔ داده شده را از اندیس مشخص به نمونه‌ای از کلاس [NameValueHeaderValue](../namevalueheadervalue/) تبدیل می‌کند. |
| static **int32_t** [GetNameValueLength](../namevalueheadervalue/getnamevaluelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | رشتهٔ داده شده را از اندیس مشخص به نمونه‌ای از کلاس [NameValueHeaderValue](../namevalueheadervalue/) تبدیل می‌کند. |
| static **int32_t** [GetNameValueListLength](../namevalueheadervalue/getnamevaluelistlength/)([String](../../system/string/), **int32_t**, char16_t, [System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>) | رشتهٔ داده شده را از اندیس مشخص به مجموعه‌ای از نمونه‌های کلاس NameValueHeaderValue تبدیل می‌کند و طول زیررشتهٔ تجزیه‌شده را برمی‌گرداند. |
| static **int32_t** [GetNameValueWithParametersLength](./getnamevaluewithparameterslength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | رشتهٔ داده شده را از اندیس مشخص به نمونه‌ای از کلاس [NameValueWithParametersHeaderValue](./) تبدیل می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| static **int32_t** [GetValueLength](../namevalueheadervalue/getvaluelength/)([String](../../system/string/), **int32_t**) | طول مقداری را از اندیس مشخص برمی‌گرداند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی (کپی) انواع سفارشی را فراهم می‌کند. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)() | یک نمونهٔ جدید می‌سازد. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
|  [NameValueHeaderValue](../namevalueheadervalue/namevalueheadervalue/)([String](../../system/string/), [String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)([String](../../system/string/), [String](../../system/string/)) | یک نمونهٔ جدید می‌سازد. |
|  [NameValueWithParametersHeaderValue](./namevaluewithparametersheadervalue/)() | یک نمونهٔ جدید می‌سازد. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور اختصاص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | رشتهٔ داده شده را به نمونه‌ای از کلاس [NameValueWithParametersHeaderValue](./) تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| void [set_Value](../namevalueheadervalue/set_value/)([String](../../system/string/)) | مقدار نمونهٔ فعلی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](./tostring/)() const override | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static void [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>) | نمایش رشته‌ای از مجموعهٔ نمونه‌های کلاس NameValueHeaderValue را برمی‌گرداند. |
| static [String](../../system/string/) [ToString](../namevalueheadervalue/tostring/)([System::SharedPtr](../../system/sharedptr/)\<[ObjectCollection](../objectcollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\>, char16_t, **bool**) | نمایش رشته‌ای از مجموعهٔ نمونه‌های کلاس NameValueHeaderValue را برمی‌گرداند. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](./)\>\&) | سعی می‌کند رشتهٔ داده شده را به نمونه‌ای از کلاس [NameValueWithParametersHeaderValue](./) تبدیل کند. |
| static **bool** [TryParse](../namevalueheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\&) | سعی می‌کند رشتهٔ داده شده را به نمونه‌ای از کلاس [NameValueHeaderValue](../namevalueheadervalue/) تبدیل کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری توسط بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [NameValueHeaderValue](../namevalueheadervalue/)
* فضای نام [System::Net::Http::Headers](../)
* کتابخانه [Aspose.Slides](../../)