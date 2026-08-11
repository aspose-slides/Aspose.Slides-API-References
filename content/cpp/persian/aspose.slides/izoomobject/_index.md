---
title: IZoomObject
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک شی Zoom در اسلاید است.
type: docs
weight: 4265
url: /fa/aspose.slides/izoomobject/
---
## IZoomObject کلاس

Represents a Zoom object in a slide.

```cpp
class IZoomObject : public virtual Aspose::Slides::IGraphicalObject
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر جای‌دار (placeholder) وجود نداشته باشد، یک جای‌دار جدید اضافه می‌کند و ویژگی‌های جای‌دار را به مقدار مشخص‌شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندنی [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسلی اعمال‌شده بر یک شکل است برمی‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است برمی‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ویژگی‌های چارچوب شکل را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را بر حسب پوینت می‌گیرد. خواندنی **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند آیا شکل مخفی است یا نه. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندهای ابرمتنی. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندهای ابرمتنی تعریف‌شده برای عبور ماوس را برمی‌گرداند. خواندنی [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() | نوع تصویر یک شیء زوم را می‌گیرد. خواندنی [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه «Mark as decorative» را می‌گیرد. خواندن/نوشتن **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند آیا شکل TextHolder است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | یک شناسهٔ یکتا دارای دامنهٔ اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد به‌طور قابل اعتماد شکل را از هرجای سند ارجاع دهند. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null را برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | محل‌نگهدار برای یک شکل را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ویژگی‌های چارچوب خام شکل را برمی‌گرداند. خواندنی [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](./get_returntoparent/)() | رفتار ناوبری در نمایش اسلاید را می‌گیرد. خواندنی **bool**. مقدار پیش‌فرض: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](./get_showbackground/)() | مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا نه را می‌گیرد. خواندنی **bool**. مقدار پیش‌فرض: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](./get_transitionduration/)() | مدت زمان انتقال بین Zoom و اسلاید را می‌گیرد. خواندنی **float**. مقدار پیش‌فرض: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | یک شناسهٔ داخلی با دامنهٔ ارائه (presentation) را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا به‌صورت برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتای پایدار رفتار شود. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را بر حسب پوینت می‌گیرد. خواندنی **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشهٔ بالایی-چپ شکل را بر حسب پوینت می‌گیرد. خواندنی **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشهٔ بالایی-چپ شکل را بر حسب پوینت می‌گیرد. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() | تصویر برای شیء زوم را می‌گیرد. خواندنی [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در انتهای ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترتیب z برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل پایهٔ placeholder را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارشگر مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر کوچک شکل را برمی‌گرداند. نوع محدودهٔ تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نشان‌دهندهٔ نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارشگر مرجع مشترک را بر حسب مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل placeholder نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های چارچوب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند آیا شکل مخفی است یا نه. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند ابرمتنی تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند ابرمتنی تعریف‌شده برای عبور ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) | نوع تصویر یک شیء زوم را تنظیم می‌کند. نوشتن [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینه «Mark as decorative» را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های چارچوب خام شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](./set_returntoparent/)(**bool**) | رفتار ناوبری در نمایش اسلاید را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پادساعتگرد است. نوشتن **float**. |
| virtual void [set_ShowBackground](./set_showbackground/)(**bool**) | مقداری که مشخص می‌کند آیا Zoom پس‌زمینه اسلاید مقصد را استفاده می‌کند یا نه را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: true |
| virtual void [set_TransitionDuration](./set_transitionduration/)(**float**) | مدت زمان انتقال بین Zoom و اسلاید را تنظیم می‌کند. نوشتن **float**. مقدار پیش‌فرض: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشهٔ بالایی-چپ شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشهٔ بالایی-چپ شکل را بر حسب پوینت تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | تصویر برای شیء زوم را تنظیم می‌کند. نوشتن [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارشگر مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | تعداد شمارشگر مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | تعداد شمارشگر مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | تعداد شمارشگر مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | تعداد شمارشگر مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IGraphicalObject](../igraphicalobject/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)