---
title: ISlideShowTransition
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر انتقال اسلاید شو.
type: docs
weight: 3810
url: /fa/aspose.slides/islideshowtransition/
---
## ISlideShowTransition کلاس

Represents slide show transition.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | این ویژگی مشخص می‌کند که آیا اسلایدشو پس از زمان معینی به اسلاید بعدی می‌رود یا نه. خواندن **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | زمان، بر حسب میلی‌ثانیه، پس از که انتقال باید آغاز شود را مشخص می‌کند. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشود، فرض می‌شود که هیچ پیش‌روی خودکار نمی‌افتد. خواندن **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | مشخص می‌کند که آیا کلیک ماوس اسلاید را پیش می‌برد یا نه. اگر این ویژگی مشخص نشود، مقدار true فرض می‌شود. خواندن **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | مدت زمان اثر انتقال اسلاید را به میلی‌ثانیه دریافت می‌کند. خواندن **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | داده‌های صوتی توکار را برمی‌گرداند. خواندن [IAudio](../iaudio/). |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | مشخص می‌کند که آیا این صدا یک صدا داخلی است یا نه. اگر این ویژگی به true تنظیم شود، برنامه‌ی تولید‌کننده هشدار داده می‌شود تا ویژگی name مشخص‌شده برای این صدا در فهرست صداهای داخلی را بررسی کند و سپس نام یا رابط کاربری سفارشی را ارائه دهد. خواندن **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | این ویژگی مشخص می‌کند که آیا صدا تا رخداد صدا بعدی در اسلاید شو حلقه می‌زند یا نه. خواندن **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | تنظیم یا دریافت حالت صدا برای انتقال اسلاید. خواندن [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | نام خوانا برای صداهای انتقال را مشخص می‌کند. [ISlideShowTransition::set_Sound](./set_sound/) باید برای دریافت یا تنظیم نام صدا اختصاص یابد. خواندن [System::String](../../system/string/). |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | سرعت انتقالی که هنگام رفتن از اسلاید فعلی به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. خواندن [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | نوع انتقال. خواندن [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | مقدار انتقال نمایش [Slide](../slide/). فقط-خواندنی [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی آبجکت‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | این ویژگی مشخص می‌کند که آیا اسلایدشو پس از زمان معینی به اسلاید بعدی می‌رود یا نه. نوشتن **bool**. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | زمان، بر حسب میلی‌ثانیه، پس از که انتقال باید آغاز شود را مشخص می‌کند. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشود، فرض می‌شود که هیچ پیش‌روی خودکار نمی‌افتد. نوشتن **uint32_t**. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | مشخص می‌کند که آیا کلیک ماوس اسلاید را پیش می‌برد یا نه. اگر این ویژگی مشخص نشود، مقدار true فرض می‌شود. نوشتن **bool**. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | مدت زمان اثر انتقال اسلاید را به میلی‌ثانیه تنظیم می‌کند. نوشتن **int32_t**. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | داده‌های صوتی توکار را تنظیم می‌کند. نوشتن [IAudio](../iaudio/). |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | مشخص می‌کند که آیا این صدا یک صدا داخلی است یا نه. اگر این ویژگی به true تنظیم شود، برنامه‌ی تولید‌کننده هشدار داده می‌شود تا ویژگی name مشخص‌شده برای این صدا در فهرست صداهای داخلی را بررسی کند و سپس نام یا رابط کاربری سفارشی را ارائه دهد. نوشتن **bool**. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | این ویژگی مشخص می‌کند که آیا صدا تا رخداد صدا بعدی در اسلاید شو حلقه می‌زند یا نه. نوشتن **bool**. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | تنظیم یا دریافت حالت صدا برای انتقال اسلاید. نوشتن [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/). |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | نام خوانا برای صداهای انتقال را مشخص می‌کند. [ISlideShowTransition::set_Sound](./set_sound/) باید برای دریافت یا تنظیم نام صدا اختصاص یابد. نوشتن [System::String](../../system/string/). |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | سرعت انتقالی که هنگام رفتن از اسلاید فعلی به اسلاید بعدی استفاده می‌شود را تنظیم می‌کند. نوشتن [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/). |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | نوع انتقال. نوشتن [TransitionType](../../aspose.slides.slideshow/transitiontype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه C# typeof([System.Object](../../system/object/)) را اجرا می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)