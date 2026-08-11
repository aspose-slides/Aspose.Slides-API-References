---
title: IColorFormat
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر رنگی که در یک ارائه استفاده می‌شود.
type: docs
weight: 1691
url: /fa/aspose.slides/icolorformat/
---
## IColorFormat کلاس

نمایانگر رنگی که در یک ارائه استفاده می‌شود.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | قالب رنگ را از \"color\" کپی می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **uint8_t** [get_B](./get_b/)() | مؤلفه آبی یک رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | رنگ حاصل را باز می‌گرداند (با اعمال تمام تبدیلات رنگ). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیلات رنگ را پاک می‌کند. خواندن [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | عملیات تبدیلات رنگ اعمال‌شده بر رنگ در ایندکس مشخص را باز می‌گرداند. خواندن/نوشتن [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | مجموعهٔ تبدیلات رنگ اعمال‌شده بر یک رنگ را بازمی‌گرداند. فقط‌خواندنی [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | روش تعریف رنگ را باز می‌گرداند. خواندن [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | مؤلفه آبی رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | مؤلفه سبز رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | مؤلفه قرمز رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | مؤلفه سبز رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | مؤلفه هیو (Hue) رنگ در نمایش HSL را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | مؤلفه لومننس (Luminance) رنگ در نمایش HSL را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | پیکربندی پیش‌فرض رنگ را باز می‌گرداند. خواندن [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | مؤلفه قرمز رنگ را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | مؤلفه اشباع (Saturation) رنگ در نمایش HSL را باز می‌گرداند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. خواندن **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | رنگ شناسایی‌شده توسط طرح رنگ را باز می‌گرداند. خواندن [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | رنگ شناسایی‌شده توسط جدول رنگ سیستم را باز می‌گرداند. خواندن [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هاشینگ اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | مقدار شمارنده مرجع مشترک را به میزان مشخص کاهش می‌دهد. |
| virtual void [set_B](./set_b/)(**uint8_t**) | مؤلفه آبی رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | رنگ حاصل را باز می‌گرداند (با اعمال تمام تبدیلات رنگ). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیلات رنگ را پاک می‌کند. نوشتن [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | عملیات تبدیلات رنگ اعمال‌شده بر رنگ در ایندکس مشخص را تنظیم می‌کند. خواندن/نوشتن [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | روش تعریف رنگ را تنظیم می‌کند. نوشتن [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | مؤلفه آبی رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | مؤلفه سبز رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | مؤلفه قرمز رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | مؤلفه سبز رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | مؤلفه هیو (Hue) رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | مؤلفه لومننس (Luminance) رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | پیکربندی پیش‌فرض رنگ را تنظیم می‌کند. نوشتن [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | مؤلفه قرمز رنگ را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | مؤلفه اشباع (Saturation) رنگ در نمایش HSL را تنظیم می‌کند. تمام تبدیلات رنگ نادیده گرفته می‌شوند. نوشتن **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | رنگ شناسایی‌شده توسط طرح رنگ را تنظیم می‌کند. نوشتن [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | رنگ شناسایی‌شده توسط جدول رنگ سیستم را تنظیم می‌کند. نوشتن [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب عددی n ام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | یک [System::String](../../system/string/) که قالب رنگ فعلی را نمایندگی می‌کند باز می‌گرداند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل با عبارت lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IFillParamSource](../ifillparamsource/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)