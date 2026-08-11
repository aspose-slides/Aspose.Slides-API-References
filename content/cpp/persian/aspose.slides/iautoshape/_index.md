---
title: IAutoShape
second_title: مرجع API Aspose.Slides برای C++
description: نمایان‌گر یک AutoShape است.
type: docs
weight: 1366
url: /fa/aspose.slides/iautoshape/
---
## IAutoShape کلاس

نمایان‌گر [AutoShape](../autoshape/) است.

```cpp
class IAutoShape : public virtual Aspose::Slides::IGeometryShape
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر نگهدارنده‌ای وجود نداشته باشد، یک نگهدارنده جدید اضافه می‌کند و ویژگی‌های نگهدارنده را به مقدار مشخص تنظیم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) | یک [TextFrame](../textframe/) جدید به شکل اضافه می‌کند. اگر شکل از پیش [TextFrame](../textframe/) داشته باشد، فقط متن آن را تغییر می‌دهد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور-نقطه به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور-نقطه به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | مقدار تنظیمات شکل را در اندیس مشخص شده برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با شکل را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با شکل را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() | قفل‌های [AutoShape](../autoshape/) را برمی‌گرداند. فقط-خواندنی [IAutoShapeLock](../iautoshapelock/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | ویژگی تعیین می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. فقط-خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) که شامل افکت‌های پیکسلی اعمال‌شده به شکل است را برمی‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) که شامل ویژگی‌های قالب‌بندی پر کردن برای شکل است را برمی‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ویژگی‌های فریم شکل را برمی‌گرداند. فقط-خواندنی [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گیرد. فقط-خواندنی **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | مشخص می‌کند آیا شکل پنهان است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | هایپرلینک تعریف‌شده برای کلیک موش را برمی‌گرداند. فقط-خواندنی [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر هایپرلینک‌ها فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | هایپرلینک تعریف‌شده برای عبور موش را برمی‌گرداند. فقط-خواندنی [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه 'Mark as decorative' را می‌گیرد. خواندنی/نوشتنی **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextBox](./get_istextbox/)() | مشخص می‌کند آیا شکل یک جعبه متن است. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | مشخص می‌کند آیا شکل TextHolder است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) که شامل ویژگی‌های قالب‌بندی خطوط برای شکل است را برمی‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | یک شناسه منحصر به فرد در محدوده اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای بینابینی امکان ارجاع قابل اطمینان به شکل را از هر نقطه‌ای از سند می‌دهد، برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | نگهدارنده برای یک شکل را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ویژگی‌های فریم شکل خام را برمی‌گرداند. فقط-خواندنی [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخانده شده است را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | نوع پیش‌تنظیم هندسی را برمی‌گرداند. نکته: با تغییر مقدار، تمام مقادیر تنظیم مجدد به مقادیر پیش‌فرض خواهند شد. فقط-خواندنی [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | شیء [TextFrame](../textframe/) برای [AutoShape](../autoshape/) را برمی‌گرداند. فقط-خواندنی [ITextFrame](../itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) که شامل ویژگی‌های قالب‌بندی خطوط برای شکل است را برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | یک شناسه داخلی، در محدوده ارائه، که برای استفاده توسط افزودنی‌ها یا کدهای دیگر هدف‌گذاری شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید منحصربه‌فرد پایدار در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() | مشخص می‌کند آیا این شکل خودکار باید با پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شدن مشخص شود. فقط-خواندنی **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گیرد. فقط-خواندنی **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گیرد. فقط-خواندنی **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود برمی‌گیرد. فقط-خواندنی **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت‌ترین موقعیت z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی‌ترین موقعیت برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل نگهدارندهٔ پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گیرد. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | کپی مسیر شکل هندسی را برمی‌گرداند. مختصات‌ها نسبت به گوشهٔ بالا-چپ شکل هستند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع حد‌قالب تصویر بندانگشتی [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان lock() در C#. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را اولیه‌سازی می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را اولیه‌سازی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را اولیه‌سازی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را با مقدار مشخصی کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل یک نگهدارنده نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | ویژگی تعیین می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | مشخص می‌کند آیا شکل مخفی است یا نه. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | هایپرلینک تعریف‌شده برای کلیک موش را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | هایپرلینک تعریف‌شده برای عبور موش را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | تنظیم گزینه 'Mark as decorative'. خواندنی/نوشتنی **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخانده شده است را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. نوشتن **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | نوع پیش‌تنظیم هندسی را تنظیم می‌کند. نکته: با تغییر مقدار، تمام مقادیر تنظیم مجدد به مقادیر پیش‌فرض خواهند شد. نوشتن [Slides::ShapeType](../shapetype/). |
| virtual void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) | مشخص می‌کند آیا این شکل خودکار باید با پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شدن مشخص شود. نوشتن **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | هندسهٔ شکل را از شیء [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) به [ShapeType::Custom](../shapetype/) تغییر می‌کند. |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | هندسهٔ شکل را از آرایهٔ [IGeometryPath](../igeometrypath/) به‌روزرسانی می‌کند. مختصات‌ها باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([ShapeType](../shapetype/)) به [ShapeType::Custom](../shapetype/) تغییر می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگوئی n-ام را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف فراهم می‌شود. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بیان lock() در C# برای آزادسازی قفل. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IGeometryShape](../igeometryshape/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)