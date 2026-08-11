---
title: IZoomFrame
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء Zoom اسلاید را در یک اسلاید نشان می‌دهد.
type: docs
weight: 4252
url: /fa/aspose.slides/izoomframe/
---
## IZoomFrame کلاس

یک شیء Zoom [Slide](../slide/) را در یک اسلاید نشان می‌دهد.

```cpp
class IZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر موجود نباشد، یک نگهدارنده جدید اضافه می‌کند و ویژگی‌های نگهدارنده را به یک مورد مشخص تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. مطالعه کنید [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. مطالعه کنید [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. مطالعه کنید [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسلی اعمال شده بر شکل است برمی‌گرداند. فقط‌خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پرکننده برای شکل است برمی‌گرداند. فقط‌خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ویژگی‌های فریم شکل را برمی‌گرداند. مطالعه کنید [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را به نقطه (points) می‌گیرد. قابل‌خواندن **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند آیا شکل پنهان است یا خیر. قابل‌خواندن **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهای ابرمتنی تعریف شده برای کلیک موش را برمی‌گرداند. مطالعه کنید [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندهای ابرمتنی. فقط‌خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندهای ابرمتنی تعریف شده برای عبور موش را برمی‌گرداند. مطالعه کنید [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | نوع تصویر یک شیء Zoom را می‌گیرد. قابل‌خواندن [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه 'Mark as decorative' را می‌گیرد. قابل‌خواندن/نوشتن **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند آیا شکل TextHolder است یا نه. فقط‌خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط‌خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را برمی‌گرداند. مطالعه کنید [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | شناسهٔ یکتای محدودهٔ اسلاید که برای طول عمر شکل ثابت می‌ماند را برمی‌گرداند. فقط‌خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | شیء والد [GroupShape](../groupshape/) را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | نگهدارندهٔ یک شکل را برمی‌گرداند. فقط‌خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط‌خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ویژگی‌های فریم شکل خام را برمی‌گرداند. مطالعه کنید [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | رفتار ناوبری در ارائه اسلاید را می‌گیرد. قابل‌خواندن **bool**. مقدار پیش‌فرض: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را برمی‌گرداند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. قابل‌خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | مقداری که مشخص می‌کند آیا Zoom از پس‌زمینهٔ اسلاید مقصد استفاده می‌کند را می‌گیرد. قابل‌خواندن **bool**. مقدار پیش‌فرض: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | شیء اسلایدی که شیء Zoom [Slide](../slide/) به آن پیوند دارد را می‌گیرد. مطالعه کنید [ISlide](../islide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط‌خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | مدت زمان انتقال بین Zoom و اسلاید را می‌گیرد. قابل‌خواندن **float**. مقدار پیش‌فرض: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | شناسهٔ داخلی محدودهٔ ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتای پایدار در نظر گرفته شود. فقط‌خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را به نقطه (points) می‌گیرد. قابل‌خواندن **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشهٔ بالا-چپ شکل را به نقطه (points) می‌گیرد. قابل‌خواندن **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشهٔ بالا-چپ شکل را به نقطه (points) می‌گیرد. قابل‌خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | تصویر برای شیء Zoom را می‌گیرد. مطالعه کنید [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را می‌دهد و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را می‌دهد. فقط‌خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل نگهدارندهٔ پایه‌ای (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر کوچک شکل را برمی‌گرداند. نوع مرزهای تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل () در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل نگهدارنده نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را به نقطه (points) تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند آیا شکل پنهان باشد یا نه. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند ابرمتنی تعریف شده برای کلیک موش را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند ابرمتنی تعریف شده برای عبور موش را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | نوع تصویر یک شیء Zoom را تنظیم می‌کند. نوشتن [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینه 'Mark as decorative' را تنظیم می‌کند. قابل‌خواندن/نوشتن **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | رفتار ناوبری در ارائه اسلاید را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌هایی که شکل مشخص‌شده حول محور z چرخانده می‌شود را تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. نوشتن **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | مقداری که مشخص می‌کند آیا Zoom از پس‌زمینهٔ اسلاید مقصد استفاده می‌کند را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: true |
| virtual void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | شیء اسلایدی که شیء Zoom [Slide](../slide/) به آن پیوند دارد را تنظیم می‌کند. نوشتن [ISlide](../islide/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | مدت زمان انتقال بین Zoom و اسلاید را تنظیم می‌کند. نوشتن **float**. مقدار پیش‌فرض: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را به نقطه (points) تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشهٔ بالا-چپ شکل را به نقطه (points) تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشهٔ بالا-چپ شکل را به نقطه (points) تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | تصویر برای شیء Zoom را تنظیم می‌کند. نوشتن [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الیتمپلیت nام را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازهٔ C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای قفل () در C# را برای باز کردن قفل پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجعه کنید

* کلاس [IZoomObject](../izoomobject/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)