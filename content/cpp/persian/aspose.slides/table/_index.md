---
title: Table
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر یک جدول روی اسلاید.
type: docs
weight: 5409
url: /fa/aspose.slides/table/
---
## کلاس Table

نمایش یک جدول روی اسلاید.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | اگر placeholder ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌سازد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند؛ در این حالت دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند؛ در این حالت دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | خاصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. خواندن [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | ستونی را در اندیس مشخص شده برمی‌گرداند. فقط‌خواندنی [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | مجموعهٔ ستون‌ها را برمی‌گرداند. فقط‌خواندنی [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | دادهٔ سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | شیء [EffectFormat](../effectformat/) را که شامل افکت‌های پیکسلی اعمال شده به یک شکل است برمی‌گرداند. توجه: می‌تواند برای برخی انواع شکل‌ها که ویژگی افکت ندارند، مقدار null برگرداند. فقط‌خواندنی [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | شیء [TableFormat::get_FillFormat](../tableformat/get_fillformat/) که قالب‌بندی پر کردن برای [Table](./) را شامل می‌شود برمی‌گرداند. فقط‌خواندنی [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | تعیین می‌کند آیا ستون اول جدول باید با قالب‌بندی خاص رسم شود. خواندن **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | تعیین می‌کند آیا ردیف اول جدول باید با قالب‌بندی خاص رسم شود. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | ارتفاع شکل را به واحد نقطه می‌گیرد. خواندن **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | تعیین می‌کند آیا شکل مخفی است. خواندن **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | هایپرلینک تعریف‌شده برای کلیک موس را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | مدیر هایپرلینک را برمی‌گرداند. فقط‌خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | هایپرلینک تعریف‌شده برای حرکت موس بر فراز را برمی‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | گزینه «Mark as decorative» را دریافت می‌کند. خواندنی/نوشتنی **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | تعیین می‌کند آیا شکل گروه‌بندی شده است. فقط‌خواندنی **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | تعیین می‌کند آیا شکل TextHolder_PPT است. فقط‌خواندنی **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی خاص رسم شود. خواندن **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | تعیین می‌کند آیا ردیف آخر جدول باید با قالب‌بندی خاص رسم شود. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | شیء [LineFormat](../lineformat/) را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است برمی‌گرداند. توجه: ممکن است برای برخی انواع شکل‌هایی که ویژگی خط ندارند، null برگرداند. فقط‌خواندنی [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | نام یک شکل را برمی‌گرداند. نباید null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. خواندن [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | شناسهٔ یکتا با حوزه اسلاید را برمی‌گرداند که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هر جایی در سند می‌دهد. فقط‌خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | شیء والد [GroupShape](../groupshape/) را برمی‌گرداند اگر شکل گروه‌بندی شده باشد. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | placeholder شکل را برمی‌گرداند. اگر شکل placeholder نداشته باشد، null برمی‌گرداند. فقط‌خواندنی [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ارائهٔ والد اسلاید را برمی‌گرداند. فقط‌خواندنی [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ویژگی‌های فریم شکل خام را برمی‌گرداند. خواندن [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | تعیین می‌کند آیا جدول جهت خواندن راست به چپ دارد. خواندن **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند. مقدار مثبت نشانگر چرخش ساعتگرد است؛ مقدار منفی نشانگر چرخش پادساعتگرد. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | ردیفی را در اندیس مشخص شده برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | مجموعهٔ ردیف‌ها را برمی‌گرداند. فقط‌خواندنی [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | اسلاید والد شکل را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | سبک جدول پیش‌ساخته را دریافت می‌کند. خواندن [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | شیء [TableFormat](../tableformat/) را که شامل ویژگی‌های قالب‌بندی برای این جدول است برمی‌گرداند. فقط‌خواندنی [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | شیء [ThreeDFormat](../threedformat/) را که ویژگی‌های اثر 3D برای یک شکل است برمی‌گرداند. توجه: ممکن است برای برخی شکل‌هایی که ویژگی 3D ندارند، null برگرداند. فقط‌خواندنی [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | شناسهٔ داخلی با حوزه ارائه که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی تغییر یابد، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. فقط‌خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. خواندن **bool**. |
| **float** [get_Width](../shape/get_width/)() override | عرض شکل را به نقطه می‌گیرد. خواندن **float**. |
| **float** [get_X](../shape/get_x/)() override | مختصات x گوشهٔ بالا-چپ شکل را به نقطه می‌گیرد. خواندن **float**. |
| **float** [get_Y](../shape/get_y/)() override | مختصات y گوشهٔ بالا-چپ شکل را به نقطه می‌گیرد. خواندن **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در انتهای z-order را برمی‌گرداند و Shapes[Count - 1] شکل در جلوی z-order را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | یک شکل placeholder پایه را برمی‌گرداند (شکلی از قالب و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری شده است). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌سازد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | تصویر کوچک شکل را برمی‌گرداند. نوع محدودهٔ تصویر کوچک شکل [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) به‌طور پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | تصویر کوچک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | مرزهای بصری شکل را که از محتوی رندر شده محاسبه شده است دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | سلولی را در اندیس‌های ستون و ردیف مشخص شده برمی‌گرداند. فقط‌خواندنی [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | عملکرد قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را می‌دهد. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | سلول‌های همسایه را ادغام می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از کلاس‌های مشتق را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را برحسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌وار شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص شده کاهش می‌دهد. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | مشخص می‌کند این شکل placeholder نیست. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | خاصیت مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | تعیین می‌کند آیا ستون اول جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | تعیین می‌کند آیا ردیف اول جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ارتفاع شکل را که به نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | تعیین می‌کند آیا شکل مخفی است. نوشتن **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | تعیین می‌کند آیا ردیف‌های زوج باید با قالب‌بندی متفاوت رسم شوند. نوشتن **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینک تعریف‌شده برای کلیک موس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | هایپرلینک تعریف‌شده برای حرکت موس بر فراز را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | گزینه «Mark as decorative» را تنظیم می‌کند. خواندنی/نوشتنی **bool**. |
| void [set_LastCol](./set_lastcol/)(**bool**) override | تعیین می‌کند آیا ستون آخر جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | تعیین می‌کند آیا ردیف آخر جدول باید با قالب‌بندی خاص رسم شود. نوشتن **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ویژگی‌های فریم شکل خام را تنظیم می‌کند. نوشتن [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | تعیین می‌کند آیا جدول جهت خواندن راست به چپ دارد. نوشتن **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد است؛ مقدار منفی نشانگر چرخش پاد ساعتگرد. نوشتن **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | سبک جدول پیش‌ساخته را تنظیم می‌کند. نوشتن [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | تعیین می‌کند آیا ستون‌های زوج باید با قالب‌بندی متفاوت رسم شوند. نوشتن **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | عرض شکل را که به نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../shape/set_x/)(**float**) override | مختصات x گوشهٔ بالا-چپ شکل را که به نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | مختصات y گوشهٔ بالا-چپ شکل را که به نقطه اندازه‌گیری می‌شود تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک پوینتر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را می‌دهد. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | ویژگی‌های قالب‌بندی قسمت تعریف‌شده را برای تمام قسمت‌های سلول‌های جدول تنظیم می‌کند. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده را برای تمام پاراگراف‌های سلول‌های جدول تنظیم می‌کند. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | ویژگی‌های قالب‌بندی فریم متن تعریف‌شده را برای تمام فریم‌های متن سلول‌های جدول تنظیم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را می‌دهد. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را باز می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## مراجع

* کلاس [GraphicalObject](../graphicalobject/)
* کلاس [ITable](../itable/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)