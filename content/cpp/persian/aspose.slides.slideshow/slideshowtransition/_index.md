---
title: SlideShowTransition
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر انتقال اسلایدشو.
type: docs
weight: 404
url: /fa/aspose.slides.slideshow/slideshowtransition/
---
## کلاس SlideShowTransition

Represents slide show transition.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## متدها

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تعیین می‌کند که آیا دو نمونه [SlideShowTransition](./) برابر هستند یا خیر. خواندنی/نوشتنی **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیاء با استفاده از مفهوم [Object.Equals](../../system/object/equals/) در C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء نوع مرجع به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | این ویژگی مشخص می‌کند آیا نمایش اسلاید پس از زمان معینی به اسلاید بعدی می‌رود یا خیر. خواندنی **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | زمان را به میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید آغاز شود. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشده باشد، فرض می‌شود که پیشرفت خودکار رخ نمی‌دهد. خواندنی **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا نه. اگر این ویژگی مشخص نشده باشد، مقدار true فرض می‌شود. خواندنی **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | دورهٔ اثر انتقال اسلاید را به میلی‌ثانیه دریافت می‌کند. خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | داده‌های صوتی تعبیه‌شده را بازمی‌گرداند. خواندنی [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | مشخص می‌کند آیا این صدا صدا داخلی است یا نه. اگر این ویژگی به true تنظیم شود، برنامهٔ تولیدکننده هشدار داده می‌شود تا ویژگی name را که برای این صدا در فهرست صداهای داخلی تعیین شده است، بررسی کند و در صورت نیاز نام یا رابط کاربری سفارشی را نمایش دهد. خواندنی **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | این ویژگی مشخص می‌کند آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلایدها تکرار می‌شود یا خیر. خواندنی **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | تنظیم یا بازگرداندن حالت صدا برای انتقال اسلاید. خواندنی [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. برای دریافت یا تنظیم نام صدا باید [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) اختصاص یابد. خواندنی [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | سرعت انتقالی که هنگام انتقال از اسلاید جاری به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. خواندنی [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | نوع انتقال. خواندنی [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) مقدار انتقال نمایش را نشان می‌دهد. فقط-خواندنی [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | به عنوان تابع هش برای یک نوع خاص عمل می‌کند که مناسب استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش است. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با استفاده از عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | این ویژگی مشخص می‌کند آیا نمایش اسلاید پس از زمان معینی به اسلاید بعدی می‌رود یا خیر. نوشتنی **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | زمان را به میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید آغاز شود. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشده باشد، فرض می‌شود که پیشرفت خودکار رخ نمی‌دهد. نوشتنی **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا نه. اگر این ویژگی مشخص نشده باشد، مقدار true فرض می‌شود. نوشتنی **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | دورهٔ اثر انتقال اسلاید را به میلی‌ثانیه تنظیم می‌کند. نوشتنی **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | داده‌های صوتی تعبیه‌شده را تنظیم می‌کند. نوشتنی [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | مشخص می‌کند آیا این صدا صدا داخلی است یا نه. اگر این ویژگی به true تنظیم شود، برنامهٔ تولیدکننده هشدار داده می‌شود تا ویژگی name را که برای این صدا در فهرست صداهای داخلی تعیین شده است، بررسی کند و در صورت نیاز نام یا رابط کاربری سفارشی را نمایش دهد. نوشتنی **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | این ویژگی مشخص می‌کند آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلایدها تکرار می‌شود یا خیر. نوشتنی **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | تنظیم یا بازگرداندن حالت صدا برای انتقال اسلاید. نوشتنی [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. برای دریافت یا تنظیم نام صدا باید [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) اختصاص یابد. نوشتنی [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | سرعت انتقالی که هنگام انتقال از اسلاید جاری به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. نوشتنی [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | نوع انتقال. نوشتنی [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان nام الگوی قالب را به اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با استفاده از عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* فضای‌نام [Aspose::Slides::SlideShow](../)
* کتابخانه [Aspose.Slides](../../)