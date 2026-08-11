---
title: IGroupShape
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک گروه از اشکال روی اسلاید است.
type: docs
weight: 2484
url: /fa/aspose.slides/igroupshape/
---
## کلاس IGroupShape

نمایانگر یک گروه از اشکال روی اسلاید است.

```cpp
class IGroupShape : public virtual Aspose::Slides::IShape
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | اگر placeholder وجود نداشته باشد یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | خاصیت مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود. خواندن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال بر روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) را که شامل اثرات پیکسل اعمال شده بر شکل است برمی‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است برمی‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | خصوصیات قاب شکل را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGroupShapeLock](../igroupshapelock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را بر حسب نقطه (points) می‌گیرد. خواندن **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند آیا شکل مخفی است یا نه. خواندن **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | لینک‌های تعریف‌شده برای کلیک ماوس را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر لینک‌ها. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | لینک‌های تعریف‌شده برای عبور ماوس را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه 'Mark as decorative' را می‌گیرد. خواندن/نوشتن **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند آیا شکل در گروه‌بندی است یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند آیا شکل TextHolder است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | یک شناساگر منحصر به‌سرداسلاید که در طول زندگی شکل ثابت می‌ماند و به PowerPoint یا کد interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای از سند می‌دهد را برمی‌گرداند. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](./)\> [get_ParentGroup](../ishape/get_parentgroup/)() | اگر شکل در گروه باشد، شیء والد [GroupShape](../groupshape/) را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | placeholder برای یک شکل را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه (presentation) را برمی‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | خصوصیات چارچوب خام شکل را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش ضد ساعت‌گرد است. خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | یک شکل داخل گروه در ایندکس مشخص‌شده را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | مجموعه‌ای از اشکال داخل گروه را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../ishapecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | یک شناساگر داخلی که به‌صورت scoped برای ارائه است و برای استفاده افزونه‌ها یا کدهای دیگر در نظر گرفته شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازنویسی شود، نباید به‌عنوان کلید یکتا ثابت در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را بر حسب نقطه (points) می‌گیرد. خواندن **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مقدار x مختصات گوشه بالای چپ شکل را بر حسب نقطه می‌گیرد. خواندن **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مقدار y مختصات گوشه بالای چپ شکل را بر حسب نقطه می‌گیرد. خواندن **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای عقب ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل placeholder پایه (شکل از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده شده است) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شئ را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر کوچک شکل را برمی‌گرداند. نوع محدوده تصویر کوچک [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌طور پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شئ را می‌گیرد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شئ نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل placeholder نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | خاصیت مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات قاب شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را بر حسب نقطه تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند آیا شکل مخفی است یا نه. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | لینک تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | لینک تعریف‌شده برای عبور ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | خصوصیات چارچوب خام شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش ضد ساعت‌گرد است. نوشتن **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را بر حسب نقطه تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مقدار x مختصات گوشه بالای چپ شکل را بر حسب نقطه تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مقدار y مختصات گوشه بالای چپ شکل را بر حسب نقطه تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تعویض pointerها در کانتینرها به حالت weak را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع weak را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع weak را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IShape](../ishape/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)