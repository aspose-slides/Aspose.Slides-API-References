---
title: Reflection
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک اثر Reflection.
type: docs
weight: 1067
url: /fa/aspose.slides.effects/reflection/
---
## Reflection کلاس

نمایش یک اثر [Reflection](./).

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مشخص می‌کند آیا [Reflection](./) مشخص‌شده برابر با [Reflection](./) جاری است. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را در سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای منظورهای داخلی. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) شعاع. فقط خواندنی **double**. |
| **float** [get_Direction](./get_direction/)() override | جهت انعکاس. فقط خواندنی **float**. |
| **double** [get_Distance](./get_distance/)() override | فاصله انعکاس. فقط خواندنی **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | موقعیت انتهایی (در طول مسیر گرادیان آلفا) مقدار آلفای انتهایی (درصد) را مشخص می‌کند. فقط خواندنی **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | شفافیت انتهایی انعکاس. (درصد). فقط خواندنی **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | جهت جابه‌جایی انعکاس را مشخص می‌کند. (زاویه). فقط خواندنی **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) را برمی‌گرداند. فقط-خواندنی [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | تراز مستطیل. فقط خواندنی [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | مشخص می‌کند آیا انعکاس باید با شکل چرخانده شود اگر شکل چرخانده شود. فقط خواندنی **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | عامل مقیاس افقی را مشخص می‌کند؛ مقیاس منفی باعث وارونگی می‌شود. (درصد) فقط خواندنی **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | عامل مقیاس عمودی را مشخص می‌کند؛ مقیاس منفی باعث وارونگی می‌شود. (درصد) فقط خواندنی **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | زاویۀ کراس افقی را مشخص می‌کند. فقط خواندنی **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | زاویۀ کراس عمودی را مشخص می‌کند. فقط خواندنی **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. فقط خواندنی **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | شفافیت شروع انعکاس. (درصد). فقط خواندنی **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | نسخه. فقط-خواندنی **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده مرجع مرتبط با شی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | دریافت داده اثر [Reflection](./) مؤثر با اعمال وراثت. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | به عنوان تابع هش برای یک نوع خاص عمل می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی شی. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با دستور lock() در C#. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان ساختن نسخهٔ مشابه انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | ایجاد شی. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابلهٔ مرجع با شیء نوع مقدار و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) شعاع. نوشتن **double**. |
| void [set_Direction](./set_direction/)(**float**) override | جهت انعکاس. نوشتن **float**. |
| void [set_Distance](./set_distance/)(**double**) override | فاصله انعکاس. نوشتن **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | موقعیت انتهایی (در طول مسیر گرادیان آلفا) مقدار آلفای انتهایی (درصد) را مشخص می‌کند. نوشتن **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | شفافیت انتهایی انعکاس. (درصد). نوشتن **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | جهت جابه‌جایی انعکاس را مشخص می‌کند. (زاویه). نوشتن **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | تراز مستطیل. نوشتن [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | مشخص می‌کند آیا انعکاس باید با شکل چرخانده شود اگر شکل چرخانده شود. نوشتن **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | عامل مقیاس افقی را مشخص می‌کند؛ مقیاس منفی باعث وارونگی می‌شود. (درصد) نوشتن **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | عامل مقیاس عمودی را مشخص می‌کند؛ مقیاس منفی باعث وارونگی می‌شود. (درصد) نوشتن **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | زاویۀ کراس افقی را مشخص می‌کند. نوشتن **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | زاویۀ کراس عمودی را مشخص می‌کند. نوشتن **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | موقعیت شروع (در طول مسیر گرادیان آلفا) مقدار آلفای شروع (درصد) را مشخص می‌کند. نوشتن **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | شفافیت شروع انعکاس. (درصد). نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار فعلی شمارندهٔ مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با دستور lock() در C#. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IReflection](../ireflection/)
* کلاس [IVisualEffect](../ivisualeffect/)
* کلاس [IPVIObject](../../aspose.slides/ipviobject/)
* نام‌فضا [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)