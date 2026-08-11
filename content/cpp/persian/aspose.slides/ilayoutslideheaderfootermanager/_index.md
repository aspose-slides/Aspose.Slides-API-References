---
title: ILayoutSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: مدیری را نشان می‌دهد که رفتار فوتر اسلاید طرح‌بندی، نگهدارنده‌های تاریخ-زمان، شماره صفحه و تمام نگهدارنده‌های فرزند را نگه می‌دارد. نگهدارنده‌های فرزند به این معنی هستند که این نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند.
type: docs
weight: 2666
url: /fa/aspose.slides/ilayoutslideheaderfootermanager/
---
## ILayoutSlideHeaderFooterManager کلاس

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders. Child placeholders mean placeholders are contained on depending slides. Depending slides use and depend on layout slide.

```cpp
class ILayoutSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseSlideHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989، NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989، NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک نگهدارنده تاریخ-زمان حضور دارد. خواندنی **bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک نگهدارنده فوتر حضور دارد. خواندنی **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک نگهدارنده شماره صفحه حضور دارد. خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء یک نمونه از نوعی که توسط targetType توصیف شده است را نمایندگی می‌کند. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فعال می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فعال می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فعال می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | متن را در نگهدارنده تاریخ-زمان اسلاید طرح‌بندی و تمام نگهدارنده‌های تاریخ-زمان فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی‌اند که نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده تاریخ-زمان اسلاید طرح‌بندی و تمام نگهدارنده‌های تاریخ-زمان فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | متن را در نگهدارنده تاریخ-زمان اسلاید تنظیم می‌کند. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده تاریخ-زمان اسلاید را تغییر می‌دهد. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | متن را در نگهدارنده فوتر اسلاید طرح‌بندی و تمام نگهدارنده‌های فوتر فرزند تنظیم می‌کند. نگهدارنده‌های فرزند به این معنی‌اند که نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده فوتر اسلاید طرح‌بندی و تمام نگهدارنده‌های فوتر فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | متن را در نگهدارنده فوتر اسلاید تنظیم می‌کند. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده فوتر اسلاید را تغییر می‌دهد. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده شماره صفحه اسلاید طرح‌بندی و تمام نگهدارنده‌های شماره صفحه فرزند را تغییر می‌دهد. نگهدارنده‌های فرزند به این معنی‌اند که نگهدارنده‌ها در اسلایدهای وابسته موجود هستند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته‌اند. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | قابلیت مشاهدهٔ نگهدارنده شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل کردن بیان lock() در C# را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBaseSlideHeaderFooterManager](../ibaseslideheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)