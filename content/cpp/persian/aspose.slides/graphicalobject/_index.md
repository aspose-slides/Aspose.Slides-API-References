---
title: GraphicalObject
second_title: Aspose.Slides برای C++ مرجع API
description: نمایندهٔ شیء گرافیکی انتزاعی است.
type: docs
weight: 1171
url: /fa/aspose.slides/graphicalobject/
---
## GraphicalObject کلاس

Represents abstract graphical object.

```cpp
class GraphicalObject : public Aspose::Slides::Shape,
                        public virtual Aspose::Slides::IGraphicalObject
```

## متدها

| متد | شرح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | در صورت عدم وجود یک جای‌پذیر جدید اضافه می‌کند و ویژگی‌های جای‌پذیر را به مقدار مشخص‌شده تنظیم می‌نماید. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. بخوانید [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. بخوانید [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. بخوانید [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) شیئی را که اثرات پیکسلی اعمال‌شده به شکل را شامل می‌شود برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی اثر ندارند مقدار null برگرداند. فقط‌خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) شیئی را که ویژگی‌های قالب‌بندی پر کردن برای یک شکل را شامل می‌شود برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند مقدار null برگرداند. فقط‌خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. بخوانید [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل، بر حسب نقاط، را به دست می‌آورد. فقط‌خواندنی **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | تعیین می‌کند که آیا شکل مخفی است یا خیر. فقط‌خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | هایپرلینکی که برای کلیک ماوس تعریف شده است را برمی‌گرداند. بخوانید [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر هایپرلینک را برمی‌گرداند. فقط‌خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | هایپرلینکی که برای حرکت ماوس تعریف شده است را برمی‌گرداند. بخوانید [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را به دست می‌آورد. خواندنی/نوشتنی **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. فقط‌خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر. فقط‌خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) شیئی را که ویژگی‌های قالب‌بندی خط برای یک شکل را شامل می‌شود برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی خط ندارند مقدار null برگرداند. فقط‌خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. نباید مقدار null باشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. بخوانید [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای از سند می‌دهد. فقط‌خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت مقدار null برمی‌گرداند. فقط‌خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | جای‌پذیر یک شکل را برمی‌گرداند. اگر شکل جای‌پذیری نداشته باشد، مقدار null برمی‌گرداند. فقط‌خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائه مادر یک اسلاید را برمی‌گرداند. فقط‌خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های فریم شکل خام را برمی‌گرداند. بخوانید [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد و مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. فقط‌خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) شیئی را که ویژگی‌های اثر 3D برای یک شکل را شامل می‌شود برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌ها که ویژگی 3D ندارند مقدار null برگرداند. فقط‌خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | یک شناسه داخلی scoped به ارائه را برمی‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس دوباره اختصاص یابد، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. فقط‌خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل، بر حسب نقاط، را به دست می‌آورد. فقط‌خواندنی **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشه فوق‌چپ شکل، بر حسب نقاط، را به دست می‌آورد. فقط‌خواندنی **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشه فوق‌چپ شکل، بر حسب نقاط، را به دست می‌آورد. فقط‌خواندنی **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلو ترتیب z را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل جای‌پذیر پایه را برمی‌گرداند (شکلی از لایه‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث‌بری می‌کند). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری شیءهای سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر کوچک شکل را برمی‌گرداند. نوع محدوده تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌ صورت پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | حدود بصری شکل که از محتوای رندر شده محاسبه می‌شود را به دست می‌آورد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدار [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کلاس‌برداری) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | مشخص می‌کند که این شکل یک جای‌پذیر نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. بنویسید [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. بنویسید [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل، بر حسب نقاط، را تنظیم می‌کند. بنویسید **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | تعیین می‌کند که آیا شکل مخفی است یا خیر. بنویسید **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینکی که برای کلیک ماوس تعریف شده است را تنظیم می‌کند. بنویسید [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینکی که برای حرکت ماوس تعریف شده است را تنظیم می‌کند. بنویسید [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندنی/نوشتنی **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید از رشته خالی استفاده کنید. بنویسید [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل خام را تنظیم می‌کند. بنویسید [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد و مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. بنویسید **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل، بر حسب نقاط، را تنظیم می‌کند. بنویسید **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشه فوق‌چپ شکل، بر حسب نقاط، را تنظیم می‌کند. بنویسید **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشه فوق‌چپ شکل، بر حسب نقاط، را تنظیم می‌کند. بنویسید **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری دستور C# lock() را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدار [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [Shape](../shape/)
* کلاس [IGraphicalObject](../igraphicalobject/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)