---
title: OuterShadow
second_title: منابع API Aspose.Slides برای C++
description: نمایش یک اثر سایه بیرونی.
type: docs
weight: 1041
url: /fa/aspose.slides.effects/outershadow/
---
## OuterShadow کلاس

نمایش یک اثر سایه بیرونی.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## متدها

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تعیین می‌کند که آیا [OuterShadow](./) مشخص شده برابر با [OuterShadow](./) جاری است. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) شعاع، بر حسب نقطه. مقدار پیش‌فرض \\u2013 0 pt. خواندن **double**. |
| **float** [get_Direction](./get_direction/)() override | جهت سایه، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0 (چپ به راست). خواندن **float**. |
| **double** [get_Distance](./get_distance/)() override | فاصله سایه از شیء، بر حسب نقطه. مقدار پیش‌فرض \\u2013 0 pt. خواندن **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) را باز می‌گرداند. فقط-خواندنی [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | ترازبندی مستطیل. مقدار پیش‌فرض \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). خواندن [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | نشان می‌دهد که آیا سایه همراه شکل می‌چرخد یا خیر. مقدار پیش‌فرض \\u2013 true. خواندن **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | عامل مقیاس افقی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض \\u2013 100 %. خواندن **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | عامل مقیاس عمودی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض \\u2013 100 %. خواندن **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | رنگ سایه. مقدار پیش‌فرض \\u2013 سیاه خودکار (وابسته به تم). فقط-خواندنی [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | زاویهٔ کج شدن افقی، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0. خواندن **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | زاویهٔ کج شدن عمودی، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0. خواندن **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | نسخه. فقط-خواندنی **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | دادهٔ مؤثر اثر سایه بیرونی را با اعمال وراثت دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن نوع‌های سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء نوع مقدار را با nullptr از نظر مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) شعاع، بر حسب نقطه. مقدار پیش‌فرض \\u2013 0 pt. نوشتن **double**. |
| void [set_Direction](./set_direction/)(**float**) override | جهت سایه، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0 (چپ به راست). نوشتن **float**. |
| void [set_Distance](./set_distance/)(**double**) override | فاصله سایه از شیء، بر حسب نقطه. مقدار پیش‌فرض \\u2013 0 pt. نوشتن **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | ترازبندی مستطیل. مقدار پیش‌فرض \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). نوشتن [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | نشان می‌دهد که آیا سایه همراه شکل می‌چرخد یا خیر. مقدار پیش‌فرض \\u2013 true. نوشتن **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | عامل مقیاس افقی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض \\u2013 100 %. نوشتن **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | عامل مقیاس عمودی، به درصد اندازهٔ اصلی. مقیاس منفی باعث وارونه شدن می‌شود. مقدار پیش‌فرض \\u2013 100 %. نوشتن **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | زاویهٔ کج شدن افقی، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0. نوشتن **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | زاویهٔ کج شدن عمودی، بر حسب درجه. مقدار پیش‌فرض \\u2013 0 \\u00B0. نوشتن **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را باز می‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [IOuterShadow](../ioutershadow/)
* کلاس [IVisualEffect](../ivisualeffect/)
* کلاس [IPVIObject](../../aspose.slides/ipviobject/)
* فضای‌نام [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)