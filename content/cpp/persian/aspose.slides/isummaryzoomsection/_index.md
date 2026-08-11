---
title: ISummaryZoomSection
second_title: Aspose.Slides برای C++ - مرجع API
description: شیء Summary Zoom Section را در یک فریم Summary Zoom نشان می‌دهد.
type: docs
weight: 3927
url: /fa/aspose.slides/isummaryzoomsection/
---
## ISummaryZoomSection کلاس

یک شیء Summary Zoom [Section](../section/) را در یک فریم Summary Zoom نشان می‌دهد.

```cpp
class ISummaryZoomSection : public virtual Aspose::Slides::ISectionZoomFrame
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر هیچ جایگزین (placeholder) وجود نداشته باشد یک جایگزین جدید اضافه می‌کند و خصوصیات جایگزین را به مقدار مشخص شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌فلوتی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌فلوتی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را بر می‌گرداند. **بخوانید** [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند. **بخوانید** [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | خصوصیت نحوهٔ رندر شدن شکل در حالت نمایش سیاه-سفید را مشخص می‌کند. **بخوانید** [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را بر می‌گرداند. **فقط‌خواندنی** **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | دادهٔ سفارشی شکل را بر می‌گرداند. **فقط‌خواندنی** [ICustomData](../icustomdata/). |
| virtual [System::String](../../system/string/) [get_Description](./get_description/)() | توصیف متنی شیء Summary Zoom [Section](../section/) را بر می‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) که اثرات پیکسل اعمال شده به یک شکل را شامل می‌شود را بر می‌گرداند. **فقط‌خواندنی** [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) که ویژگی‌های قالب‌بندی پر کردن برای یک شکل را شامل می‌شود را بر می‌گرداند. **فقط‌خواندنی** [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | خصوصیات فریم شکل را بر می‌گرداند. **بخوانید** [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را بر می‌گرداند. **فقط‌خواندنی** [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را بر حسب نقطه (points) می‌گیرد. **فقط‌خواندنی** **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند که آیا شکل مخفی است یا خیر. **فقط‌خواندنی** **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوند (hyperlink) تعریف شده برای کلیک ماوس را بر می‌گرداند. **بخوانید** [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها **فقط‌خواندنی** [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوند تعریف شده برای عبور ماوس را بر می‌گرداند. **بخوانید** [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | نوع تصویر شیء زوم را می‌گیرد. **بخوانید** [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینهٔ «علامت‌گذاری به عنوان تزئینی» را می‌گیرد. **خواندنی/نوشتنی** **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. **فقط‌خواندنی** **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند که آیا شکل TextHolder است یا خیر. **فقط‌خواندنی** **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) که ویژگی‌های قالب‌بندی خط برای یک شکل را شامل می‌شود را بر می‌گرداند. **فقط‌خواندنی** [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را بر می‌گرداند. **بخوانید** [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | شناسهٔ یکتا برای اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را به‌طور قابل اطمینان از هرجایی در سند ارجاع دهد. **فقط‌خواندنی** **uint32_t**. **همچنین ببینید** [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | شیء والد [GroupShape](../groupshape/) را اگر شکل گروه‌بندی شده باشد بر می‌گرداند. در غیر اینصورت null بر می‌گرداند. **فقط‌خواندنی** [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | جایگزین (placeholder) برای یک شکل را بر می‌گرداند. **فقط‌خواندنی** [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه (presentation) را بر می‌گرداند. **فقط‌خواندنی** [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | خصوصیات فریم خام شکل را بر می‌گرداند. **بخوانید** [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | رفتار ناوبری در نمایش اسلاید را می‌گیرد. **فقط‌خواندنی** **bool**. مقدار پیش‌فرض: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بر می‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعتگرد است. **فقط‌خواندنی** **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را بر می‌گرداند. **فقط‌خواندنی** [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | مقداری که مشخص می‌کند آیا Zoom پس‌زمینهٔ اسلاید مقصد را استفاده می‌کند یا نه را می‌گیرد. **فقط‌خواندنی** **bool**. مقدار پیش‌فرض: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را بر می‌گرداند. **فقط‌خواندنی** [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../isectionzoomframe/get_targetsection/)() | شیء بخش (section) که شیء Zoom [Section](../section/) به آن لینک دارد را می‌گیرد. **بخوانید** [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) که ویژگی‌های قالب‌بندی خط برای یک شکل را شامل می‌شود را بر می‌گرداند. **فقط‌خواندنی** [IThreeDFormat](../ithreedformat/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | عنوان متنی Summary Zoom [Section](../section/) را بر می‌گرداند. |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | مدت زمان انتقال بین Zoom و اسلاید را می‌گیرد. **فقط‌خواندنی** **float**. مقدار پیش‌فرض: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | شناسه‌ای داخلی، scoped به ارائه، که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازنویسی شود، نباید به عنوان کلید یکتا دائمی رفتار شود. **فقط‌خواندنی** **uint32_t**. **همچنین ببینید** [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را بر حسب نقطه می‌گیرد. **فقط‌خواندنی** **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشهٔ بالایی-چپ شکل را بر حسب نقطه می‌گیرد. **فقط‌خواندنی** **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشهٔ بالایی-چپ شکل را بر حسب نقطه می‌گیرد. **فقط‌خواندنی** **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | تصویر برای شیء زوم را می‌گیرد. **بخوانید** [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در z-order را بر می‌گرداند. Shapes[0] شکل را در پشت z-order باز می‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو z-order باز می‌گرداند. **فقط‌خواندنی** **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل placeholder پایه را بر می‌گرداند (شکل از layout و/یا master اسلاید که شکل جاری از آن ارث می‌برد). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فعال می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر بند انگشتی شکل را بر می‌گرداند. نوع مرز تصویر بند انگشتی [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌طور پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر بند انگشتی شکل را بر می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل متد C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری (lock) C# را انجام می‌دهد. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فعال می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل placeholder نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. **نوشتنی** [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. **نوشتنی** [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | خصوصیت نحوهٔ رندر شدن شکل در حالت نمایش سیاه-سفید را مشخص می‌کند. **نوشتنی** [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Description](./set_description/)([System::String](../../system/string/)) | توصیف متنی Summary Zoom [Section](../section/) را تنظیم می‌کند. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات فریم شکل را تنظیم می‌کند. **نوشتنی** [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را بر حسب نقطه تنظیم می‌کند. **نوشتنی** **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند که آیا شکل مخفی باشد یا نه. **نوشتنی** **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند تعریف شده برای کلیک ماوس را تنظیم می‌کند. **نوشتنی** [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند تعریف شده برای عبور ماوس را تنظیم می‌کند. **نوشتنی** [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | نوع تصویر شیء زوم را تنظیم می‌کند. **نوشتنی** [ZoomImageType](../zoomimagetype/). مقدار پیش‌فرض: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینهٔ «علامت‌گذاری به عنوان تزئینی» را تنظیم می‌کند. **نوشتنی/خواندنی** **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. **نوشتنی** [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات فریم خام شکل را تنظیم می‌کند. **نوشتنی** [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | رفتار ناوبری در نمایش اسلاید را تنظیم می‌کند. **نوشتنی** **bool**. مقدار پیش‌فرض: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعتگرد است. **نوشتنی** **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | مقدار مشخص‌کنندهٔ استفاده از پس‌زمینه اسلاید مقصد توسط Zoom را تنظیم می‌کند. **نوشتنی** **bool**. مقدار پیش‌فرض: true |
| virtual void [set_TargetSection](../isectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | شیء بخش را که شیء Zoom [Section](../section/) به آن لینک دارد تنظیم می‌کند. **نوشتنی** [ISection](../isection/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | عنوان متنی Summary Zoom [Section](../section/) را تنظیم می‌کند. |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | مدت زمان انتقال بین Zoom و اسلاید را تنظیم می‌کند. **نوشتنی** **float**. مقدار پیش‌فرض: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را بر حسب نقطه تنظیم می‌کند. **نوشتنی** **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشهٔ بالایی-چپ شکل را بر حسب نقطه تنظیم می‌کند. **نوشتنی** **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشهٔ بالایی-چپ شکل را بر حسب نقطه تنظیم می‌کند. **نوشتنی** **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | تصویر برای شیء زوم را تنظیم می‌کند. **نوشتنی** [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان سوئچ کردن اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی گشای قفل (unlock) بیان C# lock(). مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ISectionZoomFrame](../isectionzoomframe/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)