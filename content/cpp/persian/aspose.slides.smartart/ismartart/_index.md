---
title: ISmartArt
second_title: مرجع API Aspose.Slides برای C++
description: نمایش‌دهنده یک نمودار SmartArt.
type: docs
weight: 1
url: /fa/aspose.slides.smartart/ismartart/
---
## ISmartArt کلاس

نمایش‌دهنده یک [SmartArt](../smartart/) نمودار.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | اگر هیچ‌یک وجود نداشته باشد، یک مکان‌گیر جدید اضافه می‌کند و خصوصیات مکان‌گیر را به مقدار مشخص شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | مجموعه‌ای از تمام گره‌ها را در شیء [SmartArt](../smartart/) برمی‌گرداند. فقط‌خواندنی [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | خاصیتی که مشخص می‌کند یک شکل چگونه در حالت نمایش سیاه-سفید رندرسازی می‌شود. خواند [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | سبک رنگ [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. خواند [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | شیء [EffectFormat](../../aspose.slides/effectformat/) که شامل افکت‌های پیکسل اعمال‌شده بر یک شکل است را برمی‌گرداند. فقط‌خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | شیء [FillFormat](../../aspose.slides/fillformat/) که شامل خصوصیات قالب‌بندی پر رنگ برای یک شکل است را برمی‌گرداند. فقط‌خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | خصوصیات چارچوب شکل را برمی‌گرداند. خواند [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | ارتفاع شکل را به نقاط می‌گیرد. خواند **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | تشخیص می‌دهد آیا شکل مخفی است یا نه. خواند **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهای تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواند [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها. فقط‌خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوند تعریف‌شده برای حرکت ماوس روی عنصر را برمی‌گرداند. خواند [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | گزینه 'Mark as decorative' را دریافت می‌کند. خواند/نوشت **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | تشخیص می‌دهد آیا شکل گروه‌بندی شده است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | وضعیت نمودار [SmartArt](../smartart/) را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، اگر نمودار از معکوس‌سازی پشتیبانی کند. خواند **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | تشخیص می‌دهد آیا شکل TextHolder است یا نه. فقط‌خواندنی **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | طرح‌بندی شیء [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. خواند [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | شیء [LineFormat](../../aspose.slides/lineformat/) که شامل خصوصیات قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط‌خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | نام یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | یک گره از مجموعه ریشه‌ها در شیء [SmartArt](../smartart/) با ایندکس مشخص شده را برمی‌گرداند. فقط‌خواندنی [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | یک گره از مجموعه‌ای که شامل تمام گره‌ها در شیء [SmartArt](../smartart/) است، با ایندکس مشخص شده را برمی‌گرداند. فقط‌خواندنی [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | مجموعه‌ای از گره‌های ریشه در شیء [SmartArt](../smartart/) را برمی‌گرداند. فقط‌خواندنی [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | یک شناسه منحصر به‌فرد scoped به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و اجازه می‌دهد PowerPoint یا کد interop به‌طور قابل اطمینان از هر نقطه‌ای در سند به شکل ارجاع دهد. فقط‌خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../../aspose.slides/groupshape/) را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | مکان‌گیر برای یک شکل را برمی‌گرداند. فقط‌خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | سبک سریع شیء [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. خواند [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | خصوصیات چارچوب خام شکل را برمی‌گرداند. خواند [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواند **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | شیء [ThreeDFormat](../../aspose.slides/threedformat/) که شامل خصوصیات قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط‌خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | یک شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید منحصر به‌فرد ماندگار درنظر گرفته شود. فقط‌خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | عرض شکل را به نقاط می‌گیرد. خواند **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | مختصات x گوشه بالای چپ شکل را به نقاط می‌گیرد. خواند **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | مختصات y گوشه بالای چپ شکل را به نقاط می‌گیرد. خواند **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب z برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | یک شکل مکان‌گیر پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) bounds تصویر بندانگشتی شکل به‌طور پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری با عبارت C# lock(). مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به وسیله مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به وسیله مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | تعریف می‌کند که این شکل مکان‌گیر نیست. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | خاصیتی که مشخص می‌کند یک شکل چگونه در حالت نمایش سیاه-سفید رندرسازی می‌شود. نوشت [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | سبک رنگ [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. نوشت [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | خصوصیات چارچوب شکل را تنظیم می‌کند. نوشت [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ارتفاع شکل را به نقاط تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | تشخیص می‌دهد آیا شکل مخفی است یا نه. نوشت **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشت [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند تعریف‌شده برای حرکت ماوس روی عنصر را تنظیم می‌کند. نوشت [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | گزینه 'Mark as decorative' را تنظیم می‌کند. نوشت/خواند **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | وضعیت نمودار [SmartArt](../smartart/) را نسبت به جهت چپ-به-راست (LTR) یا راست-به-چپ (RTL) برمی‌گرداند یا تنظیم می‌کند، اگر نمودار از معکوس‌سازی پشتیبانی کند. نوشت **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | طرح‌بندی شیء [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. نوشت [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | سبک سریع شیء [SmartArt](../smartart/) را برمی‌گرداند یا تنظیم می‌کند. نوشت [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | خصوصیات چارچوب خام شکل را تنظیم می‌کند. نوشت [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | تعداد درجاتی که شکل مشخص شده حول محور z می‌چرخد را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. نوشت **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | عرض شکل را به نقاط تنظیم می‌کند. نوشت **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | مختصات x گوشه بالای چپ شکل را به نقاط تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | مختصات y گوشه بالای چپ شکل را به نقاط تنظیم می‌کند. نوشت **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازقفل‌گذاری عبارت C# lock(). مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* فضای‌نام [Aspose::Slides::SmartArt](../)
* کتابخانه [Aspose.Slides](../../)