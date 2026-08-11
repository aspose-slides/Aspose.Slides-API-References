---
title: IEffect
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر اثر انیمیشن.
type: docs
weight: 248
url: /fa/aspose.slides.animation/ieffect/
---
## IEffect کلاس

Represents animation effect.

```cpp
class IEffect : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر وفق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر وفق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | رنگ پس از انیمیشن برای اثر تعریف شده است. خواندن [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | نوع پس از انیمیشن برای اثر تعریف شده است. خواندن [AfterAnimationType](../afteranimationtype/). |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | نوع متن متحرک برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی متحرک شود. خواندن [AnimateTextType](../animatetexttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | رفتار انیمیشن را در ایندکس مشخص‌شده برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | مجموعه‌ای از رفتارها برای اثر را برمی‌گرداند. خواندن [IBehaviorCollection](../ibehaviorcollection/). |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | تاخیر بین بخش‌های متن متحرک (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر بر حسب ثانیه را مشخص می‌کند. خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | تأثیر یک توالی را در ایندکس مشخص‌شده برمی‌گرداند. |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | کلاس اثر را تعریف می‌کند. خواندن [EffectPresetClassType](../effectpresetclasstype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | یک توالی برای اثر برمی‌گرداند. فقط-خواندنی [ISequence](../isequence/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | صدا توکار برای اثر تعریف شده است. خواندن [IAudio](../../aspose.slides/iaudio/). |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. خواندن **bool**. |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | زیرفرمت اثر را تعریف می‌کند. خواندن [EffectSubtype](../effectsubtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | شکل هدف برای اثر را برمی‌گرداند. فقط-خواندنی [IShape](../../aspose.slides/ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | انیمیشن متن را برمی‌گرداند. فقط-خواندنی [ITextAnimation](../itextanimation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | مقدار زمان‌بندی برای اثر را تعریف می‌کند. خواندن [ITiming](../itiming/). |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | نوع اثر را تعریف می‌کند. خواندن [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل کردن با عبارت lock() در C#. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص برای [Object::ReferenceEquals](../../system/object/referenceequals/) در حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص برای [Object::ReferenceEquals](../../system/object/referenceequals/) در حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | رنگ پس از انیمیشن برای اثر تعریف می‌شود. نوشتن [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | نوع پس از انیمیشن برای اثر تعریف می‌شود. نوشتن [AfterAnimationType](../afteranimationtype/). |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | نوع متن متحرک برای اثر را تعریف می‌کند. متن شکل می‌تواند به صورت حرف، کلمه یا به‌صورت کلی متحرک شود. نوشتن [AnimateTextType](../animatetexttype/). |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | رفتار انیمیشن را در ایندکس مشخص‌شده تنظیم می‌کند. |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | مجموعه‌ای از رفتارها برای اثر را برمی‌گرداند. نوشتن [IBehaviorCollection](../ibehaviorcollection/). |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | تاخیر بین بخش‌های متن متحرک (کلمات یا حروف) را تعریف می‌کند. مقدار مثبت درصد مدت اثر را مشخص می‌کند. مقدار منفی تاخیر بر حسب ثانیه را مشخص می‌کند. نوشتن **float**. |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | کلاس اثر را تعریف می‌کند. نوشتن [EffectPresetClassType](../effectpresetclasstype/). |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | صدا توکار برای اثر تعریف شده است. نوشتن [IAudio](../../aspose.slides/iaudio/). |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | این ویژگی مشخص می‌کند که آیا اثر انیمیشن صدای قبلی را متوقف می‌کند یا نه. نوشتن **bool**. |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | زیرفرمت اثر را تعریف می‌کند. نوشتن [EffectSubtype](../effectsubtype/). |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | مقدار زمان‌بندی برای اثر را تعریف می‌کند. نوشتن [ITiming](../itiming/). |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | نوع اثر را تعریف می‌کند. نوشتن [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار کنونی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل با عبارت lock() در C#. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)