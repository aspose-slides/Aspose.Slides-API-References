---
title: Timing
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر زمان‌بندی انیمیشن.
type: docs
weight: 625
url: /fa/aspose.slides.animation/timing/
---
## کلاس Timing

نمایانگر زمان‌بندی انیمیشن است.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_Accelerate](./get_accelerate/)() override | درصد اثر رفتار شتاب‌دهنده در طول زمان را توصیف می‌کند. به **float** خوانده می‌شود. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | مشخص می‌کند آیا پس از پخش به سمت پیش‌رو، انیمیشن به صورت خودکار به عقب پخش شود یا خیر. به **bool** خوانده می‌شود. |
| **float** [get_Decelerate](./get_decelerate/)() override | درصد اثر رفتار کندشده در طول زمان را توصیف می‌کند. به **float** خوانده می‌شود. |
| **float** [get_Duration](./get_duration/)() override | مدت زمان اثر انیمیشن را توصیف می‌کند. به **float** خوانده می‌شود. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | تعداد دفعات تکرار اثر را توصیف می‌کند. به **float** خوانده می‌شود. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | تعداد دفعات تکرار اثر را توصیف می‌کند. به **float** خوانده می‌شود. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | این ویژگی مشخص می‌کند آیا اثر تا پایان اسلاید تکرار شود یا خیر. به **bool** خوانده می‌شود. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | این ویژگی مشخص می‌کند آیا اثر تا کلیک بعدی تکرار شود یا خیر. به **bool** خوانده می‌شود. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | مشخص می‌کند آیا یک اثر پس از کامل شدن مجدداً شروع شود یا نه. به [EffectRestartType](../effectrestarttype/) خوانده می‌شود. |
| **bool** [get_Rewind](./get_rewind/)() override | این ویژگی مشخص می‌کند آیا اثر پس از پایان پخش به عقب برگردد یا نه. به **bool** خوانده می‌شود. |
| **float** [get_Speed](./get_speed/)() override | درصدی که زمان‌بندی باید سرعت بگیرد (یا کاهش یابد) را مشخص می‌کند. به **float** خوانده می‌شود. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | زمان تأخیر پس از تحریک را توصیف می‌کند. به **float** خوانده می‌شود. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | نوع تحریک را توصیف می‌کند. به [EffectTriggerType](../effecttriggertype/) خوانده می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیانیه C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌نماید. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌نماید. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابله مرجع برای شیء نوع مقدار با nullptr انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شماره شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | درصد اثر رفتار شتاب‌دهنده در طول زمان را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | مشخص می‌کند آیا پس از پخش به سمت پیش‌رو، انیمیشن به صورت خودکار به عقب پخش شود یا خیر. **bool** نوشته می‌شود. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | درصد اثر رفتار کندشده در طول زمان را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_Duration](./set_duration/)(**float**) override | مدت زمان اثر انیمیشن را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | تعداد دفعات تکرار اثر را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | تعداد دفعات تکرار اثر را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | این ویژگی مشخص می‌کند آیا اثر تا پایان اسلاید تکرار شود یا خیر. **bool** نوشته می‌شود. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | این ویژگی مشخص می‌کند آیا اثر تا کلیک بعدی تکرار شود یا خیر. **bool** نوشته می‌شود. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | مشخص می‌کند آیا یک اثر پس از کامل شدن مجدداً شروع شود یا نه. [EffectRestartType](../effectrestarttype/) نوشته می‌شود. |
| void [set_Rewind](./set_rewind/)(**bool**) override | این ویژگی مشخص می‌کند آیا اثر پس از پایان پخش به عقب برگردد یا نه. **bool** نوشته می‌شود. |
| void [set_Speed](./set_speed/)(**float**) override | درصدی که زمان‌بندی باید سرعت بگیرد (یا کاهش یابد) را مشخص می‌کند. **float** نوشته می‌شود. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | زمان تأخیر پس از تحریک را توصیف می‌کند. **float** نوشته می‌شود. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | نوع تحریک را توصیف می‌کند. [EffectTriggerType](../effecttriggertype/) نوشته می‌شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام تمپلیت را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیانیه C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ITiming](../itiming/)
* کلاس [IDOMObject](../../aspose.slides/idomobject/)
* فضای‌نام [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)