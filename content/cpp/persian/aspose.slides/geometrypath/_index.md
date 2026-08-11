---
title: GeometryPath
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر مسیر هندسی GeometryShape
type: docs
weight: 1067
url: /fa/aspose.slides/geometrypath/
---
## کلاس GeometryPath

نمایانگر مسیر هندسی [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## متدها

| متد | توضیح |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | قوس مشخص شده را به مسیر اضافه می‌کند. |
| void [CloseFigure](./closefigure/)() override | شکل فعلی این مسیر را می‌بندد. |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند. |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | منحنی Bezier مکعبی را در انتهای مسیر اضافه می‌کند. |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | منحنی Bezier مکعبی را به مکان مشخص شده در مسیر اضافه می‌کند. |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | منحنی Bezier مکعبی را به مکان مشخص شده در مسیر اضافه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
|  [GeometryPath](./geometrypath/)() | یک نمونه از [GeometryPath](./) ایجاد می‌کند. |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | حالت پر شدن را تنظیم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | مسیر هندسی [GeometryShape](../geometryshape/) را به‌عنوان آرایه‌ای از بخش‌های مسیر برمی‌گرداند. |
| **bool** [get_Stroke](./get_stroke/)() override | ظاهر خط را تنظیم می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارشگر مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیفی توسط targetType است. معادل عملگر C# 'is'. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | خطی را به انتهای مسیر اضافه می‌کند. |
| void [LineTo](./lineto/)(**float**, **float**) override | خطی را به انتهای مسیر اضافه می‌کند. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | خطی را به مکان مشخص شده در مسیر اضافه می‌کند. |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | خطی را به مکان مشخص شده در مسیر اضافه می‌کند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌برداری انواع سفارشی را فراهم می‌کند. |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | موقعیت نقطه بعدی را تنظیم می‌کند. |
| void [MoveTo](./moveto/)(**float**, **float**) override | موقعیت نقطه بعدی را تنظیم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سپارد. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند. |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | منحنی Bezier درجه دوم را در انتهای مسیر اضافه می‌کند. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | منحنی Bezier درجه دوم را به مکان مشخص شده در مسیر اضافه می‌کند. |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | منحنی Bezier درجه دوم را به مکان مشخص شده در مسیر اضافه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| void [RemoveAt](./removeat/)(**int32_t**) override | بخش موردنظر را در ایندکس مشخص‌شده مسیر هندسی حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارشگر مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | حالت پر شدن را تنظیم می‌کند. |
| void [set_Stroke](./set_stroke/)(**bool**) override | ظاهر خط را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به‌صورت اشاره‌گر ضعیف تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارشگر مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارشگر مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارشگر مرجع مشترک را کاهش داده و مقدار آن را بر می‌گرداند. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای قفل‌گذاری بیان lock() در C# را برای باز کردن قفل پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارشگر مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارشگر مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IGeometryPath](../igeometrypath/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)