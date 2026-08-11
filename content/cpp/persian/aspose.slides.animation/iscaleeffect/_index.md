---
title: IScaleEffect
second_title: مرجع API Aspose.Slides برای C++
description: نمایان‌گر اثر مقیاس انیمیشن است.
type: docs
weight: 365
url: /fa/aspose.slides.animation/iscaleeffect/
---
## IScaleEffect کلاس

نمایان‌گر اثر مقیاس انیمیشن است.

```cpp
class IScaleEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند به‌طوری که دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | نمایان‌گر این است که آیا رفتارهای انیمیشن انباشته می‌شوند یا خیر. [NullableBool](../../aspose.slides/nullablebool/) را بخوانید. |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | نمایان‌گر این است که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. [BehaviorAdditiveType](../behavioradditivetype/) را بخوانید. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بخوانید. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | مختصات x/y برای شروع انیمیشن (به درصد) را تعیین می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | نمایان‌گر ویژگی‌های رفتار است. فقط-خواندنی [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | ویژگی‌های زمان‌بندی برای رفتار اثر را نمایش می‌دهد. [ITiming](../itiming/) را بخوانید. |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | مکان هدف برای اثر مقیاس انیمیشن (به درصد) را تعیین می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بخوانید. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ZoomContent](./get_zoomcontent/)() | تعیین می‌کند که آیا محتوا باید بزرگ‌نمایی شود یا خیر. [NullableBool](../../aspose.slides/nullablebool/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مأمور [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان cloning انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | نمایان‌گر این است که آیا رفتارهای انیمیشن انباشته می‌شوند یا خیر. [NullableBool](../../aspose.slides/nullablebool/) را بنویسید. |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | نمایان‌گر این است که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. [BehaviorAdditiveType](../behavioradditivetype/) را بنویسید. |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مقدار جابجایی نسبی برای انیمیشن (به درصد) را توصیف می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بنویسید. |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مختصات x/y برای شروع انیمیشن (به درصد) را تعیین می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بنویسید. |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | ویژگی‌های زمان‌بندی برای رفتار اثر را نمایش می‌دهد. [ITiming](../itiming/) را بنویسید. |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | مکان هدف برای اثر مقیاس انیمیشن (به درصد) را تعیین می‌کند. [System::Drawing::PointF](../../system.drawing/pointf/) را بنویسید. |
| virtual void [set_ZoomContent](./set_zoomcontent/)([NullableBool](../../aspose.slides/nullablebool/)) | تعیین می‌کند که آیا محتوا باید بزرگ‌نمایی شود یا خیر. [NullableBool](../../aspose.slides/nullablebool/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مأمور [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [IBehavior](../ibehavior/)
* نام‌فضا [Aspose::Slides::Animation](../)
* کتابخانه [Aspose.Slides](../../)