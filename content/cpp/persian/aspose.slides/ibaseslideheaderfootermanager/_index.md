---
title: IBaseSlideHeaderFooterManager
second_title: مرجع API Aspose.Slides برای C++
description: مدیری را نشان می‌دهد که رفتار فوتر، تاریخ-زمان و جای‌دارهای شماره صفحه را برای همه انواع اسلایدها در بر می‌گیرد.
type: docs
weight: 1509
url: /fa/aspose.slides/ibaseslideheaderfootermanager/
---
## IBaseSlideHeaderFooterManager کلاس

نمایانگر مدیری است که رفتار جای‌متن‌های پاورقی، تاریخ-زمان، شماره صفحه را برای تمام انواع اسلاید در بر می‌گیرد.

```cpp
class IBaseSlideHeaderFooterManager : public Aspose::Slides::IBaseHeaderFooterManager
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_IsDateTimeVisible](./get_isdatetimevisible/)() | مقدار را که نشان می‌دهد یک جای‌متن تاریخ-زمان موجود است، باز می‌گرداند. Read**bool**. |
| virtual **bool** [get_IsFooterVisible](./get_isfootervisible/)() | مقدار را که نشان می‌دهد یک جای‌متن پاورقی موجود است، باز می‌گرداند. Read **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](./get_isslidenumbervisible/)() | مقدار را که نشان می‌دهد یک جای‌متن شماره صفحه موجود است، باز می‌گرداند. Read**bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را باز می‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را باز می‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت C# lock() را انجام می‌دهد. به‌طور مستقیم فراخوانی شود یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده ارجاع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [SetDateTimeText](./setdatetimetext/)([System::String](../../system/string/)) | متن را در جای‌متن تاریخ-زمان اسلاید تنظیم می‌کند. |
| virtual void [SetDateTimeVisibility](./setdatetimevisibility/)(**bool**) | قابلیت مشاهده جای‌متن تاریخ-زمان اسلاید را تغییر می‌دهد. |
| virtual void [SetFooterText](./setfootertext/)([System::String](../../system/string/)) | متن را در جای‌متن پاورقی اسلاید تنظیم می‌کند. |
| virtual void [SetFooterVisibility](./setfootervisibility/)(**bool**) | قابلیت مشاهده جای‌متن پاورقی اسلاید را تغییر می‌دهد. |
| virtual void [SetSlideNumberVisibility](./setslidenumbervisibility/)(**bool**) | قابلیت مشاهده جای‌متن شماره صفحه اسلاید را تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را باز می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشار یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش داده و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشار یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازقفل‌گذاری با عبارت C# lock() را انجام می‌دهد. به‌طور مستقیم فراخوانی شود یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشار یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشار یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [IBaseHeaderFooterManager](../ibaseheaderfootermanager/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)