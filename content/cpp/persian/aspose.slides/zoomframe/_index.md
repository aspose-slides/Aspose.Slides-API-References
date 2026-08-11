---
title: ZoomFrame
second_title: مرجع API Aspose.Slides برای C++
description: یک شی Zoom اسلاید را در یک اسلاید نشان می‌دهد.
type: docs
weight: 5578
url: /fa/aspose.slides/zoomframe/
---
## کلاس ZoomFrame

یک شی Zoom [Slide](../slide/) را در یک اسلاید نشان می‌دهد.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | در صورت عدم وجود، یک جایگزین جدید می‌افزاید و ویژگی‌های جایگزین را به مقدار مشخص‌شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از روش [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقاط شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. مطالعه [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. مطالعه [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-و-سفید چگونه رندر شود. مطالعه [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شی [EffectFormat](../effectformat/) را که شامل افکت‌های پیکسلی اعمال‌شده بر یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌هایی که ویژگی اثر ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شی [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌هایی که ویژگی پر ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. مطالعه [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را برحسب پوینت می‌گیرد. خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | تعیین می‌کند که آیا شکل مخفی است یا نه. خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوندی که برای کلیک ماوس تعریف شده است را برمی‌گرداند. مطالعه [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوندی که برای قرار‌گیری ماوس تعریف شده است را برمی‌گرداند. مطالعه [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | نوع تصویر یک شی Zoom را برمی‌گیرد. مطالعه [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه «علامت‌گذاری به‌عنوان تزئینی» را می‌گیرد. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند که آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شی [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌هایی که ویژگی خط ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید مقدار null نباشد. در صورت نیاز مقدار رشتهٔ خالی را استفاده کنید. مطالعه [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسهٔ یکتای محدودهٔ اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای میان‌پیمایان امکان ارجاع قابل اعتماد به شکل از هرجای سند را می‌دهد. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | در صورت گروه‌بندی شکل، شی والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | جایگزین یک شکل را برمی‌گرداند. اگر شکل جایگزینی نداشته باشد مقدار null برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائهٔ والد یک اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های فریم خام شکل را برمی‌گرداند. مطالعه [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | رفتار ناوبری در نمایش اسلاید را می‌گیرد. خواندنی **bool**. مقدار پیش‌فرض: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجات چرخش شکل مشخص شده حول محور Z را برمی‌گرداند. مقدار مثبت نشان‌دهندهٔ چرخش ساعتگرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعتگرد است. خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | مقداری که مشخص می‌کند Zoom آیا پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه را می‌گیرد. خواندنی **bool**. مقدار پیش‌فرض: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | شی اسلایدی که شی Zoom [Slide](../slide/) به آن پیوند دارد را می‌گیرد. مطالعه [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شی [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های اثر ۳بعدی برای یک شکل است برمی‌گرداند. توجه: برای برخی انواع شکل‌هایی که ویژگی ۳بعدی ندارند می‌تواند مقدار null برگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | مدت زمان انتقال بین Zoom و اسلاید را می‌گیرد. خواندنی **float**. مقدار پیش‌فرض: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسهٔ داخلی محدودهٔ ارائه را برمی‌گرداند که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به عنوان کلید یکتای پایدار در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را برحسب پوینت می‌گیرد. خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات X گوشهٔ بالایی‌چپ شکل را برحسب پوینت می‌گیرد. خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات Y گوشهٔ بالایی‌چپ شکل را برحسب پوینت می‌گیرد. خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | تصویر برای شی Zoom را می‌گیرد. مطالعه [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب Z را برمی‌گرداند. Shapes[0] شکل در انتهای ترتیب Z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب Z را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل جایگزین پایه را برمی‌گرداند (شکلی از چیدمان و/یا اسلاید مستر که شکل جاری از آن ارث‌بری می‌کند). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر بندانگشتی شکل را برمی‌گرداند. نوع مرزهای تصویر بندانگشت [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به طور پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر بندانگشت شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | مرزهای بصری شکل را که از محتوای رندر شده محاسبه می‌شود، می‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوعی است که توسط targetType توصیف شده. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. واقعاً چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شی از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل جایگزین نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | ویژگی مشخص می‌کند یک شکل در حالت نمایش سیاه-و-سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را برحسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | وضعیت مخفی بودن شکل را تنظیم می‌کند. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوند تعریف‌شده برای قرار‌گیری ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | نوع تصویر یک شی Zoom را تنظیم می‌کند. نوشتن [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه «علامت‌گذاری به‌عنوان تزئینی» را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. باید مقدار null نباشد. در صورت نیاز مقدار رشتهٔ خالی را استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم خام شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | رفتار ناوبری در نمایش اسلاید را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجات چرخش شکل مشخص شده حول محور Z را تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعتگرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعتگرد است. نوشتن **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | مقدار مشخص‌کنندهٔ استفاده از پس‌زمینه اسلاید مقصد توسط Zoom را تنظیم می‌کند. نوشتن **bool**. مقدار پیش‌فرض: true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | شی اسلایدی که شی Zoom [Slide](../slide/) به آن پیوند دارد را تنظیم می‌کند. نوشتن [ISlide](../islide/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | مدت زمان انتقال بین Zoom و اسلاید را تنظیم می‌کند. نوشتن **float**. مقدار پیش‌فرض: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را برحسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات X گوشهٔ بالایی‌چپ شکل را برحسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات Y گوشهٔ بالایی‌چپ شکل را برحسب پوینت تنظیم می‌کند. نوشتن **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | تصویر برای شی Zoom را تنظیم می‌کند. نوشتن [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الیتم n قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../shape/) را به صورت فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../shape/) را به صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ZoomObject](../zoomobject/)
* کلاس [IZoomFrame](../izoomframe/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)