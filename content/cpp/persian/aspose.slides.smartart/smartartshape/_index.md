---
title: SmartArtShape
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر شکل SmartArt
type: docs
weight: 105
url: /fa/aspose.slides.smartart/smartartshape/
---
## SmartArtShape کلاس

نمایانگر شکل [SmartArt](../smartart/)

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | اگر جای‌دار موجود نباشد، یک جای‌دار جدید اضافه می‌کند و ویژگی‌های جای‌دار را به مورد مشخص تنظیم می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | آرایه‌ای از عناصر شکل را ایجاد و بازمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | مقدار تنظیمات شکل را در اندیس مشخص بازمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | مجموعه‌ای از مقادیر تنظیمات شکل را بازمی‌گرداند. فقط خواندنی [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | متن جایگزین مرتبط با شکل را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با شکل را بازمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | خاصیت مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را بازمی‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | داده‌های سفارشی شکل را بازمی‌گرداند. فقط خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | شیء [EffectFormat](../../aspose.slides/effectformat/) را که شامل افکت‌های پیکسلی اعمال‌شده به شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی افکت ندارند مقدار null برگرداند. فقط خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | شیء [FillFormat](../../aspose.slides/fillformat/) را که شامل ویژگی‌های فرمت پر کردن برای یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند مقدار null برگرداند. فقط خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | ویژگی‌های قاب شکل را بازمی‌گرداند. خواندنی [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | ارتفاع شکل را بر حسب پوینت دریافت می‌کند. خواندنی **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | پیوندی که برای کلیک ماوس تعریف شده است را بازمی‌گرداند. خواندنی [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | مدیر پیوندها را بازمی‌گرداند. فقط خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | پیوندی که برای حرکت ماوس فوق آن تعریف شده است را بازمی‌گرداند. خواندنی [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | گزینه 'علامت‌گذاری به عنوان تزئینی' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | تعیین می‌کند شکل گروه‌بندی شده است یا نه. فقط خواندنی **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | تعیین می‌کند شکل TextHolder_PPT است یا نه. فقط خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | شیء [LineFormat](../../aspose.slides/lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند مقدار null برگرداند. فقط خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | نام یک شکل را بازمی‌گرداند. نباید خالی باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. خواندنی [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | شناسه یکتا محدد به اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع معتبر به شکل از هر نقطه‌ای در سند را می‌دهد، بازمی‌گرداند. فقط خواندنی **uint32_t**. همچنین نگاه کنید به [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../../aspose.slides/groupshape/) را بازمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | جای‌دار یک شکل را بازمی‌گرداند. اگر شکل هیچ جای‌داری نداشته باشد null برمی‌گرداند. فقط خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | ارائه والد یک اسلاید را بازمی‌گرداند. فقط خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | ویژگی‌های خام قاب شکل را بازمی‌گرداند. خواندنی [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | تعداد درجه‌هایی که شکل مشخص حول محور z چرخیده است را بازمی‌گرداند. مقدار مثبت به معنی چرخش ساعت‌گرد، مقدار منفی به معنی چرخش پادساعت‌گرد است. خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | قفل‌های شکل را بازمی‌گرداند. فقط خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | شیء سبک شکل را بازمی‌گرداند. فقط خواندنی [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | نوع پیش‌تنظیم هندسه را بازمی‌گرداند. توجه: با تغییر مقدار، تمام مقادیر تنظیمات به مقادیر پیش‌فرض بازنشانی می‌شوند. خواندنی [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | اسلاید والد یک شکل را بازمی‌گرداند. فقط خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | متن شکل [SmartArt](../smartart/) را بازمی‌گرداند. فقط خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | شیء [ThreeDFormat](../../aspose.slides/threedformat/) را که شامل ویژگی‌های اثر 3D برای یک شکل است، بازمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند مقدار null برگرداند. فقط خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | شناسه داخلی محدد به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را بازمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتخصیص شود، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. فقط خواندنی **uint32_t**. همچنین مراجعه کنید به [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | عرض شکل را بر حسب پوینت دریافت می‌کند. خواندنی **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | مختصات x گوشهٔ بالا-چپ شکل را بر حسب پوینت دریافت می‌کند. خواندنی **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | مختصات y گوشهٔ بالا-چپ شکل را بر حسب پوینت دریافت می‌کند. خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را بازمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی پیشِ ترتیب z را برمی‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | یک شکل جای‌دار پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌گیرد) را بازمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | کپی مسیر شکل هندسی را بازمی‌گرداند. مختصات نسبت به گوشهٔ بالا-چپ شکل است. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | تصویر بندانگشتی شکل را بازمی‌گرداند. نوع محدودهٔ تصویر بندانگشتی [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) به طور پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | تصویر بندانگشتی شکل را بازمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | حدهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر پایه ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | تعریف می‌کند که این شکل جای‌دار نیست. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | خاصیت مشخص می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ارتفاع شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | تعیین می‌کند شکل مخفی است یا نه. نوشتن **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند را که برای کلیک ماوس تعریف شده است تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند را که برای حرکت ماوس فوق آن تعریف شده است تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | گزینه 'علامت‌گذاری به عنوان تزئینی' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های خام قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | تعداد درجه‌هایی که شکل مشخص حول محور z چرخیده است را تنظیم می‌کند. مقدار مثبت به معنی چرخش ساعت‌گرد، مقدار منفی به معنی چرخش پادساع گرد است. نوشتن **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | نوع پیش‌تنظیم هندسه را تنظیم می‌کند. توجه: با تغییر مقدار، تمام مقادیر تنظیمات به مقادیر پیش‌فرض بازنشانی می‌شوند. نوشتن [Slides::ShapeType](../../aspose.slides/shapetype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | عرض شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | مختصات x گوشهٔ بالا-چپ شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | مختصات y گوشهٔ بالا-چپ شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | هندسه شکل را از شیء [IGeometryPath](../../aspose.slides/igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([ShapeType](../../aspose.slides/shapetype/)) را به [ShapeType::Custom](../../aspose.slides/shapetype/) تغییر می‌دهد. |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | هندسه شکل را از آرایه‌ای از [IGeometryPath](../../aspose.slides/igeometrypath/) به‌روزرسانی می‌کند. مختصات باید نسبت به گوشهٔ بالا-چپ شکل باشد. نوع شکل ([ShapeType](../../aspose.slides/shapetype/)) را به [ShapeType::Custom](../../aspose.slides/shapetype/) تغییر می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n-ام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../../aspose.slides/shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../../aspose.slides/shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [GeometryShape](../../aspose.slides/geometryshape/)
* کلاس [ISmartArtShape](../ismartartshape/)
* فضای‌نام [Aspose::Slides::SmartArt](../)
* کتابخانه [Aspose.Slides](../../)