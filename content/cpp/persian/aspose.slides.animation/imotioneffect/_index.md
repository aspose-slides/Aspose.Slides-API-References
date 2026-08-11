---
title: IMotionEffect
second_title: Aspose.Slides برای C++ مرجع API
description: رفتار اثر حرکتی را نمایش می‌دهد.
type: docs
weight: 287
url: /fa/aspose.slides.animation/imotioneffect/
---
## کلاس IMotionEffect

Represent motion effect behavior of effect.

```cpp
class IMotionEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | نمایانگر این است که آیا رفتارهای انیمیشن انباشته می‌شوند. خواند [NullableBool](../../aspose.slides/nullablebool/). |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | نمایانگر این است که آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. خواند [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual **float** [get_Angle](./get_angle/)() | زاویه نسبی مسیر حرکت را توصیف می‌کند. خواند **float**. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. خواند [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | مختصات x/y را برای شروع انیمیشن (به درصد) مشخص می‌کند. خواند [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() | مشخص می‌کند مبدا مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. خواند [MotionOriginType](../motionorigintype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() | ابتدا مسیر را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. خواند [IMotionPath](../imotionpath/). |
| virtual [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() | نحوه حرکت مسیر حرکت هنگام جابجایی شکل را مشخص می‌کند. خواند [MotionPathEditMode](../motionpatheditmode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | خواص رفتار را نمایان می‌کند. فقط‌خواندنی [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() | مرکز چرخش استفاده‌شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. خواند [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | خواص زمان‌بندی رفتار اثر را نمایان می‌کند. خواند [ITiming](../itiming/). |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | موقعیت هدف برای اثر حرکت انیمیشن (به درصد) را مشخص می‌کند. خواند [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به‌صورت مرجع-مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | نمایانگر این است که آیا رفتارهای انیمیشن انباشته می‌شوند. نوشت [NullableBool](../../aspose.slides/nullablebool/). |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | نمایانگر این است که آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. نوشت [BehaviorAdditiveType](../behavioradditivetype/). |
| virtual void [set_Angle](./set_angle/)(**float**) | زاویه نسبی مسیر حرکت را توصیف می‌کند. نوشت **float**. |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. نوشت [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مختصات x/y را برای شروع انیمیشن (به درصد) مشخص می‌کند. نوشت [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) | مشخص می‌کند مبدا مسیر حرکت نسبت به چه چیزی است، مانند طرح اسلاید یا والد. نوشت [MotionOriginType](../motionorigintype/). |
| virtual void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) | ابتدا مسیر را به همراه مختصات برای حرکت انیمیشن مشخص می‌کند. نوشت [IMotionPath](../imotionpath/). |
| virtual void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) | نحوه حرکت مسیر حرکت هنگام جابجایی شکل را مشخص می‌کند. نوشت [MotionPathEditMode](../motionpatheditmode/). |
| virtual void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مرکز چرخش استفاده‌شده برای چرخاندن مسیر حرکت به زاویه X را توصیف می‌کند. نوشت [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | خواص زمان‌بندی رفتار اثر را نمایان می‌کند. نوشت [ITiming](../itiming/). |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | موقعیت هدف برای اثر حرکت انیمیشن (به درصد) را مشخص می‌کند. نوشت [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | تعداد مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمندپوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تعداد مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمندپوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | کنستراکت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی از بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | تعداد مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمندپوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تعداد مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از هوشمندپوینترها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBehavior](../ibehavior/)
* فضای‌نام [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)