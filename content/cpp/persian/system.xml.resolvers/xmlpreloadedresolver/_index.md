---
title: XmlPreloadedResolver
second_title: Aspose.Slides برای مرجع API C++
description: کلاسی را نشان می‌دهد که برای پیش بارگذاری کش با DTDها یا جریان‌های XML استفاده می‌شود.
type: docs
weight: 1
url: /fa/system.xml.resolvers/xmlpreloadedresolver/
---
## XmlPreloadedResolver کلاس

نمایش‌دهندهٔ کلاسی است که برای پیش‌بارگذاری کش با DTDها یا جریان‌های XML استفاده می‌شود.

```cpp
class XmlPreloadedResolver : public System::Xml::XmlResolver
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | یک آرایه بایتی را به ذخیرهٔ [XmlPreloadedResolver](./) اضافه می‌کند و آن را به یک URI نگاشت می‌کند. اگر این ذخیره قبلاً نگاشت برای همان URI را داشته باشد، نگاشت موجود بازنویسی می‌شود. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | یک آرایه بایتی را به ذخیرهٔ [XmlPreloadedResolver](./) اضافه می‌کند و آن را به یک URI نگاشت می‌کند. اگر این ذخیره قبلاً نگاشت برای همان URI را داشته باشد، نگاشت موجود بازنویسی می‌شود. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | یک Stream را به ذخیرهٔ [XmlPreloadedResolver](./) اضافه می‌کند و آن را به یک URI نگاشت می‌کند. اگر این ذخیره قبلاً نگاشت برای همان URI را داشته باشد، نگاشت موجود بازنویسی می‌شود. |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&, const [String](../../system/string/)\&) | یک رشته حاوی داده‌های پیش‌بارگذاری‌شده را به ذخیرهٔ [XmlPreloadedResolver](./) اضافه می‌کند و آن را به یک URI نگاشت می‌کند. اگر این ذخیره قبلاً نگاشت برای همان URI را داشته باشد، نگاشت موجود بازنویسی می‌شود. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارزش (value) را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN با هیچ مقداری از جمله NaN برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN با هیچ مقداری از جمله NaN برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\> [get_PreloadedUris](./get_preloadeduris/)() | یک مجموعه از URIهای پیش‌بارگذاری‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetEntity](./getentity/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), const [TypeInfo](../../system/typeinfo/)\&) override | یک URI را به شیئی که شامل منبع واقعی است نگاشت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | هم‌ارز روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به‌دست می‌آورد. هم‌ارز فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. هم‌ارز عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کنندهٔ قفل‌گذاری بیان lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | هم‌ارز روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های فرزند را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع ارزش با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| void [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | داده‌ای که مربوط به URI است را از [XmlPreloadedResolver](./) حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [ResolveUri](./resolveuri/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) override | URI مطلق را با استفاده از URI پایه و نسبی حل می‌کند. |
| void [set_Credentials](./set_credentials/)([SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) override | اعتبارهای مورد استفاده برای احراز هویت [Net::WebRequest](../../system.net/webrequest/) زیرین را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| **bool** [SupportsType](./supportstype/)([SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, const [TypeInfo](../../system/typeinfo/)\&) override | تعیین می‌کند آیا رزولور انواع دیگری علاوه بر Stream را پشتیبانی می‌کند یا نه. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | هم‌ارز روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)() | نمونهٔ جدیدی از کلاس [XmlPreloadedResolver](./) را مقداردهی اولیه می‌کند. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)([XmlKnownDtds](../xmlknowndtds/)) | نمونهٔ جدیدی از کلاس [XmlPreloadedResolver](./) را با DTDهای شناخته‌شده پیش‌بارگذاری‌شده مشخص‌شده مقداردهی اولیه می‌کند. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | نمونهٔ جدیدی از کلاس [XmlPreloadedResolver](./) را با رزولور پشت‌صحنهٔ مشخص‌شده مقداردهی اولیه می‌کند. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/)) | نمونهٔ جدیدی از کلاس [XmlPreloadedResolver](./) را با رزولور پشت‌صحنه و DTDهای شناخته‌شده پیش‌بارگذاری‌شدهٔ مشخص‌شده مقداردهی اولیه می‌کند. |
|  [XmlPreloadedResolver](./xmlpreloadedresolver/)(const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&, [XmlKnownDtds](../xmlknowndtds/), const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\>\>\&) | نمونهٔ جدیدی از کلاس [XmlPreloadedResolver](./) را با رزولور پشت‌صحنهٔ مشخص‌شده، DTDهای شناخته‌شده پیش‌بارگذاری‌شده و مقایسه‌گر برابری URI مقداردهی اولیه می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به نمونه‌ای از این کلاس است. |

## نکات

اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص حافظه شوند. هرگز نمونه‌های این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای تأیید می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید.

## مراجع

* کلاس [XmlResolver](../../system.xml/xmlresolver/)
* فضای‌نام [System::Xml::Resolvers](../)
* کتابخانه [Aspose.Slides](../../)