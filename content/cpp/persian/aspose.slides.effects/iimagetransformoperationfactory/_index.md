---
title: IImageTransformOperationFactory
second_title: مرجع API Aspose.Slides برای C++
description: اجازه می‌دهد تا نمونه‌های افکت‌های تصویر ایجاد شوند
type: docs
weight: 755
url: /fa/aspose.slides.effects/iimagetransformoperationfactory/
---
## کلاس IImageTransformOperationFactory


اجازه می‌دهد تا نمونه‌های افکت‌های تصویر را ایجاد کند

```cpp
class IImageTransformOperationFactory : public virtual System::Object
```

## متدها

| Method | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [CreateAlphaBiLevel](./createalphabilevel/)(**float**) | یک اثر Alpha [BiLevel](../bilevel/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [CreateAlphaFloor](./createalphafloor/)() | یک اثر Alpha floor ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [CreateAlphaInverse](./createalphainverse/)() | یک اثر Alpha inverse ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [CreateAlphaModulate](./createalphamodulate/)() | یک اثر Alpha modulate ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [CreateAlphaModulateFixed](./createalphamodulatefixed/)(**float**) | یک اثر Alpha modulate fixed ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [CreateAlphaReplace](./createalphareplace/)(**float**) | یک اثر Alpha replace ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [CreateAlphCeiling](./createalphceiling/)() | یک اثر Alpha Ceiling ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [CreateBiLevel](./createbilevel/)(**float**) | یک اثر [BiLevel](../bilevel/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [CreateBlur](./createblur/)(**double**, **bool**) | یک اثر [Blur](../blur/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [CreateColorChange](./createcolorchange/)() | یک اثر تغییر رنگ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [CreateColorReplace](./createcolorreplace/)() | یک اثر جایگزینی رنگ ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [CreateDuotone](./createduotone/)() | یک اثر [Duotone](../duotone/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [CreateFillOverlay](./createfilloverlay/)() | یک اثر Fill overlay ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [CreateGrayScale](./creategrayscale/)() | یک اثر Gray scale ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [CreateHSL](./createhsl/)(**float**, **float**, **float**) | یک اثر Hue Saturation [Luminance](../luminance/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [CreateLuminance](./createluminance/)(**float**, **float**) | یک اثر [Luminance](../luminance/) ایجاد می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [CreateTint](./createtint/)(**float**, **float**) | یک اثر [Tint](../tint/) ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخه‌کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخه‌کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr بر پایه مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌ به‌اشتراک‌گذاری شده را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع به‌اشتراک‌گذاری را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع به‌اشتراک‌گذاری را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع به‌اشتراک‌گذاری را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری را با عبارت C# lock() باز می‌کند. مستقیماً فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## ملاحظات

برای رابط COM. 
## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)