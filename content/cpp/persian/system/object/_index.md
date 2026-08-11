---
title: Object
second_title: Aspose.Slides برای C++ مرجع API
description: کلاس پایه‌ای که امکان استفاده از متدهای موجود برای کلاس System.Object در C# را فراهم می‌کند. همه کلاس‌های غیر‌ساده‌ای که در محیط ترجمه‌شده استفاده می‌شوند باید از آن ارث‌ببرند.
type: docs
weight: 1132
url: /fa/system/object/
---
## کلاس Object

کلاس پایه که امکان استفاده از متدهای موجود برای [System.Object](./) کلاس در C# را فراهم می‌کند. تمام کلاس‌های غیر‌ساده‌ای که در محیط ترجمه‌شده استفاده می‌شوند باید از آن ارث‌ببرند.

```cpp
class Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | مقایسهٔ اشیاء با استفاده از معنای C# [Object.Equals](./equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء نوع ارجاعی به سبک C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء نوع مقدار به سبک C#. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | معادل متد C# [Object.GetHashCode()](./gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](./gettype/). |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](./lock/)() | اجرا کنندهٔ قفل‌گذاری بیان lock() در C#. مستقیماً فراخوانی شود یا از شیء نگهدارنده [LockContext](../lockcontext/) استفاده شود. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](./memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](./object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](./object/)([Object](./) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها با استفاده از کپی را فراهم می‌سازد. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها با استفاده از کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](./referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص خاص [Object::ReferenceEquals](./referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک weak pointer (نه shared) تنظیم می‌کند. امکان تغییر نشانگرها در مخازن به حالت weak را می‌دهد. |
| int [SharedCount](./sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش داده و مقدار آن را بر می‌گرداند. نباید مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده شود. |
| virtual [String](../string/) [ToString](./tostring/)() const | معادل متد C# [Object.ToString()](./tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | اجرا کنندهٔ سازهٔ typeof([System.Object](./)) در C#. |
| void [Unlock](./unlock/)() | اجرا کنندهٔ آزادسازی بیان lock() در C#. مستقیماً فراخوانی شود یا از شیء نگهدارنده [LockContext](../lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | شمارندهٔ مرجع weak را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](./weakrefremoved/)() | شمارندهٔ مرجع weak را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده شود. |
| virtual  [~Object](./~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [ptr](./ptr/) | نام مستعار برای نوع اشاره‌گر هوشمند. |

## توضیحات

علاوه بر متدهای موجود در کلاس C# [System.Object](./)، این امکان پشتیبانی از برخی مفاهیم خاص محیط کد ترجمه‌شده را نیز فراهم می‌کند. این شامل شمارش مرجع استفاده‌شده توسط کلاس‌های اشاره‌گر هوشمند ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) و سایر سرویس‌های مرتبط با مدیریت حافظه، دیباگ و غیره است.

هر [Object](./) دو شمارندهٔ مرجع دارد: شمارندهٔ مرجع اشتراکی و شمارندهٔ مرجع weak. شمارندهٔ مرجع weak همیشه در ساختار دادهٔ جداگانه‌ای ذخیره می‌شود نه در خود [Object](./) که این امکان را می‌دهد تا اشاره‌گرهای weak پس از از بین رفتن شیء مرجع باقی بمانند. شمارندهٔ مرجع هوشمند یا در خود شیء یا در همان ساختار جداگانه ذخیره می‌شود، بسته به وضعیت ماکرو ENABLE_EXTERNAL_REFCOUNT. به طور پیش‌فرض، در ساخت‌های دیباگ فعال و در ساخت‌های release غیرفعال است. اگر شمارندهٔ اشاره‌گر هوشمند در خود شیء ذخیره شود، ساختار دادهٔ جداگانه فقط هنگامی ساخته می‌شود که اشاره‌گرهای weak به شیء وجود داشته باشند. در غیر این صورت، به همراه خود شیء ساخته می‌شود.

تمام اشاره‌گرهای هوشمند از این دو شمارنده مرجع استفاده می‌کنند و به یک گروه مالکیت واحد و تنها کمک می‌نمایند.

اگر زیرکلاس [Object](./) روی پشته ساخته شود، نمی‌توان اشاره‌گرهای هوشمند به آن ایجاد کرد، در غیر این صورت مسأله حذف از پشته پیش می‌آید.

این نوع می‌تواند یا روی پشته به عنوان نوع مقدار یا در heap با استفاده از تابع [System::MakeObject()](../makeobject/) تخصیص یابد. پس از تخصیص شیء، هرگز این دو حالت استفاده را ترکیب نکنید: داشتن اشاره‌گرهای [SmartPtr](../smartptr/) به اشیاء تخصیص‌یافته در پشته به شدت ممنوع است.

## مراجع

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)