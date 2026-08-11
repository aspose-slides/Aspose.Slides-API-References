---
title: ITable
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک جدول بر روی اسلاید است.
type: docs
weight: 4018
url: /fa/aspose.slides/itable/
---
## کلاس ITable

نمایانگر یک جدول بر روی اسلاید است.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## متدها

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | در صورتی که placeholder وجود نداشته باشد یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص‌شده تنظیم می‌گردد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را بر می‌گرداند. مطالعه [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند. مطالعه [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه و سفید چگونه رندر شود. مطالعه [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | ستونی در ایندکس مشخص بر می‌گرداند. فقط-خواندنی [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | مجموعه‌ای از ستون‌ها را بر می‌گرداند. فقط-خواندنی [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را بر می‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | داده‌های سفارشی شکل را بر می‌گرداند. فقط-خواندنی [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | شیء [EffectFormat](../effectformat/) را که شامل افکت‌های پیکسلی اعمال شده بر شکل است بر می‌گرداند. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | شیء [FillFormat](../fillformat/) را که شامل ویژگی‌های قالب‌بندی پرکننده برای شکل است بر می‌گرداند. فقط-خواندنی [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | تعیین می‌کند آیا ستون اول جدول باید با قالب‌بندی خاص رسم شود. خواندنی **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | تعیین می‌کند آیا ردیف اول جدول باید با قالب‌بندی خاص رسم شود. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ویژگی‌های فریم شکل را بر می‌گرداند. مطالعه [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود به دست می‌آورد. خواندنی **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | تعیین می‌کند آیا شکل مخفی است. خواندنی **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | هایپرلینک تعریف‌شده برای کلیک ماوس را بر می‌گرداند. مطالعه [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر هایپرلینک‌ها. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | هایپرلینک تعریف‌شده برای حرکت ماوس را بر می‌گرداند. مطالعه [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | گزینه «علامت به‌عنوان تزئینی» را به‌دست می‌آورد. خواندنی/نوشتنی **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | تعیین می‌کند آیا شکل گروه‌بندی شده است. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | تعیین می‌کند آیا شکل TextHolder است. فقط-خواندنی **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی خاص رسم شود. خواندنی **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | تعیین می‌کند آیا ردیف آخر جدول باید با قالب‌بندی خاص رسم شود. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بر می‌گرداند. فقط-خواندنی [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | نام یک شکل را بر می‌گرداند. مطالعه [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | شناسه منحصربه‌فردی scoped به اسلاید را بر می‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع مطمئن به شکل از هر نقطه‌ای در سند را می‌دهد. فقط-خواندنی **uint32_t**. برای جزئیات بیشتر به [IShape::get_UniqueId](../ishape/get_uniqueid/) مراجعه کنید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | شیء والد [GroupShape](../groupshape/) را اگر شکل گروه‌بندی شده باشد بر می‌گرداند. در غیراینصورت null بر می‌گرداند. فقط-خواندنی [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | placeholder برای یک شکل را بر می‌گرداند. فقط-خواندنی [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ارائه را بر می‌گرداند. فقط-خواندنی [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ویژگی‌های فریم خام شکل را بر می‌گرداند. مطالعه [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | تعیین می‌کند آیا جدول ترتیب خواندن راست به چپ دارد. خواندنی **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را بر می‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | ردیفی در ایندکس مشخص بر می‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | مجموعه‌ای از ردیف‌ها را بر می‌گرداند. فقط-خواندنی [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | اسلاید پایه را بر می‌گرداند. فقط-خواندنی [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | سبک جدول پیش‌ساخته را به‌دست می‌آورد یا تنظیم می‌کند. مطالعه [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | شیء [TableFormat](../tableformat/) را که شامل ویژگی‌های قالب‌بندی برای این جدول است بر می‌گرداند. فقط-خواندنی [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | شیء [ThreeDFormat](../threedformat/) را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است بر می‌گرداند. فقط-خواندنی [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | شناسه داخلی scoped به ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است بر می‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه دوباره اختصاص یابد، نباید به‌عنوان کلید منحصربه‌فرد پایدار محسوب شود. فقط-خواندنی **uint32_t**. برای جزئیات بیشتر به [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) مراجعه کنید. |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندنی **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود به دست می‌آورد. خواندنی **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | مختصات x گوشه سمت چپ-بالای شکل را که بر حسب نقاط اندازه‌گیری می‌شود به دست می‌آورد. خواندنی **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | مختصات y گوشه سمت چپ-بالای شکل را که بر حسب نقاط اندازه‌گیری می‌شود به دست می‌آورد. خواندنی **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در پشت ترتیب z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب z برمی‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | یک شکل placeholder پایه (شکل از لایه و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد) را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را به‌دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فعال می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | تصویر کوچک شکل را برمی‌گرداند. نوع bounds تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به‌دست می‌آورد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | سلول در ایندکس‌های ستون و ردیف مشخص را بر می‌گرداند. فقط-خواندنی [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# «is». |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان C# lock() را انجام می‌دهد. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | سلول‌های همسایه را ادغام می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را با مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | تعریف می‌کند که این شکل placeholder نیست. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | ویژگی مشخص می‌کند شکل در حالت نمایش سیاه و سفید چگونه رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | تعیین می‌کند آیا ستون اول جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | تعیین می‌کند آیا ردیف اول جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | تعیین می‌کند آیا شکل مخفی است. نوشتن **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. نوشتن **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | هایپرلینک تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | هایپرلینک تعریف‌شده برای حرکت ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | گزینه «علامت به‌عنوان تزئینی» را تنظیم می‌کند. نوشتن/خواندن **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | تعیین می‌کند آیا ردیف آخر جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ویژگی‌های فریم خام شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | تعیین می‌کند آیا جدول ترتیب خواندن راست به چپ دارد. نوشتن **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | تعداد درجه‌های چرخش شکل مشخص‌شده حول محور z را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. نوشتن **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | سبک جدول پیش‌ساخته را به‌دست می‌آورد یا تنظیم می‌کند. نوشتن [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. نوشتن **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | مختصات x گوشه سمت چپ-بالای شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | مختصات y گوشه سمت چپ-بالای شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n-ام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | ویژگی‌های فرمت بخش تعریف‌شده را برای تمام بخش‌های عنصر تنظیم می‌کند. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | ویژگی‌های فرمت پاراگراف تعریف‌شده را برای تمام پاراگراف‌های عنصر تنظیم می‌کند. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | ویژگی‌های فرمت فریم متنی تعریف‌شده را برای تمام فریم‌های متنی عنصر تنظیم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را به‌دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از Smart Pointer‌ها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از Smart Pointer‌ها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)) را انجام می‌دهد. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی قفل‌گذاری بیان C# lock() را برای باز کردن قفل انجام می‌دهد. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از Smart Pointer‌ها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از Smart Pointer‌ها یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتوای [Shape](../shape/) را به عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IGraphicalObject](../igraphicalobject/)
* کلاس [IBulkTextFormattable](../ibulktextformattable/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)