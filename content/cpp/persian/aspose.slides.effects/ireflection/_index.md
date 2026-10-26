---
title: IReflection
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک افکت بازتاب.
type: docs
weight: 937
url: /fa/aspose.slides.effects/ireflection/
---
## IReflection کلاس

نمایانگر یک افکت بازتاب.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | تقلید از مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | تقلید از مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) شعاع. خواندن **double**. |
| virtual **float** [get_Direction](./get_direction/)() | جهت بازتاب. خواندن **float**. |
| virtual **double** [get_Distance](./get_distance/)() | فاصله بازتاب. خواندن **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | موقعیت پایان (در طول ramp گرادیان آلفا) مقدار آلفای نهایی (درصد) را مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | شفافیت پایان بازتاب. (درصد). خواندن **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | جهت جابجایی بازتاب را مشخص می‌کند. (زاویه). خواندن **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | تراز مستطیل. خواندن [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | مشخص می‌کند که آیا بازتاب هنگام چرخش شکل با آن بچرخد یا خیر. خواندن **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | عامل مقیاس افقی را مشخص می‌کند؛ مقیاس منفی باعث انعکاس می‌شود. (درصد) خواندن **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | عامل مقیاس عمودی را مشخص می‌کند؛ مقیاس منفی باعث انعکاس می‌شود. (درصد) خواندن **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | زاویه کج شدن افقی را مشخص می‌کند. خواندن **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | زاویه کج شدن عمودی را مشخص می‌کند. خواندن **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | موقعیت شروع (در طول ramp گرادیان آلفا) مقدار آلفای ابتدایی (درصد) را مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | شفافیت آغازین بازتاب. (درصد). خواندن **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | داده ساختار شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | داده مؤثر را با اعمال وراثت دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با دستور C# lock(). به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) شعاع. نوشتن **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | جهت بازتاب. نوشتن **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | فاصله بازتاب. نوشتن **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | موقعیت پایان (در طول ramp گرادیان آلفا) مقدار آلفای نهایی (درصد) را مشخص می‌کند. نوشتن **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | شفافیت پایان بازتاب. (درصد). نوشتن **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | جهت جابجایی بازتاب را مشخص می‌کند. (زاویه). نوشتن **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | تراز مستطیل. نوشتن [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | مشخص می‌کند که آیا بازتاب هنگام چرخش شکل با آن بچرخد یا خیر. نوشتن **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | عامل مقیاس افقی را مشخص می‌کند؛ مقیاس منفی باعث انعکاس می‌شود. (درصد) نوشتن **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | عامل مقیاس عمودی را مشخص می‌کند؛ مقیاس منفی باعث انعکاس می‌شود. (درصد) نوشتن **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | زاویه کج شدن افقی را مشخص می‌کند. نوشتن **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | زاویه کج شدن عمودی را مشخص می‌کند. نوشتن **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | موقعیت شروع (در طول ramp گرادیان آلفا) مقدار آلفای ابتدایی (درصد) را مشخص می‌کند. نوشتن **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | شفافیت آغازین بازتاب. (درصد). نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | پارامتر nام قالب را به پوینتر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و مقدار آن را بر می‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با دستور C# lock(). به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [IImageTransformOperation](../iimagetransformoperation/)
* کلاس [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* فضای‌نام [Aspose::Slides::Effects](../)
* کتابخانه [Aspose.Slides](../../)