---
title: PictureFrame
second_title: مرجع API Aspose.Slides برای C++
description: یک فریم حاوی تصویر را نشان می‌دهد.
type: docs
weight: 4733
url: /fa/aspose.slides/pictureframe/
---
## PictureFrame کلاس

یک فریم حاوی تصویر را نمایان می‌کند.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | اگر placeholder جدیدی وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | یک آرایه از عناصر شکل ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور دوگانه به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | مقدار تنظیمات شکل را در ایندکس مشخص شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | خاصیت مشخص می‌کند شکل چگونه در حالت نمایش سیاه‌سفید رندر شود. خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسلی اعمال‌شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند می‌تواند null برگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر کردن ندارند می‌تواند null برگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت می‌کند. خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | اینکه آیا شکل مخفی است را تعیین می‌کند. خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوند تعریف‌شده برای کلیک موس را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوند را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوند تعریف‌شده برای حرکت موس روی آن را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](./get_iscameo/)() | تعیین می‌کند آیا [PictureFrame](./) شیء Cameo است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند آیا شکل گروه‌بندی شده است. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند آیا شکل TextHolder_PPT است. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند می‌تواند null برگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید تهی (null) نباشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. خواندنی [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسه یکتا مختص اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل از هر نقطه‌ای در سند را می‌دهد، برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | شیء والد [GroupShape](../groupshape/) را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | شیء [PictureFillFormat](../picturefillformat/) را برای یک فریم تصویر برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | placeholder برای یک شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد null برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائه والد یک اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های فریم شکل خام را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | مقیاس ارتفاع (نسبت به اندازه اصلی تصویر) فریم تصویر را برمی‌گرداند. مقدار 1.0 معادل 100٪ است. خواندنی **float**. |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | مقیاس عرض (نسبت به اندازه اصلی تصویر) فریم تصویر را برمی‌گرداند. مقدار 1.0 معادل 100٪ است. خواندنی **float**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌گردش شکل مشخص‌شده حول محور z را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های اثر 3-بعدی برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3-بعدی ندارند می‌تواند null برگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسه داخلی مختص ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتای دائم در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود، دریافت می‌کند. خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالا-چپ شکل، بر حسب نقاط، دریافت می‌کند. خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالا-چپ شکل، بر حسب نقاط، دریافت می‌کند. خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در عقب‌ترین موقعیت z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی‌ترین موقعیت z را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | یک کپی از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل هستند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر بندانگشتی شکل را برمی‌گرداند. نوع مرزهای تصویر بندانگشتی [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | مرزهای بصری شکل را که از محتوای رندرش محاسبه می‌شود دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نشان‌دهندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل placeholder نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | خاصیت مشخص می‌کند شکل چگونه در حالت نمایش سیاه‌سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | اینکه آیا شکل مخفی است را تعیین می‌کند. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای کلیک موس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای حرکت موس روی آن را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشته خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | مقیاس ارتفاع (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. نوشتن **float**. |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | مقیاس عرض (نسبت به اندازهٔ اصلی تصویر) فریم تصویر را تنظیم می‌کند. مقدار 1.0 معادل 100٪ است. نوشتن **float**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. نوشتن **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | هندسه شکل را از شیء [IGeometryPath](../igeometrypath/) به‌روز می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | هندسه شکل را از آرایه‌ای از [IGeometryPath](../igeometrypath/) به‌روز می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([ShapeType](../shapetype/)) را به [ShapeType::Custom](../shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی دستور C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتوای [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتوای [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

مثال‌های زیر نشان می‌دهند چگونه تصویر پیش‌نمایش فریم [Audio](../audio/) را تغییر دهید.
```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Adds an audio frame to the slide with a specified position and size.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// Adds an image to presentation resources.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// Sets the image for the audio frame.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//Saves the modified presentation to disk
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* کلاس [GeometryShape](../geometryshape/)
* کلاس [IPictureFrame](../ipictureframe/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)