---
title: Matrix
second_title: "مرجع API Aspose.Slides برای C++"
description: "یک ماتریس 3x3 که عملیات تبدیل را تعریف می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() ایجاد شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 118
url: /fa/system.drawing.drawing2d/matrix/
---
## کلاس Matrix

Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | یک نسخه از شیء جاری ایجاد می‌کند. |
| void [Dispose](./dispose/)() | تمام منابع سیستم‌عامل که توسط شیء جاری به‌دست آمده‌اند را آزاد می‌کند. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | آزمون می‌کند که آیا شیء مشخص شده یک [Matrix](./) است و با این شیء یکسان است. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | آرایه‌ای شامل عناصر ماتریس به ترتیب زیر بر می‌گرداند: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | تشخیص می‌دهد که آیا ماتریس نمایان‌شده توسط شیء جاری یک ماتریس همانی است. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | تشخیص می‌دهد که آیا ماتریس نمایان‌شده توسط شیء جاری قابل معکوس است. |
| **float** [get_OffsetX](./get_offsetx/)() const | مقدار ترجمه X ماتریس نمایان‌شده توسط شیء جاری را بر می‌گرداند. |
| **float** [get_OffsetY](./get_offsety/)() const | مقدار ترجمه Y ماتریس نمایان‌شده توسط شیء جاری را بر می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارشگر مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | ماتریس نمایان‌شده توسط شیء جاری را معکوس می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا زده شود یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| [Matrix](./matrix/)() | یک نمونه جدید از کلاس [Matrix](./) که نمایانگر ماتریس همانی است، می‌سازد. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | یک نمونه جدید از کلاس [Matrix](./) می‌سازد و آن را با مقادیر مشخص‌شده مقداردهی اولیه می‌کند. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | یک نمونه جدید از کلاس [Matrix](./) برای تبدیل هندسی تعریف‌شده توسط مستطیل و آرایه نقاط مشخص‌شده می‌سازد. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | یک نمونه جدید از کلاس [Matrix](./) برای تبدیل هندسی تعریف‌شده توسط مستطیل و آرایه نقاط مشخص‌شده می‌سازد. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | ماتریس نمایان‌شده توسط شیء جاری را در‌نایت با ماتریس مشخص‌شده ضرب می‌کند. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | ماتریس نمایان‌شده توسط شیء جاری را در‌نایت با ماتریس مشخص‌شده ضرب می‌کند. |
| [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌ها با کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌ها با کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه‌ی مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه‌ی مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارشگر مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [Reset](./reset/)() | ماتریس نمایان‌شده توسط شیء جاری را بازنشانی می‌کند تا یک ماتریس همانی شود. |
| void [Rotate](./rotate/)(**float**) | ماتریس نمایان‌شده توسط شیء جاری را به‌صورت ساعت‌گرد با زاویه مشخص‌شده می‌چرخاند. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | ماتریس نمایان‌شده توسط شیء جاری را به‌صورت ساعت‌گرد حول مبدأ با زاویه مشخص‌شده می‌چرخاند. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | ماتریس نمایان‌شده توسط شیء جاری را به‌صورت ساعت‌گرد حول نقطه مشخص‌شده با زاویه مشخص می‌چرخاند. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | ماتریس نمایان‌شده توسط شیء جاری را به‌صورت ساعت‌گرد حول نقطه مشخص‌شده با زاویه مشخص می‌چرخاند. |
| void [Scale](./scale/)(**float**, **float**) | بردار مقیاس مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | بردار مقیاس مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به‌عنوان اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Shear](./shear/)(**float**, **float**) | بردار برش (shear) مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | بردار برش (shear) مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | تبدیل هندسی تعریف‌شده توسط ماتریس نمایان‌شده توسط شیء جاری را بر روی نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | تبدیل هندسی تعریف‌شده توسط ماتریس نمایان‌شده توسط شیء جاری را بر روی نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | تبدیل هندسی تعریف‌شده توسط ماتریس نمایان‌شده توسط شیء جاری را بر روی نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | تبدیل هندسی تعریف‌شده توسط ماتریس نمایان‌شده توسط شیء جاری را بر روی نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | فقط مؤلفه‌های مقیاس و چرخش ماتریس نمایان‌شده توسط شیء جاری را بر نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | فقط مؤلفه‌های مقیاس و چرخش ماتریس نمایان‌شده توسط شیء جاری را بر نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | فقط مؤلفه‌های مقیاس و چرخش ماتریس نمایان‌شده توسط شیء جاری را بر نقاط مشخص‌شده اعمال می‌کند. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | فقط مؤلفه‌های مقیاس و چرخش ماتریس نمایان‌شده توسط شیء جاری را بر نقاط مشخص‌شده اعمال می‌کند. |
| void [Translate](./translate/)(**float**, **float**) | بردار ترجمه (translate) مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | بردار ترجمه (translate) مشخص‌شده را بر روی ماتریس نمایان‌شده توسط شیء جاری اعمال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌کردن بیان lock() در C# را باز می‌کند. به‌صورت مستقیم صدا زده شود یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | هر بردار در آرایه را در‌نایت با ماتریس نمایان‌شده توسط شیء جاری ضرب می‌کند. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | هر بردار در آرایه را در‌نایت با ماتریس نمایان‌شده توسط شیء جاری ضرب می‌کند. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Matrix](./~matrix/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Drawing::Drawing2D](../)
* کتابخانه [Aspose.Slides](../../)