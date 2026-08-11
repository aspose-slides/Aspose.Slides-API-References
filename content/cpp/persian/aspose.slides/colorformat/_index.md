---
title: ColorFormat
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر رنگی است که در یک ارائه استفاده می‌شود.
type: docs
weight: 339
url: /fa/aspose.slides/colorformat/
---
## کلاس ColorFormat

نمایانگر رنگی است که در یک ارائه استفاده می‌شود.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | قالب رنگ را از \"color\" کپی می‌کند. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | برابری را با شیء مشخص‌شده بررسی می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مراجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **uint8_t** [get_B](./get_b/)() override | جزء آبی یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | رنگ حاصل را بر می‌گرداند (با اعمال تمام تبدیلات رنگ). رنگ‌های RGB را تنظیم کرده و تمام تبدیلات رنگ را پاک می‌کند. خواندن [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | عملیات تبدیل رنگ اعمال‌شده به رنگ در شاخص مشخص را بر می‌گرداند. خواندن/نوشتن [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | مجموعه تبدیلات رنگ اعمال‌شده به یک رنگ را بر می‌گرداند. فقط-خواندنی [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | روش تعریف رنگ را بر می‌گرداند. خواندن [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | جزء آبی یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| **float** [get_FloatG](./get_floatg/)() override | جزء سبز یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| **float** [get_FloatR](./get_floatr/)() override | جزء قرمز یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| **uint8_t** [get_G](./get_g/)() override | جزء سبز یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. |
| **float** [get_Hue](./get_hue/)() override | جزء هیو (Hue) یک رنگ در نمایش HSL را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| **float** [get_Luminance](./get_luminance/)() override | جزء لومنانس یک رنگ در نمایش HSL را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شی Parent_Immediate را بر می‌گرداند. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را بر می‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | پیش‌تنظیم رنگ را بر می‌گرداند. خواندن [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | جزء قرمز یک رنگ را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | جزء اشباع (Saturation) یک رنگ در نمایش HSL را بر می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | رنگ شناسایی‌شده توسط یک طرح رنگ را بر می‌گرداند. خواندن [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم را بر می‌گرداند. خواندن [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | کد هش را بر می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری وفق دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء ستودار [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فعال می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را فعال می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مورد نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_B](./set_b/)(**uint8_t**) override | جزء آبی یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | رنگ حاصل را بر می‌گرداند (با اعمال تمام تبدیلات رنگ). رنگ‌های RGB را تنظیم کرده و تمام تبدیلات رنگ را پاک می‌کند. نوشتن [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | عملیات تبدیل رنگ اعمال‌شده به رنگ در شاخص مشخص را تنظیم می‌کند. خواندن/نوشتن [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | روش تعریف رنگ را تنظیم می‌کند. نوشتن [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | جزء آبی یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | جزء سبز یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | جزء قرمز یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | جزء سبز یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. |
| void [set_Hue](./set_hue/)(**float**) override | جزء هیو (Hue) یک رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | جزء لومنانس یک رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | پیش‌تنظیم رنگ را تنظیم می‌کند. نوشتن [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | جزء قرمز یک رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | جزء اشباع (Saturation) یک رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | رنگ شناسایی‌شده توسط یک طرح رنگ را تنظیم می‌کند. نوشتن [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم را تنظیم می‌کند. نوشتن [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو شماره n را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کنتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | یک [System::String](../../system/string/) که قالب رنگ فعلی را نشان می‌دهد، بر می‌گرداند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی وفق دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء ستودار [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [PVIObject](../pviobject/)
* کلاس [IColorFormat](../icolorformat/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)