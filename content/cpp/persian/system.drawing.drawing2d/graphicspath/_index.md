---
title: GraphicsPath
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش‌دهندهٔ مجموعه‌ای از خطوط و منحنی‌های متصل است. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 66
url: /fa/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath کلاس

یک مجموعه از خطوط و منحنی‌های متصل را نمایش می‌دهد. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class GraphicsPath : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | قوس بیضوی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | قوس بیضوی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | قوس بیضوی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | قوس بیضوی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | منحنی کیوبیک بیزیئر مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | منحنی کیوبیک بیزیئر مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | منحنی کیوبیک بیزیئر مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | منحنی کیوبیک بیزیئر مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | دنباله‌ای از منحنی‌های کیوبیک بیزیئر متصل را به شکل جاری اضافه می‌کند. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | دنباله‌ای از منحنی‌های کیوبیک بیزیئر متصل را به شکل جاری اضافه می‌کند. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | منحنی بستهٔ مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | منحنی بستهٔ مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | منحنی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | منحنی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | منحنی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | منحنی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | بیضی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | بیضی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | بیضی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | بیضی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | خط مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | خط مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLine](./addline/)(int, int, int, int) | خط مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | خط مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | سری‌ای از بخش‌های خطی متصل را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | سری‌ای از بخش‌های خطی متصل را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | مسیر مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | خط‌مرزی شکل پای مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | خط‌مرزی شکل پای مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | خط‌مرزی شکل پای مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | چندضلعی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | چندضلعی مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | مستطیل مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | مستطیل مشخص‌شده را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | سری‌ای از مستطیل‌ها را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | سری‌ای از مستطیل‌ها را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | رشته‌ای از متن را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | رشته‌ای از متن را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | رشته‌ای از متن را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | رشته‌ای از متن را به مسیری که توسط شیء فعلی نمایان شده اضافه می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | یک کپی از شیء فعلی ایجاد می‌کند. |
| void [CloseAllFigures](./closeallfigures/)() | تمام اشکال باز را می‌بندد و یک شکل جدید آغاز می‌کند. |
| void [CloseFigure](./closefigure/)() | شکل فعلی را می‌بندد و یک شکل جدید آغاز می‌کند. |
| void [Dispose](./dispose/)() | تمام منابع سیستم‌عامل که توسط شیء فعلی به دست آمده‌اند را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flatten](./flatten/)() | هر منحنی در مسیر را با تبدیل به یک سری خطوط متصل صاف می‌کند. مقدار صاف‌سازی ۰٫۲۵ استفاده می‌شود. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | هر منحنی در مسیر را با تبدیل به یک سری خطوط متصل صاف می‌کند. مقدار صاف‌سازی ۰٫۲۵ استفاده می‌شود. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | هر منحنی در مسیر را با تبدیل به یک سری خطوط متصل صاف می‌کند. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | حالت پر کردن شیء فعلی را برمی‌گرداند. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | یک شیء [PathData](../pathdata/) شامل نقاطی که مسیر شیء فعلی را تشکیل می‌دهند و انواع آن‌ها را برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | آرایه‌ای شامل نقاطی که مسیر شیء فعلی را تشکیل می‌دهند برمی‌گرداند. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | آرایه‌ای شامل مقادیری که انواع نقاط مسیر شیء فعلی را نشان می‌دهند برمی‌گرداند. |
| int [get_PointCount](./get_pointcount/)() const | تعداد نقاط مسیر شیء فعلی را برمی‌گرداند. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | شیء [RectangleF](../../system.drawing/rectanglef/) را که مستطیلی را نشان می‌دهد که مسیر شیء فعلی را هنگام تبدیل با ماتریس مشخص‌شده محصور می‌کند، برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | مقداری را برمی‌گرداند که ترکیبی بیتی از مقادیر Detail::FigureType است و نشان‌دهنده انواع اشکال موجود در مسیر شیء فعلی می‌باشد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | شیء [PointF](../../system.drawing/pointf/) را که نقطه آخر مسیر را نمایش می‌دهد برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | نمونه جدیدی از کلاس [GraphicsPath](./) با حالت پر کردن مشخص‌ شده می‌سازد. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | نمونه جدیدی از شیء [GraphicsPath](./) که مسیر مشخص‌شده را نشان می‌دهد می‌سازد. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | نمونه جدیدی از شیء [GraphicsPath](./) که مسیر مشخص‌شده را نشان می‌دهد می‌سازد. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | نشان می‌دهد که آیا نقطه مشخص‌شده درون (زیر) محدودهٔ این [GraphicsPath](./) هنگام ترسیم با [Pen](../../system.drawing/pen/) مشخص‌شده قرار دارد. پیاده‌سازی نشده. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | تعیین می‌کند که آیا نقطهٔ مشخص‌شده درون مسیری که توسط شیء فعلی نمایان شده قرار دارد. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | تعیین می‌کند که آیا نقطهٔ مشخص‌شده درون مسیری که توسط شیء فعلی نمایان شده قرار دارد. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیردست‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیردست‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مرجع‌مقایسه‌ی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای موارد رشته‌ای. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع به اشتراک‌گذاری‌شده را به مقدار مشخص‌ شده کاهش می‌دهد. |
| void [Reset](./reset/)() | مسیر را خالی می‌کند با حذف تمام نقاط. |
| void [Reverse](./reverse/)() | ترتیب نقاط در آرایهٔ PathPoints این [GraphicsPath](./) را برعکس می‌کند. |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | حالت پر کردن شیء فعلی را تنظیم می‌کند. |
| void [SetMarkers](./setmarkers/)() | پیاده‌سازی نشده. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع به اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع به اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع به اشتراک‌گذاری‌شده را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [StartFigure](./startfigure/)() | یک شکل جدید را آغاز می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | مسیر شیء فعلی را با اعمال ماتریس تبدیل مشخص‌شده به آن، تغییر شکل می‌دهد. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | این مسیر را با یک خط‌مرزی دور مسیر اصلی جایگزین می‌کند. |
|  [~GraphicsPath](./~graphicspath/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Drawing::Drawing2D](../)
* کتابخانه [Aspose.Slides](../../)