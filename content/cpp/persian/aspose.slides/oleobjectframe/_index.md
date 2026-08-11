---
title: OleObjectFrame
second_title: Aspose.Slides برای مرجع API C++
description: یک شی OLE را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 4603
url: /fa/aspose.slides/oleobjectframe/
---
## OleObjectFrame کلاس

یک شی OLE را بر روی اسلاید نشان می‌دهد.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | یک جای‌نگهدار جدید اضافه می‌کند اگر وجود نداشته باشد و خصوصیات جای‌نگهدار را به مقدار مشخص‌شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند؛ جایی که دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند؛ جایی که دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای کاربردهای داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | خاصیت نحوه نمایش شکل در حالت سیاه-سفید را مشخص می‌کند. ببینید [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شی [EffectFormat](../effectformat/) را که شامل افکت‌های پیکسلی اعمال شده به یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که خصوصیات افکت ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | اطلاعات درباره داده‌های توکار OLE را دریافت می‌کند. ببینید [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | نام فایل شی OLE توکار را برمی‌گرداند. |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | مسیر شی OLE توکار را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شی [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های پر ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | خصوصیات قاب شکل را برمی‌گرداند. ببینید [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را بر حسب نقطه‌ها دریافت می‌کند. فقط-خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | مشخص می‌کند آیا شکل مخفی است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | هایپرلینکی که برای کلیک ماوس تعریف شده است را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر هایپرلینک را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | هایپرلینکی که برای عبور ماوس تعریف شده است را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | تعیین می‌کند آیا شی به‌صورت نماد (آیکن) قابل مشاهده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | تعیین می‌کند آیا شی به فایل خارجی لینک شده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شی [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | مسیر کامل به یک فایل لینک‌شده را برمی‌گرداند. نام کوتاه فایل استفاده خواهد شد. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | مسیر کامل به یک فایل لینک‌شده را برمی‌گرداند. نام بلند فایل استفاده خواهد شد. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | مسیر نسبی به یک فایل لینک‌شده را در صورت وجود برمی‌گرداند، در غیر این صورت رشتهٔ خالی بر می‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید مقدار null نباشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی استفاده کنید. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | نام یک شی را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | ProgID یک شی را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | یک شناساگر یکتای scoped به اسلاید که در طول عمر شکل ثابت می‌ماند و امکان ارجاع قابل اطمینان به شکل را از هر نقطه‌ای در سند برای PowerPoint یا کد اینترآپ فراهم می‌کند را بر می‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | شی والد [GroupShape](../groupshape/) را در صورتی که شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | جای‌نگهدارندهٔ یک شکل را برمی‌گرداند. اگر شکل جای‌نگهدارنده نداشته باشد null برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائه والد اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | خصوصیات خام قاب شکل را برمی‌گرداند. ببینید [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌هایی که شکل مشخص شده حول محور z چرخش دارد را برمی‌گرداند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | شی ویژگی‌های پر تصویر OleObject را برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | عنوان آیکن OleObject را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شی [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های افکت 3D برای یک شکل است برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | یک شناساگر داخلی scoped به ارائه که برای استفاده توسط افزودنی‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتخصیص یابد، نباید به عنوان کلید یکتای دائم در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | تعیین می‌کند آیا شی توکار لینک‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز شود یا نه. فقط-خواندنی **bool**. |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را بر حسب نقطه‌ها دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقطه‌ها دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقطه‌ها دریافت می‌کند. فقط-خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترین ترتیب را بر می‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترین را بر می‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل جای‌نگهدار پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر کوچک (thumbnail) شکل را برمی‌گرداند. نوع محدوده تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی یک نمونه از نوعی است که توسط targetType توصیف شده است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری در بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیز را کپی نمی‌کند؛ فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند؛ فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل یک جای‌نگهدار نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | خاصیت نحوه نمایش شکل در حالت سیاه-سفید را مشخص می‌کند. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | خصوصیات قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را بر حسب نقطه‌ها تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | تعیین می‌کند آیا شکل مخفی است یا نه. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینک تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینک تعریف‌شده برای عبور ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | تعیین می‌کند آیا شی به‌صورت آیکن قابل مشاهده است یا نه. نوشتن **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | مسیر کامل یک فایل لینک‌شده را برمی‌گرداند. نام بلند فایل استفاده خواهد شد. نوشتن [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید رشتهٔ خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | نام یک شی را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | ProgID یک شی را برمی‌گرداند. فقط-خواندنی [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | خصوصیات خام قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش قالب مشخص شده حول محور z را تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. نوشتن **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | عنوان آیکن OleObject را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | تعیین می‌کند آیا شی توکار لینک‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز شود یا نه. نوشتن **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را بر حسب نقطه‌ها تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالا-چپ شکل را بر حسب نقطه‌ها تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالا-چپ شکل را بر حسب نقطه‌ها تنظیم می‌کند. نوشتن **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | اطلاعات درباره داده‌های توکار OLE را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای اشاره‌گر اشتراکی). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## نکات

مثال زیر نشان می‌دهد چگونه به فریم‌های شی OLE دسترسی پیدا کنیم. 
```cpp
// فایل PPTX را به یک شی ارائه بارگذاری می‌کند
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// به اسلاید اول دسترسی می‌یابد
auto slide = pres->get_Slides()->idx_get(0);
// شکل را به OleObjectFrame تبدیل می‌کند
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// شی OLE را می‌خواند و بر روی دیسک می‌نویسد
if (oleObjectFrame != nullptr)
{
    // داده‌های فایل توکار را دریافت می‌کند
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // پسوند فایل توکار را دریافت می‌کند
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // مسیری برای ذخیره فایل استخراج‌شده ایجاد می‌کند
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // داده‌های استخراج‌شده را ذخیره می‌کند
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## همچنین ببینید

* کلاس [GraphicalObject](../graphicalobject/)
* کلاس [IOleObjectFrame](../ioleobjectframe/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)