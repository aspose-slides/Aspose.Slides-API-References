---
title: Pen
second_title: Aspose.Slides برای C++ API Reference
description: "ویژگی‌هایی مانند رنگ، عرض و غیره خطوط و منحنی‌های در حال رسم را نشان می‌دهد. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 183
url: /fa/system.drawing/pen/
---
## Pen کلاس

نمایش ویژگی‌هایی مانند رنگ، عرض و غیره برای خطوط و منحنی‌های رسم‌شده. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class Pen : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Pen](./)\> [Clone](./clone/)() | یک کپی از شیء فعلی را برمی‌گرداند. |
| void [Dispose](./dispose/)() | تمام منابع عملیاتی به‌دست آمده توسط شیء فعلی را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به-شیوه C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به-شیوه C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/) [get_Alignment](./get_alignment/)() const | مقداری را برمی‌گرداند که ترازبندی شیء [Pen](./) فعلی را نشان می‌دهد. |
| [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\> [get_Brush](./get_brush/)() | شیء [Brush](../brush/) این قلم را برمی‌گرداند. |
| [Color](../color/) [get_Color](./get_color/)() const | رنگ این قلم را برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CompoundArray](./get_compoundarray/)() const | آرایه‌ای از مقادیر که قلم ترکیبی را مشخص می‌کند برمی‌گرداند. |
| [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/) [get_DashCap](./get_dashcap/)() const | مقداری را برمی‌گرداند که نشان‌دهنده سر انتهای خط نقاط چین در هر دو طرف است. |
| **float** [get_DashOffset](./get_dashoffset/)() const | فاصله از آغاز خط تا شروع الگوی نقطه چین را برمی‌گرداند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_DashPattern](./get_dashpattern/)() const | آرایه‌ای که الگوی دلخواه نقطه چین را در یک خط نقطه چین نشان می‌دهد برمی‌گرداند. |
| [Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/) [get_DashStyle](./get_dashstyle/)() const | مقداری را برمی‌گرداند که سبک نقطه چین شیء [Pen](./) فعلی را نشان می‌دهد. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_EndCap](./get_endcap/)() const | مقداری را برمی‌گرداند که سر انتهای خط شیء [Pen](./) فعلی را نشان می‌دهد. |
| [Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/) [get_LineJoin](./get_linejoin/)() const | مقداری را برمی‌گرداند که نشان می‌دهد خطوط رسم‌شده توسط این شیء [Pen](./) چگونه به هم متصل می‌شوند. |
| **float** [get_MiterLimit](./get_miterlimit/)() const | حداکثر ضخامت پیوست در گوشهٔ زاویه‌دار را برمی‌گرداند. |
| [Drawing2D::PenType](../../system.drawing.drawing2d/pentype/) [get_PenType](./get_pentype/)() const | پیاده‌سازی نشده. |
| [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/) [get_StartCap](./get_startcap/)() const | مقداری را برمی‌گرداند که سر ابتدای خط شیء [Pen](./) فعلی را نشان می‌دهد. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | کپی‌ای از شیء Matrix که تبدیل‌های هندسی قلم نمایان توسط شیء فعلی را مشخص می‌کند، برمی‌گرداند. |
| **float** [get_Width](./get_width/)() const | عرض شیء [Pen](./) فعلی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اعلان قفل (lock) در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | ماتریس تبدیل شیء فعلی را در ماتریس مشخص‌شده ضرب می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Pen](./pen/)(const [Color](../color/)\&) | یک شیء جدید [Pen](./) که رنگ مشخص شده را نمایندگی می‌کند، می‌سازد. |
| [Pen](./pen/)(const [Color](../color/)\&, **float**) | یک شیء جدید [Pen](./) که رنگ و عرض مشخص‌شده را نمایندگی می‌کند، می‌سازد. |
| [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | یک شیء جدید [Pen](./) می‌سازد و آن را با شیء [Brush](../brush/) مشخص‌شده مقداردهی می‌کند. |
| [Pen](./pen/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**) | یک شیء جدید [Pen](./) می‌سازد و آن را با شیء [Brush](../brush/) مشخص‌شده مقداردهی می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر پایه مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراک‌گذاری‌شده را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [ResetTransform](./resettransform/)() | ماتریس تبدیل شیء فعلی را بازنشانی می‌کند تا به ماتریس همانی تبدیل شود. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | تحول هندسی محلی را به میزان زاویهٔ مشخص‌شده در ترتیب مشخص‌شده می‌چرخاند. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | تحول هندسی محلی را توسط عوامل مشخص‌شده در ترتیب مشخص‌شده مقیاس می‌دهد. |
| void [set_Alignment](./set_alignment/)([Drawing2D::PenAlignment](../../system.drawing.drawing2d/penalignment/)) | ترازبندی شیء [Pen](./) فعلی را تنظیم می‌کند. |
| void [set_Brush](./set_brush/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&) | شیء [Brush](../brush/) این قلم را تنظیم می‌کند. |
| void [set_Color](./set_color/)(const [Color](../color/)\&) | رنگ این قلم را تنظیم می‌کند. |
| void [set_CompoundArray](./set_compoundarray/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | آرایه‌ای از مقادیر که قلم ترکیبی را مشخص می‌کند، تنظیم می‌کند. |
| void [set_CustomEndCap](./set_customendcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | سر انتهای خط سفارشی را تنظیم می‌کند. |
| void [set_CustomStartCap](./set_customstartcap/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::CustomLineCap](../../system.drawing.drawing2d/customlinecap/)\>\&) | سر ابتدای خط سفارشی را تنظیم می‌کند. |
| void [set_DashCap](./set_dashcap/)([Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | مقداری را تنظیم می‌کند که سر انتهای هر دو طرف خط نقطه چین را مشخص می‌کند. |
| void [set_DashOffset](./set_dashoffset/)(**float**) | فاصلهٔ از آغاز خط تا شروع الگوی نقطه چین را تنظیم می‌کند. |
| void [set_DashPattern](./set_dashpattern/)(const [System::ArrayPtr](../../system/arrayptr/)\<**float**\>\&) | آرایه‌ای را تنظیم می‌کند که الگوی سفارشی نقطه چین را در خط نقطه چین مشخص می‌کند. آرایه شامل اعداد است که طول‌های نقطه‌ها و فواصل متناوب را تعیین می‌کند. |
| void [set_DashStyle](./set_dashstyle/)([Drawing2D::DashStyle](../../system.drawing.drawing2d/dashstyle/)) | مقداری را تنظیم می‌کند که سبک نقطه چین شیء [Pen](./) فعلی را مشخص می‌نماید. |
| void [set_EndCap](./set_endcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | سر انتهای خط شیء [Pen](./) فعلی را تنظیم می‌کند. |
| void [set_LineJoin](./set_linejoin/)([Drawing2D::LineJoin](../../system.drawing.drawing2d/linejoin/)) | مقداری را تنظیم می‌کند که نحوه اتصال خطوط رسم‌شده توسط این شیء [Pen](./) را مشخص می‌کند. |
| void [set_MiterLimit](./set_miterlimit/)(**float**) | حداکثر ضخامت پیوست در گوشهٔ زاویه‌دار را تنظیم می‌کند. |
| void [set_StartCap](./set_startcap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/)) | سر ابتدای خط شیء [Pen](./) فعلی را تنظیم می‌کند. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | یک شیء Matrix که تبدیل‌های هندسی قلم نمایان توسط شیء فعلی را مشخص می‌کند، تنظیم می‌کند. |
| void [set_Width](./set_width/)(**float**) | عرض شیء [Pen](./) فعلی را تنظیم می‌کند. |
| void [SetLineCap](./setlinecap/)([Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::LineCap](../../system.drawing.drawing2d/linecap/), [Drawing2D::DashCap](../../system.drawing.drawing2d/dashcap/)) | پیاده‌سازی نشده. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراک‌گذاری‌شده را افزاش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراک‌گذاری‌شده را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | تحول هندسی محلی را به اندازه‌های مشخص‌شده در ترتیب مشخص‌شده ترجمه می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اعلان بازکردن قفل (lock) در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهدارندهٔ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزاش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)