---
title: IShapeStyle
second_title: مرجع API Aspose.Slides برای C++
description: مرجع سبک شکل را نمایندگی می‌کند.
type: docs
weight: 3719
url: /fa/aspose.slides/ishapestyle/
---
## IShapeStyle کلاس

Represent shape's style reference.

```cpp
class IShapeStyle : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را در سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را در سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_EffectColor](./get_effectcolor/)() | رنگ اثر شکل را برمی‌گرداند. فقط-خواندنی [IColorFormat](../icolorformat/). |
| virtual **uint32_t** [get_EffectStyleIndex](./get_effectstyleindex/)() | اندیس ستون اثر شکل را در ماتریس سبک برمی‌گرداند. **uint32_t** خواندنی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FillColor](./get_fillcolor/)() | رنگ پر شکل را برمی‌گرداند. فقط-خواندنی [IColorFormat](../icolorformat/). |
| virtual **int16_t** [get_FillStyleIndex](./get_fillstyleindex/)() | اندیس ستون پر شکل را در ماتریس‌های سبک برمی‌گرداند. ۰ به معنی بدون پر، مقدار مثبت – اندیس در سبک‌های پر تم، مقدار منفی – اندیس در سبک‌های پس‌زمینه تم. **int16_t** خواندنی. |
| virtual [Aspose::Slides::FontCollectionIndex](../fontcollectionindex/) [get_FontCollectionIndex](./get_fontcollectionindex/)() | اندیس قلم شکل را در مجموعه قلم‌ها برمی‌گرداند. [Slides::FontCollectionIndex](../fontcollectionindex/) خواندنی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_FontColor](./get_fontcolor/)() | رنگ قلم شکل را برمی‌گرداند. فقط-خواندنی [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_LineColor](./get_linecolor/)() | رنگ خط مرز شکل را برمی‌گرداند. فقط-خواندنی [IColorFormat](../icolorformat/). |
| virtual **uint16_t** [get_LineStyleIndex](./get_linestyleindex/)() | اندیس ستون خط را در ماتریس سبک برمی‌گرداند. **uint16_t** خواندنی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری روی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# ‎'is'‎. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً هیچ چیزی را کپی نمی‌کند؛ تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. واقعاً هیچ چیزی را کپی نمی‌کند؛ تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص برای حالت رشته و nullptr از [Object::ReferenceEquals](../../system/object/referenceequals/). |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص برای حالت رشته‌ها از [Object::ReferenceEquals](../../system/object/referenceequals/). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_EffectStyleIndex](./set_effectstyleindex/)(**uint32_t**) | اندیس ستون اثر شکل را در ماتریس سبک تنظیم می‌کند. **uint32_t** نوشتنی. |
| virtual void [set_FillStyleIndex](./set_fillstyleindex/)(**int16_t**) | اندیس ستون پر شکل را در ماتریس‌های سبک تنظیم می‌کند. ۰ به معنی بدون پر، مقدار مثبت – اندیس در سبک‌های پر تم، مقدار منفی – اندیس در سبک‌های پس‌زمینه تم. **int16_t** نوشتنی. |
| virtual void [set_FontCollectionIndex](./set_fontcollectionindex/)([Aspose::Slides::FontCollectionIndex](../fontcollectionindex/)) | اندیس قلم شکل را در مجموعه قلم‌ها تنظیم می‌کند. [Slides::FontCollectionIndex](../fontcollectionindex/) نوشتنی. |
| virtual void [set_LineStyleIndex](./set_linestyleindex/)(**uint16_t**) | اندیس ستون خط را در ماتریس سبک تنظیم می‌کند. **uint16_t** نوشتنی. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب n-اُم را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در контейنرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازگار با ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)