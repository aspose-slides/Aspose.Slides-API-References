---
title: FlagsAttribute
second_title: Aspose.Slides برای C++ مرجع API
description: نشان می‌دهد که یک شمارش می‌تواند به عنوان یک فیلد بیتی رفتار کند؛ یعنی، یک مجموعه از.
type: docs
weight: 846
url: /fa/system/flagsattribute/
---
## FlagsAttribute کلاس

به این معنی که یک شمارش می‌تواند به عنوان یک بیت فیلد رفتار شود؛ یعنی، یک مجموعه از.

```cpp
class FlagsAttribute : public System::Attribute
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| static [Object::ptr](../object/ptr/) [GetCustomAttribute](../attribute/getcustomattribute/)(const [TypeInfo](../typeinfo/)\&, const [TypeInfo](../typeinfo/)\&) | یک ویژگی سفارشی از نوع مشخص شده را که به نوع مشخص شده اعمال شده است برمی‌گرداند. |
| static [ArrayPtr](../arrayptr/)\<[Object::ptr](../object/ptr/)\> [GetCustomAttributes](../attribute/getcustomattributes/)(const [TypeInfo](../typeinfo/)\&) | همه ویژگی‌های سفارشی اعمال شده به نوع مشخص شده را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). قابلیت رونوشت (کلون) انواع سفارشی را فعال می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به‌صورت مرجعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | مقدار شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | معادل متد C# [Object.ToString()](../object/tostring/). تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | عبارت typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | قفل‌برداری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## همچنین ببینید

* کلاس [Attribute](../attribute/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)