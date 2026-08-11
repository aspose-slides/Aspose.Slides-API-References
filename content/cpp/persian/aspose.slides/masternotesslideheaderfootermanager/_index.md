---
title: MasterNotesSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: مدیر را که رفتار فوتر اسلاید یادداشت‌های اصلی، جای‌نگهدارهای تاریخ-زمان، شماره صفحه و تمام جای‌نگهدارهای فرزند را نگه می‌دارد، نشان می‌دهد. جای‌نگهدارهای فرزند به این معنی است که این جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.
type: docs
weight: 4460
url: /fa/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager کلاس

نمایشگر (مدیر)ی است که رفتار فوتر اسلاید یادداشت‌های اصلی، جای‌نگهدارهای تاریخ-زمان، شماره صفحه و تمام جای‌نگهدارهای فرزند را نگه می‌دارد. جای‌نگهدارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند.

```cpp
class MasterNotesSlideHeaderFooterManager : public Aspose::Slides::BaseHandoutNotesSlideHeaderFooterManager,
                                            public Aspose::Slides::IMasterNotesSlideHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN به هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN به هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار تاریخ-زمان وجود دارد. خواندنی**bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار فوتر وجود دارد. خواندنی **bool**. |
| **bool** [get_IsHeaderVisible](../basehandoutnotesslideheaderfootermanager/get_isheadervisible/)() override | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار سرصفحه وجود دارد. خواندنی **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌نگهدار شماره صفحه وجود دارد. خواندنی**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهدار [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع‌ مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند تنظیم می‌کند. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار تاریخ-زمان اسلاید اصلی و تمام جای‌نگهدارهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار تاریخ-زمان اسلاید تنظیم می‌کند. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار تاریخ-زمان اسلاید را تغییر می‌دهد. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار فوتر اسلاید اصلی و تمام جای‌نگهدارهای فوتر فرزند تنظیم می‌کند. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار فوتر اسلاید اصلی و تمام جای‌نگهدارهای فوتر فرزند را تغییر می‌دهد. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار فوتر اسلاید تنظیم می‌کند. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار فوتر اسلاید را تغییر می‌دهد. |
| void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار سرصفحه اسلاید یادداشت اصلی و تمام جای‌نگهدارهای سرصفحه فرزند تنظیم می‌کند. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار سرصفحه اسلاید یادداشت اصلی و تمام جای‌نگهدارهای سرصفحه فرزند را تغییر می‌دهد. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetHeaderText](../basehandoutnotesslideheaderfootermanager/setheadertext/)([System::String](../../system/string/)) override | متن را در جای‌نگهدار سرصفحه اسلاید تنظیم می‌کند. |
| void [SetHeaderVisibility](../basehandoutnotesslideheaderfootermanager/setheadervisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار سرصفحه اسلاید را تغییر می‌دهد. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار شماره صفحه اسلاید اصلی و تمام جای‌نگهدارهای شماره صفحه فرزند را تغییر می‌دهد. جای‌نگه‌دارهای فرزند به این معنی است که جای‌نگهدارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت اصلی استفاده می‌کنند و به آن وابسته‌اند. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌نگهدار شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری از دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهدار [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseHandoutNotesSlideHeaderFooterManager](../basehandoutnotesslideheaderfootermanager/)
* کلاس [IMasterNotesSlideHeaderFooterManager](../imasternotesslideheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)