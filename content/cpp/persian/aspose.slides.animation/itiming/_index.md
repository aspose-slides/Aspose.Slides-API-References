---
title: ITiming
second_title: مرجع API Aspose.Slides برای C++
description: نمایش زمان‌بندی انیمیشن.
type: docs
weight: 443
url: /fa/aspose.slides.animation/itiming/
---
## کلاس ITiming

نمایش زمان‌بندی انیمیشن.

```cpp
class ITiming : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از سمانتیک‌های C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | درصد اثر رفتار تسریع مدت زمان را توصیف می‌کند. خواندنی **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | مشخص می‌کند آیا انیمیشن پس از پخش در جهت جلو به‌صورت خودکار در جهت معکوس پخش شود. خواندنی **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | درصد اثر رفتار کاهش سرعت مدت زمان را توصیف می‌کند. خواندنی **float**. |
| virtual **float** [get_Duration](./get_duration/)() | مدت زمان اثر انیمیشن را توصیف می‌کند. خواندنی **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | تعداد دفعات تکرار اثر را توصیف می‌کند. خواندنی **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | تعداد دفعات تکرار اثر را توصیف می‌کند. خواندنی **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | این ویژگی مشخص می‌کند آیا اثر تا انتهای اسلاید تکرار شود. خواندنی **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | این ویژگی مشخص می‌کند آیا اثر تا کلیک بعدی تکرار شود. خواندنی **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | مشخص می‌کند آیا اثر پس از تکمیل باید دوباره شروع شود. خواندنی [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | این ویژگی مشخص می‌کند آیا اثر پس از پایان پخش به‌صورت بازگردانده شود. خواندنی **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | درصدی که زمان‌بندی باید سرعت (یا کاهشی) یابد را مشخص می‌کند. خواندنی **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | زمان تأخیر پس از فعال‌سازی را توصیف می‌کند. خواندنی **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | نوع محرک را توصیف می‌کند. خواندنی [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده نسخه‌برداری. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان نسخه‌برداری از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان نسخه‌برداری از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص‌ ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص‌ ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | درصد اثر رفتار تسریع مدت زمان را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | مشخص می‌کند آیا انیمیشن پس از پخش در جهت جلو به‌صورت خودکار در جهت معکوس پخش شود. نوشتنی **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | درصد اثر رفتار کاهش سرعت مدت زمان را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | مدت زمان اثر انیمیشن را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | تعداد دفعات تکرار اثر را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | تعداد دفعات تکرار اثر را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | این ویژگی مشخص می‌کند آیا اثر تا انتهای اسلاید تکرار شود. نوشتنی **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | این ویژگی مشخص می‌کند آیا اثر تا کلیک بعدی تکرار شود. نوشتنی **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | مشخص می‌کند آیا اثر پس از تکمیل باید دوباره شروع شود. نوشتنی [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | این ویژگی مشخص می‌کند آیا اثر پس از پایان پخش به‌صورت بازگردانده شود. نوشتنی **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | درصدی که زمان‌بندی باید تسریع (یا کاهش) یابد را مشخص می‌کند. نوشتنی **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | زمان تأخیر پس از محرک را توصیف می‌کند. نوشتنی **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | نوع محرک را توصیف می‌کند. نوشتنی [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان جابجایی اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش می‌دهد و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)