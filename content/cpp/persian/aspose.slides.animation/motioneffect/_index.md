---
title: MotionEffect
second_title: مرجع API Aspose.Slides برای C++
description: نمایش رفتار اثر حرکتی از یک اثر.
type: docs
weight: 469
url: /fa/aspose.slides.animation/motioneffect/
---
## کلاس MotionEffect

نمایش رفتار اثر حرکتی از یک اثر.

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان مساوی در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان مساوی در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | نمایش می‌دهد آیا رفتارهای انیمیشن انباشته می‌شوند یا خیر. خواندن [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | نمایش می‌دهد آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. خواندن [BehaviorAdditiveType](../behavioradditivetype/). |
| **float** [get_Angle](./get_angle/)() override | زاویه نسبی مسیر حرکت را توصیف می‌کند. خواندن **float**. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. خواندن [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | مختصات x/y شروع انیمیشن (به درصد) را مشخص می‌کند. خواندن [System::Drawing::PointF](../../system.drawing/pointf/). |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | مبدا مسیر حرکت نسبت به چه چیزی (مانند طرح اسلاید یا والد) است را مشخص می‌کند. خواندن [MotionOriginType](../motionorigintype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | مسیر اولیه به همراه مختصات برای حرکت انیمیشن را مشخص می‌کند. خواندن [IMotionPath](../imotionpath/). |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. خواندن [MotionPathEditMode](../motionpatheditmode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | ویژگی‌های رفتار را نشان می‌دهد. فقط-خواندنی [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | مرکز چرخش استفاده‌شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. خواندن [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | ویژگی‌های زمان‌بندی رفتار اثر را نشان می‌دهد. خواندن [ITiming](../itiming/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | موقعیت هدف برای اثر حرکت انیمیشن (به درصد) را مشخص می‌کند. خواندن [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل کردن با دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را می‌دهد. |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و امکان ساخت کپی زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به صورت مرجعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | نمایش می‌دهد آیا رفتارهای انیمیشن انباشته می‌شوند یا خیر. نوشتن [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | نمایش می‌دهد آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. نوشتن [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_Angle](./set_angle/)(**float**) override | زاویه نسبی مسیر حرکت را توصیف می‌کند. نوشتن **float**. |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. نوشتن [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | مختصات x/y شروع انیمیشن (به درصد) را مشخص می‌کند. نوشتن [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | مبدا مسیر حرکت نسبت به چه چیزی (مانند طرح اسلاید یا والد) است را مشخص می‌کند. نوشتن [MotionOriginType](../motionorigintype/). |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | مسیر اولیه به همراه مختصات برای حرکت انیمیشن را مشخص می‌کند. نوشتن [IMotionPath](../imotionpath/). |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | نحوه حرکت مسیر حرکت هنگام جابه‌جایی شکل را مشخص می‌کند. نوشتن [MotionPathEditMode](../motionpatheditmode/). |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | مرکز چرخش استفاده‌شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. نوشتن [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | ویژگی‌های زمان‌بندی رفتار اثر را نشان می‌دهد. نوشتن [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | موقعیت هدف برای اثر حرکت انیمیشن (به درصد) را مشخص می‌کند. نوشتن [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازنده typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [Behavior](../behavior/)
* کلاس [IMotionEffect](../imotioneffect/)
* فضای‌نام [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)