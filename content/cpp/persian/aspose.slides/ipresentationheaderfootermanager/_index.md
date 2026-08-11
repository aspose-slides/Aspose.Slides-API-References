---
title: IPresentationHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: مدیر را نمایش می‌دهد که رفتار تمام جای‌نگهدارهای پاورقی، تاریخ-زمان و شماره صفحه ارائه را نگه می‌دارد.
type: docs
weight: 3407
url: /fa/aspose.slides/ipresentationheaderfootermanager/
---
## IPresentationHeaderFooterManager کلاس

مدیری را نشان می‌دهد که رفتار تمام جای‌نگهدارهای پاورقی، تاریخ-زمان و شماره صفحه ارائه را نگه می‌دارد.

```cpp
class IPresentationHeaderFooterManager : public virtual Aspose::Slides::IBaseHeaderFooterManager
```

## متدها

| متد | توضیحات |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عدد اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عدد اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده‌های داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان ایجاد هش برای شیءهای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) | متن را برای تمام جای‌نگهدارهای تاریخ-زمان تنظیم می‌کند، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی و اسلایدها. |
| virtual void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) | قابلیت نمایش تمام جای‌نگهدارهای تاریخ-زمان را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی و اسلایدها. |
| virtual void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) | متن را برای تمام جای‌نگهدارهای پاورقی تنظیم می‌کند، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی و اسلایدها. |
| virtual void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) | قابلیت نمایش تمام جای‌نگهدارهای پاورقی را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی و اسلایدها. |
| virtual void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) | متن را برای تمام جای‌نگهدارهای سرصفحه تنظیم می‌کند، شامل نوت‌مست اصلی، اسلایدهای یادداشت و مستر توزیع. |
| virtual void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) | قابلیت نمایش تمام جای‌نگهدارهای سرصفحه را تغییر می‌دهد، شامل نوت‌مست اصلی، اسلایدهای یادداشت و مستر توزیع. |
| virtual void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) | قابلیت نمایش تمام جای‌نگهدارهای شماره صفحه را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی و اسلایدها. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای مشترک). امکان تعویض اشاره‌گرها در مخزن‌ها به حالت ضعیف را می‌دهد. |
| virtual void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) | قابلیت نمایش جای‌نگهدارهای پاورقی، تاریخ-زمان و شماره صفحه را برای تمام اسلایدهای عنوان و اسلاید اول طرح‌بندی تغییر می‌دهد. اسلایدهای عنوان – اسلایدهایی بر پایهٔ اسلاید اول طرح‌بندی (بدون توجه به نوع این طرح‌بندی). |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل شیءهای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IBaseHeaderFooterManager](../ibaseheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)