---
title: Region
second_title: Aspose.Slides برای مرجع API C++
description: "نمایانگر داخلی یک شکل گرافیکی است. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای تأیید می‌شود. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 261
url: /fa/system.drawing/region/
---
## کلاس Region

نمایانگر داخلی یک شکل گرافیکی است. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، چون منجر به خطاهای زمان اجرا و/یا خطاهای تأیید می‌شود. همواره این کلاس را در یک نشانگر [System::SmartPtr](../../system/smartptr/) بپیچید و از این نشانگر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class Region : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | یک نسخهٔ کپی از شیء جاری را برمی‌گرداند. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | منطقهٔ نمایانگر شیء جاری را با بخشی از منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود و با این منطقه تقاطع ندارد، جایگزین می‌کند. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | منطقهٔ نمایانگر شیء جاری را با بخشی از منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود و با این منطقه تقاطع ندارد، جایگزین می‌کند. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | منطقهٔ نمایانگر شیء جاری را با بخشی از منطقه‌ای که توسط مسیر مشخص‌شده تعریف می‌شود و با این منطقه تقاطع ندارد، جایگزین می‌کند. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | منطقهٔ نمایانگر شیء جاری را با بخشی از منطقهٔ مشخص‌شده که با این منطقه تقاطع ندارد، جایگزین می‌کند. |
| void [Dispose](./dispose/)() | تمام منابع سیستم‌عامل که توسط شیء جاری به‌دست آمده‌اند را آزاد می‌کند. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | تعیین می‌کند آیا منطقهٔ مشخص‌شده با منطقهٔ نمایانگر شیء جاری روی سطح رسم مشخص یکسان است. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ اعداد شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند مطابق IEC 60559:1989 NaN با هیچ مقدار، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ اعداد شناور دوگانه به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند مطابق IEC 60559:1989 NaN با هیچ مقدار، از جمله NaN، برابر نیست. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ حذف منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ حذف منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ حذف منطقه‌ای که توسط مسیر مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ حذف منطقهٔ مشخص‌شده از آن، جایگزین می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | ساختار [RectangleF](../rectanglef/)‌ای را برمی‌گرداند که مستطیلی را نشان می‌دهد که این [Region](./) را بر روی سطح رسم یک شیء [Graphics](../graphics/) محاصره می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | یک شیء RegionData را برمی‌گرداند که شامل داده‌هایی است که منطقهٔ نمایانگر شیء جاری را تعریف می‌کند. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | یک آرایهٔ از ساختارهای [RectangleF](../rectanglef/) را برمی‌گرداند که این [Region](./) را پس از اعمال تبدیل ماتریسی مشخص‌شده تقریب می‌زنند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ تقاطع این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ تقاطع این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ تقاطع این منطقه و منطقه‌ای که توسط مسیر مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ تقاطع این منطقه و منطقهٔ مشخص‌شده، جایگزین می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | تعیین می‌کند آیا منطقهٔ نمایانگر شیء جاری دارای داخلی خالی بر روی سطح رسم مشخص‌شده است. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | تعیین می‌کند آیا منطقهٔ نمایانگر شیء جاری دارای داخلی نامحدود بر روی سطح رسم مشخص‌شده است. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | تعیین می‌کند آیا هر بخشی از مستطیل مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | تعیین می‌کند آیا هر بخشی از مستطیل مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده با استفاده از گرافیک‌های مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده با استفاده از گرافیک‌های مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | تعیین می‌کند آیا هر بخشی از مستطیل مشخص‌شده با استفاده از گرافیک‌های مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | تعیین می‌کند آیا هر بخشی از مستطیل مشخص‌شده با استفاده از گرافیک‌های مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | تعیین می‌کند آیا نقطهٔ مشخص‌شده با استفاده از گرافیک‌های مشخص‌شده در داخل منطقهٔ نمایانگر شیء جاری قرار دارد. |
| void [Lock](../../system/object/lock/)() | قفل کردن مطابق عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [MakeEmpty](./makeempty/)() | شیء جاری را به داخلی خالی مقداردهی اولیه می‌کند. |
| void [MakeInfinite](./makeinfinite/)() | این شیء منطقه را به داخلی نامحدود مقداردهی اولیه می‌کند. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ رونوشت. در واقع هیچ‌چیز را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان رونوشت‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیز را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان رونوشت‌سازی زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
|  [Region](./region/)() | نمونهٔ جدیدی از کلاس [Region](./) را می‌سازد. |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | نمونهٔ جدیدی از کلاس [Region](./) که منطقه‌ای تعریف‌شده توسط مستطیل مشخص‌شده را نمایان می‌کند، می‌سازد. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | نمونهٔ جدیدی از کلاس [Region](./) که منطقه‌ای تعریف‌شده توسط مستطیل مشخص‌شده را نمایان می‌کند، می‌سازد. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | نمونهٔ جدیدی از کلاس [Region](./) که منطقه‌ای تعریف‌شده توسط مسیر مشخص‌شده را نمایان می‌کند، می‌سازد. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | نمونهٔ جدیدی از کلاس [Region](./) که منطقه‌ای تعریف‌شده توسط شیء RegionData مشخص‌شده را نمایان می‌کند، می‌سازد. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به اندازه مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک نشانگر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر نشانگرها در کنتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | این منطقه را با ماتریس مشخص‌شده تبدیل می‌کند. |
| void [Transform](./transform/)(const SkMatrix\&) | این منطقه را با ماتریس مشخص‌شده تبدیل می‌کند. |
| void [Translate](./translate/)(int, int) | مختصات منطقه را به مقدار مشخص‌شده حرکت می‌دهد. |
| void [Translate](./translate/)(**float**, **float**) | مختصات منطقه را به مقدار مشخص‌شده حرکت می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ عملیات اتحاد این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ عملیات اتحاد این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ اتحاد این منطقه و منطقه‌ای که توسط مسیر مشخص‌شده تعریف می‌شود، جایگزین می‌کند. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | منطقهٔ نمایانگر شیء جاری را با نتیجهٔ اتحاد این منطقه و منطقهٔ مشخص‌شده، جایگزین می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گیری مطابق عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | منطقهٔ نمایانگر شیء جاری را با بخش‌های این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود و تقاطع ندارند، جایگزین می‌کند. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | منطقهٔ نمایانگر شیء جاری را با بخش‌های این منطقه و منطقه‌ای که توسط مستطیل مشخص‌شده تعریف می‌شود و تقاطع ندارند، جایگزین می‌کند. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | منطقهٔ نمایانگر شیء جاری را با بخش‌های این منطقه و منطقه‌ای که توسط مسیر مشخص‌شده تعریف می‌شود و تقاطع ندارند، جایگزین می‌کند. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | منطقهٔ نمایانگر شیء جاری را با بخش‌های این منطقه و منطقهٔ مشخص‌شده که تقاطع ندارند، جایگزین می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
| virtual  [~Region](./~region/)() | تخریب‌کننده. |
## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)