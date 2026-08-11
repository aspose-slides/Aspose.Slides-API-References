---
title: PrintEventArgs
second_title: مرجع API Aspose.Slides برای C++
description: "داده‌ها را برای رویدادهای BeginPrint و EndPrint فراهم می‌کند. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 92
url: /fa/system.drawing.printing/printeventargs/
---
## PrintEventArgs کلاس

داده‌ها را برای رویدادهای BeginPrint و EndPrint فراهم می‌کند. اشیای این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## متدها

| متد | توضیح |
| --- | --- |
|  [CancelEventArgs](../../system.componentmodel/canceleventargs/canceleventargs/)(**bool**) | سازنده. |
|  [CancelEventArgs](../../system.componentmodel/canceleventargs/canceleventargs/)() | سازنده؛ مقدار Cancel property را به false تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند، هرچند وفق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند، هرچند وفق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
|  [EventArgs](../../system/eventargs/eventargs/)() | سازنده. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_Cancel](../../system.componentmodel/canceleventargs/get_cancel/)() | مقدار نشان‌دهنده این که آیا رویداد باید لغو شود را برمی‌گرداند. |
| [PrintAction](../printaction/) [get_PrintAction](./get_printaction/)() | مقداری را برمی‌گرداند که عمل چاپی را که توسط شیء فعلی نمایان شده است، مشخص می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری دستور C# lock(). مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فعال می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فعال می‌سازد. |
|  [PrintEventArgs](./printeventargs/)() | یک نمونهٔ جدید از شیء [PrintEventArgs](./) می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Cancel](../../system.componentmodel/canceleventargs/set_cancel/)(**bool**) | مقدار نشان‌دهنده این که آیا رویداد باید لغو شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nth را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. اجازه می‌دهد اشاره‌گرها در کانتینرها به حالت ضعیف تبدیل شوند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل دستور C# lock(). مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | یک عضو ثابت که یک اشاره‌گر مشترک \"empty\" [EventArgs](../../system/eventargs/) (null-pointer) را نشان می‌دهد. |

## مراجع

* کلاس [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* فضای نام [System::Drawing::Printing](../)
* کتابخانه [Aspose.Slides](../../)