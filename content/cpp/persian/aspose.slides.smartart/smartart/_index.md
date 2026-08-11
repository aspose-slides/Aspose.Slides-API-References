---
title: SmartArt
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار SmartArt را نشان می‌دهد
type: docs
weight: 66
url: /fa/aspose.slides.smartart/smartart/
---
## کلاس SmartArt

نمایش یک [SmartArt](./) نمودار

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | یک نگهدارنده جدید را اضافه می‌کند اگر موجود نباشد و ویژگی‌های نگهدارنده را به یک مورد مشخص تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر براساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور دو برابر به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر براساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | مجموعه‌ای از تمام گره‌ها در شیء [SmartArt](./) را برمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../ismartartnodecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | این خصوصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندنی [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | سبک رنگ شیء [SmartArt](./) را برمی‌گرداند. خواندنی [SmartArtColorType](../smartartcolortype/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | شیء [EffectFormat](../../aspose.slides/effectformat/) را برمی‌گرداند که حاوی اثرات پیکسل اعمال‌شده به یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی‌های اثر ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | شیء [FillFormat](../../aspose.slides/fillformat/) را برمی‌گرداند که حاوی ویژگی‌های قالب‌بندی پر برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی‌های پر ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. خواندنی [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، به دست می‌آورد. خواندنی **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | پیوند فرامیانی تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواندنی [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | مدیر پیوند فرامیانی را برمی‌گرداند. فقط خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | پیوند فرامیانی تعریف‌شده برای مرور ماوس را برمی‌گرداند. خواندنی [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | گزینه «Mark as decorative» را می‌گیرد. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط خواندنی **bool**. |
| **bool** [get_IsReversed](./get_isreversed/)() override | وضعیت نمودار [SmartArt](./) را نسبت به (چپ-به-راست) LTR یا (راست-به-چپ) RTL بازمی‌گرداند یا تنظیم می‌کند، اگر نمودار از معکوس‌سازی پشتیبانی کند. خواندنی **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط خواندنی **bool**. |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | چیدمان شیء [SmartArt](./) را برمی‌گرداند. خواندنی [SmartArtLayoutType](../smartartlayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | شیء [LineFormat](../../aspose.slides/lineformat/) را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. توجه: برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید مقدار null نباشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. خواندنی [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | یک گره از مجموعه گره‌های ریشه در شیء [SmartArt](./) را در ایندکس مشخص‌شده برمی‌گرداند. فقط خواندنی [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | یک گره از مجموعه شامل تمام گره‌ها در شیء [SmartArt](./) را در ایندکس مشخص‌شده برمی‌گرداند. فقط خواندنی [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | مجموعه‌ای از گره‌های ریشه در شیء [SmartArt](./) را برمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | شناسه منحصر به فرد scoped به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت باقی می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل‌اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد. فقط خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | شیء والد [GroupShape](../../aspose.slides/groupshape/) را برمی‌گرداند اگر شکل گروهبندی شده باشد. در غیر این صورت مقدار null برمی‌گرداند. فقط خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | نگهدارنده برای یک شکل را برمی‌گرداند. اگر شکل نگهدارنده نداشته باشد مقدار null برمی‌گرداند. فقط خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | ارائه والد اسلاید را برمی‌گرداند. فقط خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | سبک سریع شیء [SmartArt](./) را برمی‌گرداند. خواندنی [SmartArtQuickStyleType](../smartartquickstyletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | ویژگی‌های فریم شکل خام را برمی‌گرداند. خواندنی [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | شیء [ThreeDFormat](../../aspose.slides/threedformat/) را که شامل ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی‌های 3D ندارند می‌تواند مقدار null بازگرداند. فقط خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً تخصیص یابد، نباید به عنوان کلید منحصر به‌فرد پایدار در نظر گرفته شود. فقط خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، به دست می‌آورد. خواندنی **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | مختصات x گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، به دست می‌آورد. خواندنی **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | مختصات y گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، به دست می‌آورد. خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در انتهای جلو ترتیب z را باز می‌گرداند. فقط خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | یک شکل نگهدارنده پایه را برمی‌گرداند (شکل از چیدمان و/یا اسلاید اصلی که شکل جاری از آن به ارث می‌برد). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | تصویر کوچک شکل را برمی‌گرداند. نوع محدوده تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، به دست می‌آورد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است یا نه. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار تعیین‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | تعریف می‌کند که این شکل یک نگهدارنده نیست. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | خصوصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | سبک رنگ شیء [SmartArt](./) را تنظیم می‌کند. نوشتن [SmartArtColorType](../smartartcolortype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | تعیین می‌کند که آیا شکل مخفی است یا نه. نوشتن **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند فرامیانی تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند فرامیانی تعریف‌شده برای مرور ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | گزینه «Mark as decorative» را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | وضعیت نمودار [SmartArt](./) را نسبت به (چپ-به-راست) LTR یا (راست-به-چپ) RTL بازمی‌گرداند یا تنظیم می‌کند، اگر نمودار از معکوس‌سازی پشتیبانی کند. نوشتن **bool**. |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | چیدمان شیء [SmartArt](./) را تنظیم می‌کند. نوشتن [SmartArtLayoutType](../smartartlayouttype/). |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید مقدار null باشد. در صورت نیاز از رشته خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | سبک سریع شیء [SmartArt](./) را تنظیم می‌کند. نوشتن [SmartArtQuickStyleType](../smartartquickstyletype/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. نوشتن **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | مختصات x گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | مختصات y گوشه بالایی-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارنده مرجع مشترک را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌نگشانی بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پینترها یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتوای [Shape](../../aspose.slides/shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتوای [Shape](../../aspose.slides/shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌نماید. |

## موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject/)
* کلاس [ISmartArt](../ismartart/)
* فضای نام [Aspose::Slides::SmartArt](../)
* کتابخانه [Aspose.Slides](../../)