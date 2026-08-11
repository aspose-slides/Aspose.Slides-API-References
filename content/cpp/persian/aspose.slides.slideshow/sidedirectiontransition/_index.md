---
title: SideDirectionTransition
second_title: Aspose.Slides برای C++ مرجع API
description: اثر انتقال اسلاید جهت جانبی.
type: docs
weight: 391
url: /fa/aspose.slides.slideshow/sidedirectiontransition/
---
## کلاس SideDirectionTransition

اثر انتقال اسلاید جهت جانبی.

```cpp
class SideDirectionTransition : public Aspose::Slides::SlideShow::TransitionValueBase,
                                public Aspose::Slides::SlideShow::ISideDirectionTransition
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../transitionvaluebase/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تعیین می‌کند که آیا دو نمونه [TransitionValueBase](../transitionvaluebase/) برابر هستند یا خیر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مراجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [TransitionSideDirectionType](../transitionsidedirectiontype/) [get_Direction](./get_direction/)() override | جهت انتقال. [TransitionSideDirectionType](../transitionsidedirectiontype/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](../transitionvaluebase/gethashcode/)() const override | به عنوان تابع هش برای یک نوع خاص عمل می‌کند که برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | متد مشابه [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده‌ای داخلی را مقداردهی اولیه می‌نماید. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء از نوع مقدار (value type) را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Direction](./set_direction/)([TransitionSideDirectionType](../transitionsidedirectiontype/)) override | جهت انتقال. [TransitionSideDirectionType](../transitionsidedirectiontype/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | متد مشابه [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی توسط عبارت lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده‌ای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [TransitionValueBase](../transitionvaluebase/)
* کلاس [ISideDirectionTransition](../isidedirectiontransition/)
* فضای‌نام [Aspose::Slides::SlideShow](../)
* کتابخانه [Aspose.Slides](../../)