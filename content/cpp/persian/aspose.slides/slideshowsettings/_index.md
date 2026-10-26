---
title: SlideShowSettings
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر تنظیمات اسلایدشو برای ارائه.
type: docs
weight: 5214
url: /fa/aspose.slides/slideshowsettings/
---
## SlideShowSettings کلاس

نمایانگر تنظیمات اسلایدشو برای ارائه.

```cpp
class SlideShowSettings : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_Loop](./get_loop/)() | حلقه [Slide](../slide/) نمایش |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_PenColor](./get_pencolor/)() | رنگ قلم برای نمایش [Slide](../slide/) |
| **bool** [get_ShowAnimation](./get_showanimation/)() | نمایش [Animation](../../aspose.slides.animation/) در نمایش [Slide](../slide/) |
| **bool** [get_ShowMediaControls](./get_showmediacontrols/)() const | نمایش کنترل‌های رسانه‌ای |
| **bool** [get_ShowNarration](./get_shownarration/)() | نمایش گفتار در نمایش [Slide](../slide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\> [get_Slides](./get_slides/)() const | [Slides](../) دامنه |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\> [get_SlideShowType](./get_slideshowtype/)() | نوع اسلایدشو را به دست می‌آورد. توسط اجداد [SlideShowType](../slideshowtype/) زیر نشان داده می‌شود: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) و [BrowsedByIndividual](../browsedbyindividual/) |
| **bool** [get_UseTimings](./get_usetimings/)() | استفاده از زمان‌بندی‌ها در نمایش [Slide](../slide/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C#. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Loop](./set_loop/)(**bool**) | حلقه [Slide](../slide/) نمایش |
| void [set_ShowAnimation](./set_showanimation/)(**bool**) | نمایش [Animation](../../aspose.slides.animation/) در نمایش [Slide](../slide/) |
| void [set_ShowMediaControls](./set_showmediacontrols/)(**bool**) | نمایش کنترل‌های رسانه‌ای |
| void [set_ShowNarration](./set_shownarration/)(**bool**) | نمایش گفتار در نمایش [Slide](../slide/) |
| void [set_Slides](./set_slides/)([System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\>) | [Slides](../) دامنه |
| void [set_SlideShowType](./set_slideshowtype/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\>) | نوع اسلایدشو را تنظیم می‌کند. توسط اجداد [SlideShowType](../slideshowtype/) زیر نشان داده می‌شود: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) و [BrowsedByIndividual](../browsedbyindividual/) |
| void [set_UseTimings](./set_usetimings/)(**bool**) | استفاده از زمان‌بندی‌ها در نمایش [Slide](../slide/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارندهٔ ارجاع مشترک را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() در C#. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به صورت مستقیم فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## مراجع مرتبط

* کلاس [Object](../../system/object/)
* فضاي نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)