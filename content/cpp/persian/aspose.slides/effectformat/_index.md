---
title: EffectFormat
second_title: مرجع API Aspose.Slides برای C++
description: خواص اثر شکل را نمایش می‌دهد.
type: docs
weight: 846
url: /fa/aspose.slides/effectformat/
---
## EffectFormat کلاس

خواص اثر شکل را نمایش می‌دهد.

```cpp
class EffectFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IEffectFormat
```

## Methods

| Method | Description |
| --- | --- |
| void [DisableBlurEffect](./disableblureffect/)() override | اثر تاری را غیرفعال می‌کند. |
| void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() override | اثر پوشش پر کردن را غیرفعال می‌کند. |
| void [DisableGlowEffect](./disablegloweffect/)() override | اثر تابش را غیرفعال می‌کند. |
| void [DisableInnerShadowEffect](./disableinnershadoweffect/)() override | اثر سایهٔ داخلی را غیرفعال می‌کند. |
| void [DisableOuterShadowEffect](./disableoutershadoweffect/)() override | اثر سایهٔ خارجی را غیرفعال می‌کند. |
| void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() override | اثر سایهٔ پیش‌تنظیم شده را غیرفعال می‌کند. |
| void [DisableReflectionEffect](./disablereflectioneffect/)() override | اثر بازتاب را غیرفعال می‌کند. |
| void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() override | اثر لبهٔ نرم را غیرفعال می‌کند. |
| void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() override | اثر پوشش پر کردن را فعال می‌کند. |
| void [EnableGlowEffect](./enablegloweffect/)() override | اثر تابش را فعال می‌کند. |
| void [EnableInnerShadowEffect](./enableinnershadoweffect/)() override | اثر سایهٔ داخلی را فعال می‌کند. |
| void [EnableOuterShadowEffect](./enableoutershadoweffect/)() override | اثر سایهٔ خارجی را فعال می‌کند. |
| void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() override | اثر سایه‌های پیش‌تنظیم شده را فعال می‌کند. |
| void [EnableReflectionEffect](./enablereflectioneffect/)() override | اثر بازتاب را فعال می‌کند. |
| void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() override | اثر لبهٔ نرم را فعال می‌کند. |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | با شیء مشخص‌شده مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() override | اثر تاری. [Effects::IBlur](../../aspose.slides.effects/iblur/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() override | اثر پوشش پر کردن. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() override | اثر تابش. [Effects::IGlow](../../aspose.slides.effects/iglow/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() override | سایهٔ داخلی. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) را بخوانید. |
| **bool** [get_IsNoEffects](./get_isnoeffects/)() override | در صورتی که همهٔ اثرها غیرفعال باشند (مانند یک شیء تازه ساخته شده، پیش‌فرض [EffectFormat](./)) مقدار true را برمی‌گرداند. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() override | سایهٔ خارجی. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) را بخوانید. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() override | سایهٔ پیش‌تنظیم شده. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() override | بازتاب. [Effects::IReflection](../../aspose.slides.effects/ireflection/) را بخوانید. |
| [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() override | لبهٔ نرم. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دسترسی به ساختار داده شمارندهٔ مرجع مرتبط با شیء را به‌دست می‌آورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() override | دسترسی به داده‌های قالب‌بندی مؤثر اثر با اعمال وراثت را به‌دست می‌آورد. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | عملیات قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. چیزی را کپی نمی‌کند، در واقع فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت اشیاء فرزند را از طریق کپی فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. چیزی را کپی نمی‌کند، در واقع فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت اشیاء فرزند را از طریق کپی فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء مقدار نوع را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های اشتراکی را با مقدار مشخص کاهش می‌دهد. |
| void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) override | اثر تاری. [Effects::IBlur](../../aspose.slides.effects/iblur/) را بنویسید. |
| void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) override | اثر پوشش پر کردن. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) را بنویسید. |
| void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) override | اثر تابش. [Effects::IGlow](../../aspose.slides.effects/iglow/) را بنویسید. |
| void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) override | سایهٔ داخلی. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) را بنویسید. |
| void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) override | سایهٔ خارجی. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) را بنویسید. |
| void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) override | سایهٔ پیش‌تنظیم شده. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) را بنویسید. |
| void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) override | بازتاب. [Effects::IReflection](../../aspose.slides.effects/ireflection/) را بنویسید. |
| void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) override | لبهٔ نرم. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) را بنویسید. |
| void [SetBlurEffect](./setblureffect/)(**double**, **bool**) override | اثر تاری را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان ال nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملیات باز‌قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [PVIObject](../pviobject/)
* کلاس [IEffectFormat](../ieffectformat/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)