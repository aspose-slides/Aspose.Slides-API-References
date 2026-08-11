---
title: ISmartArtShape
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک شکل در داخل نمودار SmartArt
type: docs
weight: 40
url: /fa/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape کلاس


Represents a shape inside [SmartArt](../smartart/) diagram

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | در صورتی که Placeholder وجود نداشته باشد، یک Placeholder جدید اضافه می‌کند و ویژگی‌های Placeholder را به مقدار مشخص‌شده تنظیم می‌نماید. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | آرایه‌ای از عناصر شکل را ایجاد و برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را در سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را در سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌علولی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌علولی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | مقدار تنظیمات یک شکل را در شاخص مشخص‌شده برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | مجموعه‌ای از مقادیر تنظیمات شکل را برمی‌گرداند. فقط-خواندنی [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. خواندن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | شیء [EffectFormat](../../aspose.slides/effectformat/) را که شامل افکت‌های پیکسلی اعمال‌شده به یک شکل است برمی‌گرداند. فقط-خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | شیء [FillFormat](../../aspose.slides/fillformat/) را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. فقط-خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | ویژگی‌های فریم شکل را برمی‌گرداند. خواندن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | مشخص می‌کند آیا شکل مخفی است یا خیر. خواندن **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواندن [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندهای ابرمتنی. فقط-خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس بر روی را برمی‌گرداند. خواندن [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | گزینه‌ی 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | مشخص می‌کند آیا شکل TextHolder است یا خیر. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | شیء [LineFormat](../../aspose.slides/lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | نام یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | شناسهٔ یکتای محدوده‌اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای بین‌پروگرامی اجازه می‌دهد به‌طور قابل‌اعتمادی از هر نقطه‌ای در سند به شکل ارجاع دهند را برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین به [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) مراجعه کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | در صورتی که شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../../aspose.slides/groupshape/) را برمی‌گرداند. در غیر این‌صورت مقدار null برمی‌گرداند. فقط-خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Placeholder مربوط به یک شکل را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | ویژگی‌های فریم خام شکل را برمی‌گرداند. خواندن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | تعداد درجاتی که شکل مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند. مقدار مثبت نشان‌دهندهٔ چرخش ساعتگرد؛ مقدار منفی نشان‌دهندهٔ چرخش پاد ساعتگرد است. خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | شیء سبک شکل را برمی‌گرداند. فقط-خواندنی [IShapeStyle](../../aspose.slides/ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | نوع پیش‌تنظیم هندسه را برمی‌گرداند. توجه: هنگام تغییر مقدار، تمام مقادیر تنظیم مجدداً به مقادیر پیش‌فرضشان بازنشانی می‌شوند. خواندن [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | متن شکل [SmartArt](../smartart/) را برمی‌گرداند. فقط-خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | شیء [ThreeDFormat](../../aspose.slides/threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | شناسهٔ داخلی محدودهٔ ارائه‌ای که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، را برمی‌گرداند. از آنجایی که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین به [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) مراجعه کنید. |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، دریافت می‌کند. خواندن **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | یک شکل Placeholder پایه (شکلی از چیدمان و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | نسخه‌ای از مسیر شکل هندسی را برمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل هستند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع حدود تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با استفاده از عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از نظر مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌های اشتراک‌گذاری‌شده را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | تعریف می‌کند که این شکل Placeholder نیست. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. نوشتن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | مشخص می‌کند آیا شکل مخفی است یا خیر. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند ابرمتنی تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند ابرمتنی تعریف‌شده برای حرکت ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | گزینهٔ 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | تعداد درجاتی که شکل مشخص‌شده حول محور z چرخانده می‌شود را تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعتگرد؛ مقدار منفی نشان‌دهندهٔ چرخش پاد ساعتگرد است. نوشتن **float**. |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | نوع پیش‌تنظیم هندسه را تنظیم می‌کند. توجه: هنگام تغییر مقدار، تمام مقادیر تنظیم به مقادیر پیش‌فرضشان بازنشانی می‌شوند. نوشتن [Slides::ShapeType](../../aspose.slides/shapetype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | هندسه شکل را از شیء [IGeometryPath](../../aspose.slides/igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([ShapeType](../../aspose.slides/shapetype/)) را به [ShapeType::Custom](../../aspose.slides/shapetype/) تغییر می‌دهد. |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | هندسه شکل را از آرایه‌ای از [IGeometryPath](../../aspose.slides/igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشند. نوع شکل ([ShapeType](../../aspose.slides/shapetype/)) را به [ShapeType::Custom](../../aspose.slides/shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n-ام الگو را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراک‌گذاری‌شده را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با استفاده از عبارت lock() در C# را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |
## موارد مرتبط

* کلاس [IGeometryShape](../../aspose.slides/igeometryshape/)
* فضای‌نام [Aspose::Slides::SmartArt](../)
* کتابخانه [Aspose.Slides](../../)