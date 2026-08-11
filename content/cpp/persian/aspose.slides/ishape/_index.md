---
title: IShape
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک شکل در اسلاید است.
type: docs
weight: 3641
url: /fa/aspose.slides/ishape/
---
## IShape کلاس

نمایانگر یک شکل در اسلاید است.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر وجود نداشته باشد یک نگهدارندهٔ جدید اضافه می‌کند و خصوصیات نگهدارنده را به مقدار مشخص تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از مفهوم C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | خاصیت مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر شود. خواند [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | تعداد نقاط اتصال در شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | [EffectFormat](../effectformat/) شیء‌ای را که اثرات پیکسلی اعمال شده بر شکل را شامل می‌شود برمی‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | [FillFormat](../fillformat/) شیء‌ای را که خصوصیات قالب‌بندی پر کردن برای یک شکل را شامل می‌شود برمی‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | خصوصیات فریم شکل را برمی‌گرداند. خواند [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](./get_height/)() | ارتفاع شکل را که به پوینت اندازه‌گیری می‌شود به دست می‌آورد. خواند **float**. |
| virtual **bool** [get_Hidden](./get_hidden/)() | مشخص می‌کند آیا شکل مخفی است یا خیر. خواند **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوند فرامی‌گردان تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواند [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوند فرامی‌گردان تعریف‌شده برای حرکت ماوس بالای شی را برمی‌گرداند. خواند [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | گزینهٔ «Mark as decorative» را به دست می‌آورد. خواند/نوشت **bool**. |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | مشخص می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | مشخص می‌کند آیا شکل TextHolder است یا خیر. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | [LineFormat](../lineformat/) شیء‌ای را که خصوصیات قالب‌بندی خط برای یک شکل را شامل می‌شود برمی‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | نام یک شکل را برمی‌گرداند. خواند [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | یک شناسهٔ یکتا scoped به اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع مطمئن به شکل از هر نقطه‌ای در سند را می‌دهد. فقط-خواندنی **uint32_t**. همچنین به [IShape::get_UniqueId](./get_uniqueid/) مراجعه کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | اگر شکل گروه‌بندی شده باشد شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | نگهدارندهٔ یک شکل را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | خصوصیات فریم خام شکل را برمی‌گرداند. خواند [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](./get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را برمی‌گرداند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. خواند **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | [ThreeDFormat](../threedformat/) شیء‌ای را که خصوصیات قالب‌بندی خط برای یک شکل را شامل می‌شود برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | یک شناسهٔ داخلی scoped به ارائه را برمی‌گرداند که برای استفاده توسط افزودنی‌ها یا کدهای دیگر منظور شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتخصیص یابد، نباید به عنوان کلید یکتا دائمی در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین به [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/) مراجعه کنید. |
| virtual **float** [get_Width](./get_width/)() | عرض شکل را که به پوینت اندازه‌گیری می‌شود به دست می‌آورد. خواند **float**. |
| virtual **float** [get_X](./get_x/)() | مختصات x گوشهٔ بالایی-چپ شکل را که به پوینت اندازه‌گیری می‌شود به دست می‌آورد. خواند **float**. |
| virtual **float** [get_Y](./get_y/)() | مختصات y گوشهٔ بالایی-چپ شکل را که به پوینت اندازه‌گیری می‌شود به دست می‌آورد. خواند **float**. |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوترین موقعیت ترتیب z را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | یک شکل نگهدارندهٔ پایه‌ای (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل جاری از آن وراثت می‌گیرد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را به دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع حدود تصویر بندانگشتی [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با استفاده از عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر پایهٔ مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای موارد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراکی را با مقدار مشخص کاهش می‌دهد. |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | تعریف می‌کند که این شکل یک نگهدارنده نیست. |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | خاصیت مشخص می‌کند که یک شکل در حالت نمایش سیاه-سفید چگونه رندر شود. نوشت [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات فریم شکل را تنظیم می‌کند. نوشت [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](./set_height/)(**float**) | ارتفاع شکل را که به پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | مشخص می‌کند آیا شکل مخفی است یا خیر. نوشت **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند فرامی‌گردان تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشت [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند فرامی‌گردان تعریف‌شده برای عبور ماوس را تنظیم می‌کند. نوشت [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | گزینهٔ «Mark as decorative» را تنظیم می‌کند. خواند/نوشت **bool**. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشت [System::String](../../system/string/). |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات فریم خام شکل را تنظیم می‌کند. نوشت [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](./set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. نوشت **float**. |
| virtual void [set_Width](./set_width/)(**float**) | عرض شکل را که به پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_X](./set_x/)(**float**) | مختصات x گوشهٔ بالایی-چپ شکل را که به پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [set_Y](./set_y/)(**float**) | مختصات y گوشهٔ بالایی-چپ شکل را که به پوینت اندازه‌گیری می‌شود تنظیم می‌کند. نوشت **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با استفاده از عبارت C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ISlideComponent](../islidecomponent/)
* کلاس [IHyperlinkContainer](../ihyperlinkcontainer/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)