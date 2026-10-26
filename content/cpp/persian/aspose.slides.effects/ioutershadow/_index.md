---
title: IOuterShadow
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک اثر سایهٔ بیرونی است.
type: docs
weight: 885
url: /fa/aspose.slides.effects/ioutershadow/
---
## IOuterShadow کلاس


نمایانگر اثر سایهٔ بیرونی است.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) شعاع، بر حسب نقطه. مقدار پیش‌فرض – 0 pt. خواندنی **double**. |
| virtual **float** [get_Direction](./get_direction/)() | جهت سایه، بر حسب درجه. مقدار پیش‌فرض – 0 ° (از چپ به راست). خواندنی **float**. |
| virtual **double** [get_Distance](./get_distance/)() | فاصله سایه از شی، بر حسب نقطه. مقدار پیش‌فرض – 0 pt. خواندنی **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | ترازبندی مستطیل. مقدار پیش‌فرض – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). خواندنی [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | نشان می‌دهد آیا سایه همراه با شکل می‌چرخد یا خیر. مقدار پیش‌فرض – true. خواندنی **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | عامل مقیاس افقی، به درصد اندازه اصلی. مقیاس منفی منجر به وارونه شدن می‌شود. مقدار پیش‌فرض – 100 %. خواندنی **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | عامل مقیاس عمودی، به درصد اندازه اصلی. مقیاس منفی منجر به وارونه شدن می‌شود. مقدار پیش‌فرض – 100 %. خواندنی **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | رنگ سایه. مقدار پیش‌فرض – سیاه خودکار (وابسته به تم). فقط‌خواندنی [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | زاویهٔ کشیدگی افقی، بر حسب درجه. مقدار پیش‌فرض – 0 °. خواندنی **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | زاویهٔ کشیدگی عمودی، بر حسب درجه. مقدار پیش‌فرض – 0 °. خواندنی **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | دادهٔ مؤثر را با اعمال وراثت دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شی نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) شعاع، بر حسب نقطه. مقدار پیش‌فرض – 0 pt. نوشتنی **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | جهت سایه، بر حسب درجه. مقدار پیش‌فرض – 0 ° (از چپ به راست). نوشتنی **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | فاصله سایه از شی، بر حسب نقطه. مقدار پیش‌فرض – 0 pt. نوشتنی **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | ترازبندی مستطیل. مقدار پیش‌فرض – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). نوشتنی [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | نشان می‌دهد آیا سایه همراه با شکل می‌چرخد یا خیر. مقدار پیش‌فرض – true. نوشتنی **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | عامل مقیاس افقی، به درصد اندازه اصلی. مقیاس منفی منجر به وارونه شدن می‌شود. مقدار پیش‌فرض – 100 %. نوشتنی **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | عامل مقیاس عمودی، به درصد اندازه اصلی. مقیاس منفی منجر به وارونه شدن می‌شود. مقدار پیش‌فرض – 100 %. نوشتنی **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | زاویهٔ کشیدگی افقی، بر حسب درجه. مقدار پیش‌فرض – 0 °. نوشتنی **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | زاویهٔ کشیدگی عمودی، بر حسب درجه. مقدار پیش‌فرض – 0 °. نوشتنی **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | ارزش فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مرتبط

* کلاس [IImageTransformOperation](../iimagetransformoperation/)
* کلاس [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* فضای‌نام [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)