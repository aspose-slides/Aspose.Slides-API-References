---
title: AutoShape
second_title: مرجع API Aspose.Slides برای C++
description: نماینده یک AutoShape.
type: docs
weight: 66
url: /fa/aspose.slides/autoshape/
---
## کلاس AutoShape

نمادی از یک [AutoShape](./).

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | در صورتی که وجود نداشته باشد، یک متغیر نگهدارنده جدید اضافه می‌کند و ویژگی‌های متغیر نگهدارنده را به مورد مشخص شده تنظیم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | یک [TextFrame](../textframe/) جدید به یک شکل اضافه می‌کند. اگر شکل قبلاً [TextFrame](../textframe/) داشته باشد، به سادگی متن آن را تغییر می‌دهد. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عددی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | مقدار تنظیمات یک شکل را در ایندکس مشخص‌شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | قفل‌های خودشکل را برمی‌گرداند. فقط خواندنی [IAutoShapeLock](../iautoshapelock/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. خواندن [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیٔ [EffectFormat](../effectformat/) را برمی‌گرداند که شامل اثرات پیکسلی اعمال‌شده بر شکل است. نکته: برای برخی انواع شکل که ویژگی اثر ندارند می‌تواند مقدار null برگرداند. فقط خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شیٔ [FillFormat](../fillformat/) را برمی‌گرداند که ویژگی‌های قالب‌بندی پرکننده برای یک شکل است. نکته: برای برخی انواع شکل که ویژگی پرکننده ندارند می‌تواند مقدار null برگرداند. فقط خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت می‌کند. خواندن **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | مشخص می‌کند آیا شکل مخفی است یا نه. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوندهای تعریف‌شده برای کلیک موشواره را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوندهای را برمی‌گرداند. فقط خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوند تعریف‌شده برای عبور موشواره را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را با **bool** خواندن/نوشتن دریافت می‌کند. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی **bool**. |
| **bool** [get_IsTextBox](./get_istextbox/)() override | مشخص می‌کند آیا شکل یک جعبه متن است یا نه. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیٔ [LineFormat](../lineformat/) را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: برای برخی انواع شکل که ویژگی خط ندارند می‌تواند مقدار null برگرداند. فقط خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. نباید مقدار null باشد. در صورت نیاز از رشته خالی استفاده کنید. خواندن [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسهٔ یکتا در سطح اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجایی در سند می‌دهد. فقط خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد شیٔ والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | متغیر نگهدارندهٔ یک شکل را برمی‌گرداند. اگر شکل متغیر نگهدارنده نداشته باشد مقدار null برمی‌گرداند. فقط خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | پیشنهاد والد ارائهٔ اسلاید را برمی‌گرداند. فقط خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های خام فریم شکل را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌های چرخش شکل حول محور z را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌عقب، مقدار منفی نشان‌دهنده چرخش ساعت‌پیش است. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | شیٔ سبک شکل را برمی‌گرداند. فقط خواندنی [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | نوع پیش‌تنظیم هندسه را برمی‌گرداند. نکته: با تغییر مقدار، همهٔ مقادیر تنظیمات به مقادیر پیش‌فرض خود باز می‌گردند. خواندن [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | شیٔ [TextFrame](../textframe/) را برای [AutoShape](./) برمی‌گرداند. فقط خواندنی [ITextFrame](../itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیٔ [ThreeDFormat](../threedformat/) را برمی‌گرداند که ویژگی‌های اثر 3D برای یک شکل است. نکته: برای برخی انواع شکل که ویژگی 3D ندارند می‌تواند مقدار null برگرداند. فقط خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسهٔ داخلی در محدوده ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتا دائم در نظر گرفته شود. فقط خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | تعیین می‌کند آیا این خودشکل باید با پس‌زمینه اسلاید پر شود به جای اینکه توسط سبک یا قالب پر شود. خواندن **bool**. |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت می‌کند. خواندن **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت می‌کند. خواندن **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود دریافت می‌کند. خواندن **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت‌ترین موقعیت z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت z را برمی‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل متغیر نگهدارندهٔ پایه را برمی‌گرداند (شکلی از قالب‌بندی و/یا اسلاید اصلی که شکل جاری از آن به ارث برده است). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیٔ را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ چپ-بالا شکل است. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر کوچک شکل را برمی‌گرداند. نوع مرزهای تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌طور پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیٔ را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | حدود بصری شکل را که از محتویات رندر شده محاسبه می‌شود دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیٔ نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیٔ مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء نوع مقدار را با nullptr برحسب مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کم می‌کند. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل متغیر نگهدارنده نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | مشخص می‌کند آیا شکل مخفی باشد. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای کلیک موشواره را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای عبور موشواره را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را با **bool** خواندن/نوشتن تنظیم می‌کند. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های خام فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل حول محور z را تنظیم می‌کند. نوشتن **float**. |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | نوع پیش‌تنظیم هندسه را تنظیم می‌کند. نکته: با تغییر مقدار، همهٔ مقادیر تنظیمات به مقادیر پیش‌فرض باز می‌گردند. نوشتن [Slides::ShapeType](../shapetype/). |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | تعیین می‌کند آیا این خودشکل باید با پس‌زمینه اسلاید پر شود به جای استایل یا قالب پرشدن. نوشتن **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالای چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | هندسه شکل را از شیٔ [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ چپ-بالای شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | هندسه شکل را از آرایهٔ [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ چپ-بالای شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | باز کردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیٔ مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## مراجع مرتبط

* کلاس [GeometryShape](../geometryshape/)
* کلاس [IAutoShape](../iautoshape/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)