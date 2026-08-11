---
title: PresentationHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: نماینده مدیری است که رفتار تمام مکان‌نگه‌دارهای پاصقفه، تاریخ-زمان و شماره‌صفحه ارائه را در بر می‌گیرد.
type: docs
weight: 4863
url: /fa/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager کلاس

نماینده‌ی مدیری است که رفتار تمام مکان‌نگه‌دارهای پاصقفه، تاریخ-زمان و شماره‌صفحه ارائه را در بر می‌گیرد.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده‌ی قفل کردن در عبارت C# lock() است. مستقیم صدا بزنید یا از شیء نظارت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کلون کردن) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه‌ی کپی در کلاس‌های فرزند را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخه‌ی کپی در کلاس‌های فرزند را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | متن را در تمام مکان‌نگه‌دارهای تاریخ-زمان تنظیم می‌کند، از جمله اسلایدهای اصلی، اسلایدهای طرح‌بندی، اسلایدها، یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | قابلیت مشاهده تمام مکان‌نگه‌دارهای تاریخ-زمان را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی، اسلایدها، یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | متن را در تمام مکان‌نگه‌دارهای پاصقفه تنظیم می‌کند، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی، اسلایدها، یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | قابلیت مشاهده تمام مکان‌نگه‌دارهای پاصقفه را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی، اسلایدها، یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | متن را در تمام مکان‌نگه‌دارهای سرصفحه تنظیم می‌کند، شامل یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | قابلیت مشاهده تمام مکان‌نگه‌دارهای سرصفحه را تغییر می‌دهد، شامل یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | قابلیت مشاهده تمام مکان‌نگه‌دارهای شماره صفحه را تغییر می‌دهد، شامل اسلایدهای اصلی، اسلایدهای طرح‌بندی، اسلایدها، یادداشت‌های اصلی، اسلایدهای یادداشت و قالب توزیع. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محتویات به حالت ضعیف را می‌دهد. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | قابلیت مشاهده مکان‌نگه‌دارهای پاصقفه، تاریخ-زمان و شماره صفحه را برای تمام اسلایدهای عنوان و برای اولین اسلاید طرح‌بندی تغییر می‌دهد. اسلایدهای عنوان \\u2013 اسلایدهایی بر پایه اولین اسلاید طرح‌بندی (بدون درنظر گرفتن نوع این طرح‌بندی اولیه). |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازنده‌ی C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرا کننده‌ی باز کردن قفل در عبارت C# lock() است. مستقیم صدا بزنید یا از شیء نظارت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع مرتبط

* کلاس [BaseHeaderFooterManager](../baseheaderfootermanager/)
* کلاس [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)