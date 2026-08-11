---
title: MasterSlideHeaderFooterManager
second_title: Aspose.Slides برای مرجع API C++
description: نماینده‌ای است که مدیریت رفتار فوتر اسلاید اصلی، نگهدارنده‌های تاریخ-زمان، شماره صفحه و تمام نگهدارنده‌های فرزند را بر عهده دارد. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.
type: docs
weight: 4499
url: /fa/aspose.slides/masterslideheaderfootermanager/
---
## کلاس MasterSlideHeaderFooterManager

نمایش‌دهنده‌ی مدیری است که رفتار فوتر اسلاید اصلی، تاریخ-زمان، نگهدارنده شماره صفحه و تمام نگهدارنده‌های فرزند را نگه می‌دارد. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند.

```cpp
class MasterSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::IMasterSlideHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند در حالی که طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند در حالی که طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | دریافت مقداری که نشان می‌دهد یک نگهدارنده تاریخ-زمان حضور دارد. خواندن**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | دریافت مقداری که نشان می‌دهد یک نگهدارنده پاورقی حضور دارد. خواندن **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | دریافت مقداری که نشان می‌دهد یک نگهدارنده شماره صفحه حضور دارد. خواندن**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده ارجاع مرتبط با شی. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شی. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شی نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | متن را برای نگهدارنده تاریخ-زمان اسلاید اصلی و تمام نگهدارنده‌های تاریخ-زمان فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده تاریخ-زمان اسلاید اصلی و تمام نگهدارنده‌های تاریخ-زمان فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | متن را برای نگهدارنده تاریخ-زمان اسلاید تنظیم می‌کند. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده تاریخ-زمان اسلاید را تغییر می‌دهد. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | متن را برای نگهدارنده پاورقی اسلاید اصلی و تمام نگهدارنده‌های پاورقی فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده پاورقی اسلاید اصلی و تمام نگهدارنده‌های پاورقی فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | متن را برای نگهدارنده پاورقی اسلاید تنظیم می‌کند. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده پاورقی اسلاید را تغییر می‌دهد. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده شماره صفحه اسلاید اصلی و تمام نگهدارنده‌های شماره صفحه فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که این نگهدارنده‌ها در اسلایدهای طرح‌بندی وابسته و اسلایدهای وابسته قرار دارند. اسلایدهای طرح‌بندی وابسته و اسلایدها از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | قابلیت مشاهده نگهدارنده شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تبدیل اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارنده مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌شکنی بیانیه C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* کلاس [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)