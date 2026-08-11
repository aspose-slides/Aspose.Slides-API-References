---
title: KeyInfoName
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایندهٔ زیرعنصر 'KeyName' در XMLDSIG یا عنصر رمزنگاری 'KeyInfo' در XML. اشیای این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 53
url: /fa/system.security.cryptography.xml/keyinfoname/
---
## KeyInfoName کلاس

نمایش‌دهنده زیرعنصر «KeyName» در XMLDSIG یا عنصر رمزنگاری XML '[KeyInfo](../keyinfo/)'. اشیای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class KeyInfoName : public System::Security::Cryptography::Xml::KeyInfoClause
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیا با استفاده از معنای [Object.Equals](../../system/object/equals/) در C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیا از نوع ارجاعی به سبک C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیا از نوع مقداری به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور در سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، حتی NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطهٔ شناور در سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، حتی NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شی. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | هم‌ارزی با متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شی. هم‌ارزی با فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی اینکه آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. هم‌ارزی با عملگر 'is' در C#. |
|  [KeyInfoName](./keyinfoname/)() |  |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | هم‌ارزی با متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شی. همه ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیز را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | مقایسهٔ اشیا بر اساس ارجاع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | مقایسهٔ اشیا بر اساس ارجاع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شی نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | کاهش شمارندهٔ ارجاع مشترک به مقدار مشخص. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان nام قالب به یک اشاره‌گر ضعیف (به‌جای مشترک). امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ ارجاع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارندهٔ ارجاع مشترک. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش و بازگرداندن شمارندهٔ ارجاع مشترک. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | هم‌ارزی با متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی آزادسازی با عبارت lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارنده ارجاع ضعیف. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارنده ارجاع ضعیف. نباید به‌صورت مستقیم صدا زده شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | نابودسازی شی. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [KeyInfoClause](../keyinfoclause/)
* فضای‌نام [System::Security::Cryptography::Xml](../)
* کتابخانه [Aspose.Slides](../../)