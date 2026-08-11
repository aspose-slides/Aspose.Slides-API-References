---
title: IAdjustValue
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار تنظیم یک شکل هندسی را نشان می‌دهد. این مقادیر بر فرم شکل تأثیر می‌گذارند.
type: docs
weight: 1288
url: /fa/aspose.slides/iadjustvalue/
---
## IAdjustValue کلاس

نمایانگر مقدار تنظیم یک شکل هندسی است. این مقادیر بر شکل تأثیر می‌گذارند.

```cpp
class IAdjustValue : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنایی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور شبیه‌سازی شده به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند؛ هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور شبیه‌سازی شده به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند؛ هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_AngleValue](./get_anglevalue/)() | مقدار را بازمی‌گرداند، به عنوان زاویه بر حسب درجه تفسیر می‌کند. خواندن **float**. |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | نام این مقدار تنظیم را بازمی‌گرداند. فقط‌خواندنی [System::String](../../system/string/). |
| virtual **int64_t** [get_RawValue](./get_rawvalue/)() | مقدار تنظیم را همان‌گونه بازمی‌گرداند. خواندن **int64_t**. |
| virtual [ShapeAdjustmentType](../shapeadjustmenttype/) [get_Type](./get_type/)() | نوع تنظیم شکل را بازمی‌گرداند. فقط‌خواندنی [ShapeAdjustmentType](../shapeadjustmenttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دست‌یابی به ساختار داده شمارنده مرجع مرتبط با شی. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دست‌یابی به نوع واقعی شی. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی اینکه آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری (lock()) سبک C#. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AngleValue](./set_anglevalue/)(**float**) | مقدار را تنظیم می‌کند، به عنوان زاویه بر حسب درجه تفسیر می‌کند. نوشتن **float**. |
| virtual void [set_RawValue](./set_rawvalue/)(**int64_t**) | مقدار تنظیم را همان‌گونه تنظیم می‌کند. نوشتن **int64_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | دست‌یابی به مقدار فعلی شمارنده مرجع اشتراکی. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و بازمی‌گرداند. نباید به طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساخت typeof([System.Object](../../system/object/)) سبک C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل (lock()) سبک C#. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به طور مستقیم فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)