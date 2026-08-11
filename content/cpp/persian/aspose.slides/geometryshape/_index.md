---
title: GeometryShape
second_title: Aspose.Slides برای مرجع API C++
description: نمایش‌گر کلاس پایه برای تمام شکل‌های هندسی است.
type: docs
weight: 1080
url: /fa/aspose.slides/geometryshape/
---
## GeometryShape کلاس

نمایش‌گر کلاس پایه برای تمام شکل‌های هندسی است.

```cpp
class GeometryShape : public Aspose::Slides::Shape,
                      public virtual Aspose::Slides::IGeometryShape
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و خصوصیات placeholder را به مقدار مشخص‌شده تنظیم می‌نماید. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() override | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه عددی شناور به‌سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عددی شناور به‌سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای موارد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) override | مقدار تنظیمات شکل را در اندیس مشخص‌شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() override | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه‌سفید رندر شود. خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسل اعمال‌شده بر شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌هایی که خاصیت اثر ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شیء [FillFormat](../fillformat/) را که شامل خصوصیات قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌هایی که خاصیت پر کردن ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | خصوصیات فریم شکل را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوند (hyperlink) تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوند تعریف‌شده برای حرکت ماوس بر روی آن را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیء [LineFormat](../lineformat/) را که شامل خصوصیات قالب‌بندی خط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌هایی که خاصیت خط ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید مقدار null نباشد. در صورت نیاز از رشته خالی استفاده کنید. خواندنی [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسهٔ یکتای محدودهٔ اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای میان‌فوری اجازه می‌دهد شکل را از هر نقطه‌ای در سند به‌صورت قابل‌اعتماد ارجاع دهد، برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | placeholder شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد مقدار null برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائهٔ والد اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | خصوصیات فریم شکل خام را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() override | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | نوع پیش‌تنظیم ژئومتری را برمی‌گرداند. نکته: در صورت تغییر مقدار، تمام مقادیر تنظیم مجدد به مقادیر پیش‌فرض خود بازنویسی می‌شوند. خواندنی [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را که شامل خصوصیات اثر 3-بعدی برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌هایی که خاصیت 3-بعدی ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسهٔ داخلی محدودهٔ ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً تخصیص داده شود، نباید به‌عنوان کلید یکتای ثابت در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالای-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالای-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشت‌ترین در ترتیب z را می‌دهد و Shapes[Shapes.Count - 1] شکل جلوی‌ترین را می‌دهد. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید مادر که شکل جاری از آن ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گیرد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() override | کپی مسیر شکل ژئومتریک را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالای-چپ شکل هستند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر بندانگشتی شکل را برمی‌گرداند. نوع [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) برای محدودهٔ تصویر بندانگشتی به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | حدود بصری شکل که از محتوای رندرش محاسبه می‌شود را برمی‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. مشابه عملگر C# `is`. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان `lock()` در C# را فراهم می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ نسخهٔ کپی. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل placeholder نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه‌سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | خصوصیات فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | تعیین می‌کند که آیا شکل مخفی است یا نه. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای حرکت ماوس بر روی آن را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. باید مقدار null نباشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | خصوصیات فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. نوشتن **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | نوع پیش‌تنظیم ژئومتری را تنظیم می‌کند. نکته: در صورت تغییر مقدار، تمام مقادیر تنظیم مجدد به مقادیر پیش‌فرض خود بازنویسی می‌شوند. نوشتن [Slides::ShapeType](../shapetype/). |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالای-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالای-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | هندسهٔ شکل را از شیء [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالای-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) به [ShapeType::Custom](../shapetype/) تغییر می‌کند. |
| void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | هندسهٔ شکل را از آرایه‌ای از [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالای-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) به [ShapeType::Custom](../shapetype/) تغییر می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C# را فراهم می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل بیان `lock()` در C# را فراهم می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتوی [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتوی [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Shape](../shape/)
* کلاس [IGeometryShape](../igeometryshape/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)