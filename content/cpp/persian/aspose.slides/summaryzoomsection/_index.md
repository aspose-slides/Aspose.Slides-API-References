---
title: SummaryZoomSection
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء Summary Zoom Section را در یک فریم Summary Zoom نشان می‌دهد.
type: docs
weight: 5331
url: /fa/aspose.slides/summaryzoomsection/
---
## کلاس SummaryZoomSection

Represents a Summary Zoom [Section](../section/) object in a Summary Zoom frame.

```cpp
class SummaryZoomSection : public Aspose::Slides::SectionZoomFrame,
                           public Aspose::Slides::ISummaryZoomSection
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | اگر جای‌نگهدارنی موجود نباشد، یک جای‌نگهدارنی جدید اضافه می‌کند و خصوصیات جای‌نگهدارنی را به مقدار مشخص شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | خصوصیت مشخص می‌کند شکل در حالت نمایش سیاه‌وسفید چگونه رندر شود. ببینید [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| [System::String](../../system/string/) [get_Description](./get_description/)() override | توضیح متنی شیء Summary Zoom [Section](../section/) را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیء [EffectFormat](../effectformat/) را برمی‌گرداند که شامل افکت‌های پیکسل اعمال‌شده به یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات افکت ندارند، مقدار null بازگرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | شیء [FillFormat](../fillformat/) را برمی‌گرداند که شامل خصوصیات قالب‌بندی پر کردن برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات پر کردن ندارند، مقدار null بازگرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | خصوصیات فریم شکل را برمی‌گرداند. ببینید [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود، دریافت می‌کند. فقط-خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | مشخص می‌کند آیا شکل مخفی است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر پیوندهای ابرمتنی را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس بر روی عنصر را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | نوع تصویر شیء زوم را دریافت می‌کند. ببینید [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | مشخص می‌کند آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | مشخص می‌کند آیا شکل TextHolder_PPT است یا نه. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیء [LineFormat](../lineformat/) را برمی‌گرداند که شامل خصوصیات قالب‌بندی خط برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات خط ندارند، مقدار null بازگرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. باید مقدار null نباشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. ببینید [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسهٔ یکتا scoped به اسلاید که در طول زمان حیات شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجایی در سند می‌دهد را برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null بازمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | جای‌نگهدارنی برای یک شکل را برمی‌گرداند. اگر شکل جای‌نگهدارنی نداشته باشد، مقدار null بازمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائه والد اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | خصوصیات فریم خام شکل را برمی‌گرداند. ببینید [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | رفتار ناوبری در نمایش اسلاید را دریافت می‌کند. فقط-خواندنی **bool**. مقدار پیش‌فرض: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد، مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | مقدار مشخص‌کننده این که Zoom آیا از پس‌زمینهٔ اسلاید مقصد استفاده کند یا نه را دریافت می‌کند. فقط-خواندنی **bool**. مقدار پیش‌فرض: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../sectionzoomframe/get_targetsection/)() override | شیء بخش را که شیء Zoom [Section](../section/) به آن لینک می‌کند، دریافت می‌کند. ببینید [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را برمی‌گرداند که شامل خصوصیات افکت‌های 3d برای یک شکل است. توجه: ممکن است برای برخی انواع شکل‌ها که خصوصیات 3d ندارند، مقدار null بازگرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | عنوان متنی شیء Summary Zoom [Section](../section/) را برمی‌گرداند. |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | مدت زمان انتقال بین Zoom و اسلاید را دریافت می‌کند. فقط-خواندنی **float**. مقدار پیش‌فرض: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسهٔ داخلی scoped به ارائه که برای افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازنشانی شود، نباید به عنوان کلید یکتای پایدار در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را که به نقطه اندازه‌گیری می‌شود، دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود، دریافت می‌کند. فقط-خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالایی چپ شکل را که به نقطه اندازه‌گیری می‌شود، دریافت می‌کند. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | تصویر برای شیء زوم را دریافت می‌کند. ببینید [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشت‌ترین در ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی‌ترین را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل جایگزین پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌آورد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر کوچک شکل را برمی‌گرداند. نوع محدودهٔ تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | حدود بصری شکل را که از محتوای رندر شدهٔ آن محاسبه می‌شود، دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملیات 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌آورد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمامی ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | تعریف می‌کند که این شکل یک جایگزین نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | خواص نحوه رندر شکل در حالت نمایش سیاه-سفید را مشخص می‌کند. [Slides::BlackWhiteMode](../blackwhitemode/) را بنویسید. |
| void [set_Description](./set_description/)([System::String](../../system/string/)) override | توضیح متنی شیء Summary Zoom [Section](../section/) را برمی‌گرداند. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. [IShapeFrame](../ishapeframe/) را بنویسید. |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. **float** را بنویسید. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | مشخص می‌کند که آیا شکل مخفی است یا نه. **bool** را بنویسید. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندی که برای کلیک ماوس تعریف شده است را تنظیم می‌کند. [IHyperlink](../ihyperlink/) را بنویسید. |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندی که برای حرکت ماوس روی آن تعریف شده است را تنظیم می‌کند. [IHyperlink](../ihyperlink/) را بنویسید. |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | نوع تصویر شیء زوم را تنظیم می‌کند. [ZoomImageType](../zoomimagetype/) را بنویسید. مقدار پیش‌فرض: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینهٔ «Mark as decorative» را تنظیم می‌کند. **bool** را بخوانید/بنویسید. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید خالی باشد. در صورت نیاز از مقدار رشتهٔ خالی استفاده کنید. [System::String](../../system/string/) را بنویسید. |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم خام شکل را تنظیم می‌کند. [IShapeFrame](../ishapeframe/) را بنویسید. |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | رفتار ناوبری در ارائه اسلایدی را تنظیم می‌کند. **bool** را بنویسید. مقدار پیش‌فرض: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش جهت ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش خلاف جهت ساعت‌گرد است. **float** را بنویسید. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | مقداری را تنظیم می‌کند که مشخص می‌کند آیا زوم پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه. **bool** را بنویسید. مقدار پیش‌فرض: true |
| void [set_TargetSection](../sectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | شیء بخش که شیء زوم [Section](../section/) به آن لینک می‌شود را تنظیم می‌کند. [ISection](../isection/) را بنویسید. |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | عنوان متنی شیء Summary Zoom [Section](../section/) را برمی‌گرداند. |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | مدت زمان انتقال بین زوم و اسلاید را تنظیم می‌کند. **float** را بنویسید. مقدار پیش‌فرض: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود تنظیم می‌کند. **float** را بنویسید. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالا-چپ شکل، اندازه‌گیری‌شده بر حسب نقطه، را تنظیم می‌کند. **float** را بنویسید. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالا-چپ شکل، اندازه‌گیری‌شده بر حسب نقطه، را تنظیم می‌کند. **float** را بنویسید. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | تصویر برای شیء زوم را تنظیم می‌کند. [IPPImage](../ippimage/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به‌عنوان اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌آورد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای رفع قفل دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را می‌نویسد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [SectionZoomFrame](../sectionzoomframe/)
* کلاس [ISummaryZoomSection](../isummaryzoomsection/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)