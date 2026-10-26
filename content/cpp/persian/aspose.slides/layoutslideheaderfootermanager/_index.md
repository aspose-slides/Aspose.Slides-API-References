---
title: LayoutSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: مدیریت را نشان می‌دهد که رفتار فوتر اسلاید طرح‌بندی، تاریخ-زمان، جای‌گذاری شماره صفحه و تمام جای‌گذاری‌های فرزند را نگه می‌دارد. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند.
type: docs
weight: 4317
url: /fa/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager کلاس


مدیری را که رفتار فوتر اسلاید طرح‌بندی، تاریخ-زمان، جای‌گذاری شماره صفحه و تمام جای‌گذاری‌های فرزند را نگه می‌دارد، نشان می‌دهد. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند.

```cpp
class LayoutSlideHeaderFooterManager : public Aspose::Slides::BaseSlideHeaderFooterManager,
                                       public Aspose::Slides::ILayoutSlideHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر در نظر گرفته شوند حتی اگر بر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر در نظر گرفته شوند حتی اگر بر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_IsDateTimeVisible](../baseslideheaderfootermanager/get_isdatetimevisible/)() override | دریافت مقدار نشان‌دهندهٔ وجود یک جای‌گذاری تاریخ-زمان. خواندنی **bool**. |
| **bool** [get_IsFooterVisible](../baseslideheaderfootermanager/get_isfootervisible/)() override | دریافت مقدار نشان‌دهندهٔ وجود یک جای‌گذاری فوتر. خواندنی **bool**. |
| **bool** [get_IsSlideNumberVisible](../baseslideheaderfootermanager/get_isslidenumbervisible/)() override | دریافت مقدار نشان‌دهندهٔ وجود یک جای‌گذاری شماره صفحه. خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارندهٔ ارجاع مرتبط با شیء. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شیء. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی اینکه آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل (lock()) در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | یک شیء ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع-مقایسهٔ شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) override | متن را برای جای‌گذاری تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گذاری‌های تاریخ-زمان فرزند تنظیم می‌کند. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌گذاری تاریخ-زمان اسلاید طرح‌بندی و تمام جای‌گذاری‌های تاریخ-زمان فرزند را تغییر می‌دهد. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetDateTimeText](../baseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) override | متن را برای جای‌گذاری تاریخ-زمان اسلاید تنظیم می‌کند. |
| void [SetDateTimeVisibility](../baseslideheaderfootermanager/setdatetimevisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌گذاری تاریخ-زمان اسلاید را تغییر می‌دهد. |
| void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) override | متن را برای جای‌گذاری فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند تنظیم می‌کند. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) override | قابلیت مشاهدهٔ فوتر اسلاید طرح‌بندی و تمام فوترهای فرزند را تغییر می‌دهد. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید اصلی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetFooterText](../baseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) override | متن را برای جای‌گذاری فوتر اسلاید تنظیم می‌کند. |
| void [SetFooterVisibility](../baseslideheaderfootermanager/setfootervisibility/)(**bool**) override | قابلیت مشاهدهٔ فوتر اسلاید را تغییر می‌دهد. |
| void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌گذاری شماره صفحه اسلاید طرح‌بندی و تمام جای‌گذاری‌های شماره صفحه فرزند را تغییر می‌دهد. جای‌گذاری‌های فرزند به این معنی هستند که جای‌گذاری‌ها در اسلایدهای وابسته قرار دارند. اسلایدهای وابسته از اسلاید طرح‌بندی استفاده می‌کنند و به آن وابسته هستند. |
| void [SetSlideNumberVisibility](../baseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) override | قابلیت مشاهدهٔ جای‌گذاری شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | تنظیم آرگومان الیتمپلیت nام به عنوان اشاره‌گر ضعیف (به‌جای مشترک). امکان تعویض اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ ارجاع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | افزایش شمارندهٔ ارجاع مشترک. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | کاهش و بازگرداندن شمارندهٔ ارجاع مشترک. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای قفل (lock()) در C# را باز می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | افزایش شمارندهٔ ارجاع ضعیف. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | کاهش شمارندهٔ ارجاع ضعیف. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseSlideHeaderFooterManager](../baseslideheaderfootermanager/)
* کلاس [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)