---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides برای C++ مرجع API
description: مدیری را نمایندگی می‌کند که رفتار فوتر اسلاید یادداشت‌های اصلی، جای‌دارهای تاریخ-زمان، شماره صفحه و تمام جای‌دارهای فرزند را در بر می‌گیرد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند.
type: docs
weight: 2900
url: /fa/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager کلاس

مدیری را نشان می‌دهد که رفتار فوتر اسلاید یادداشت‌های اصلی، جای‌دارهای تاریخ-زمان، شماره صفحه و تمام جای‌دارهای فرزند را در بر می‌گیرد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌دار تاریخ-زمان موجود است. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌دار فوتر موجود است. Read **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌دار هدر موجود است. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | مقداری را برمی‌گرداند که نشان می‌دهد یک جای‌دار شماره صفحه موجود است. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به طور مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت subclasses به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت subclasses به‌صورت کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | متن را در جای‌دار تاریخ-زمان اسلاید یادداشت‌های اصلی و تمام جای‌دارهای تاریخ-زمان فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | قابلیت دیده شدن جای‌دار تاریخ-زمان اسلاید یادداشت‌های اصلی و تمام جای‌دارهای تاریخ-زمان فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | متن را در جای‌دار تاریخ-زمان اسلاید تنظیم می‌کند. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | قابلیت دیده شدن جای‌دار تاریخ-زمان اسلاید را تغییر می‌دهد. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | متن را در جای‌دار فوتر اسلاید یادداشت‌های اصلی و تمام جای‌دارهای فوتر فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | قابلیت دیده شدن جای‌دار فوتر اسلاید یادداشت‌های اصلی و تمام جای‌دارهای فوتر فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | متن را در جای‌دار فوتر اسلاید تنظیم می‌کند. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | قابلیت دیده شدن جای‌دار فوتر اسلاید را تغییر می‌دهد. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | متن را در جای‌دار هدر اسلاید یادداشت‌های اصلی و تمام جای‌دارهای هدر فرزند تنظیم می‌کند. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | قابلیت دیده شدن جای‌دار هدر اسلاید یادداشت‌های اصلی و تمام جای‌دارهای هدر فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | متن را در جای‌دار هدر اسلاید تنظیم می‌کند. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | قابلیت دیده شدن جای‌دار هدر اسلاید را تغییر می‌دهد. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | قابلیت دیده شدن جای‌دار شماره صفحه اسلاید یادداشت‌های اصلی و تمام جای‌دارهای شماره صفحه فرزند را تغییر می‌دهد. جای‌دارهای فرزند به این معنی هستند که جای‌دارها در اسلایدهای یادداشت وابسته قرار دارند. اسلایدهای یادداشت وابسته از اسلاید یادداشت‌های اصلی استفاده می‌کنند و به آن وابسته هستند. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | قابلیت دیده شدن جای‌دار شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراک‌گذاری) تنظیم می‌کند. امکان سوئیچ کردن اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. به طور مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)