---
title: Chart
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 53
url: /fa/aspose.slides.charts/chart/
---
## Chart کلاس

یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.

```cpp
class Chart : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::Charts::IChart
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | اگر وجود نداشته باشد یک جای‌گیر جدید اضافه می‌کند و ویژگی‌های جای‌گیر را به مقدار مشخص‌شده تنظیم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | یک تم مؤثر برای این نمودار را برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() override | دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [IAxesManager](../iaxesmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() override | یک شیء که امکان تغییر قالب دیوار پشت یک نمودار سه‌بعدی را می‌دهد. فقط-خواندنی [IChartWall](../ichartwall/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | خواص تعیین می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() override | اطلاعات در مورد داده‌های مرتبط یا جاسازی‌شده با یک نمودار را برمی‌گرداند. فقط-خواندنی [IChartData](../ichartdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() override | جدول داده‌ای یک نمودار را برمی‌گرداند. فقط-خواندنی [IDataTable](../idatatable/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() override | عنوان نمودار را برمی‌گرداند. فقط-خواندنی [IChartTitle](../icharttitle/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | داده سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() override | روش رسم سلول‌های خالی در یک نمودار را برمی‌گرداند. خواندن [DisplayBlanksAsType](../displayblanksastype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | شیء [EffectFormat](../../aspose.slides/effectformat/) که شامل افکت‌های پیکسلی اعمال‌شده بر یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند ممکن است مقدار null بازگرداند. فقط-خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | شیء [FillFormat](../../aspose.slides/fillformat/) که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است مقدار null بازگرداند. فقط-خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() override | یک شیء که امکان تغییر قالب کف یک نمودار سه‌بعدی را می‌دهد را برمی‌گرداند. فقط-خواندنی [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | ویژگی‌های فریم شکل را برمی‌گرداند. خواندن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **bool** [get_HasDataTable](./get_hasdatatable/)() override | تعیین می‌کند آیا یک نمودار جدول داده دارد یا خیر. خواندن **bool**. |
| **bool** [get_HasLegend](./get_haslegend/)() override | تعیین می‌کند آیا نمودار دارای لِجند است یا خیر. خواندن **bool**. |
| **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() override | مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. خواندن **bool**. |
| **bool** [get_HasTitle](./get_hastitle/)() override | تعیین می‌کند آیا عنوان نمودار قابل مشاهده است یا خیر. خواندن **bool**. |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | ارتفاع شکل را برحسب نقطه می‌گیرد. خواندن **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | تعیین می‌کند آیا شکل پنهان است یا خیر. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | پیوندی که برای کلیک موس تعریف شده را برمی‌گرداند. خواندن [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | مدیر پیوندها را برمی‌گرداند. فقط-خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | پیوندی که برای حرکت موس فوق تعریف شده را برمی‌گرداند. خواندن [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | گزینه 'Mark as decorative' را دریافت می‌کند. خواندن/نوشتن **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | تعیین می‌کند آیا شکل گروه‌بندی شده است یا خیر. فقط-خواندنی **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | تعیین می‌کند آیا شکل TextHolder_PPT است یا خیر. فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() override | لِجند برای یک نمودار را برمی‌گرداند. فقط-خواندنی [ILegend](../ilegend/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | شیء [LineFormat](../../aspose.slides/lineformat/) که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null بازگرداند. فقط-خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | نام یک شکل را برمی‌گرداند. نباید مقدار null باشد. در صورت نیاز از رشته خالی استفاده کنید. خواندن [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | یک شناسه یکتا scoped به اسلاید را برمی‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد به‌طور قابل اطمینان از هر نقطه‌ای از سند به شکل ارجاع دهد. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | اگر شکل گروه‌بندی شده باشد شیء والد [GroupShape](../../aspose.slides/groupshape/) را برمی‌گرداند. در غیر این صورت null را برمی‌گرداند. فقط-خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | جای‌گیر برای یک شکل را برمی‌گرداند. اگر شکل جای‌گیر نداشته باشد null را برمی‌گرداند. فقط-خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() override | ناحیه ترسیم یک نمودار را نشان می‌دهد. فقط-خواندنی [IChartPlotArea](../ichartplotarea/). |
| **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() override | تعیین می‌کند آیا فقط سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی false باشد. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | ارائه مادر یک اسلاید را برمی‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | ویژگی‌های فریم خام شکل را برمی‌گرداند. خواندن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را برمی‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() override | چرخش سه‌بعدی یک نمودار را برمی‌گرداند. فقط-خواندنی [IRotation3D](../irotation3d/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() override | مشخص می‌کند برچسب‌های داده‌ای بیش از حداکثر نمودار نمایش داده شوند. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() override | یک شیء که امکان تغییر قالب دیوار جانبی یک نمودار سه‌بعدی را می‌دهد را برمی‌گرداند. فقط-خواندنی [IChartWall](../ichartwall/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | اسلاید والد یک شکل را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [StyleType](../styletype/) [get_Style](./get_style/)() override | سبک نمودار را برمی‌گرداند. خواندن [StyleType](../styletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن نمودار را برمی‌گرداند. این ویژگی برای انواع زیر قابل اعمال نیست: [ChartType::Treemap](../charttype/), [ChartType::Sunburst](../charttype/), [ChartType::Waterfall](../charttype/), [ChartType::Histogram](../charttype/), [ChartType::Funnel](../charttype/),[ChartType::BoxAndWhisker](../charttype/). فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | مدیر تم را برمی‌گرداند. فقط-خواندنی [Aspose::Slides::Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | شیء [ThreeDFormat](../../aspose.slides/threedformat/) که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند. نکته: برای برخی انواع شکل‌ها که ویژگی 3d ندارند ممکن است مقدار null بازگرداند. فقط-خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | نوع نمودار را برمی‌گرداند. خواندن [ChartType](../charttype/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | یک شناسه داخلی scoped به ارائه که برای استفاده توسط افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است را برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتخصیص شود، نباید به عنوان کلید یکتا پایدار در نظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() override | اشکال کشیده‌شده بر روی نمودار را مشخص می‌کند. فقط-خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | عرض شکل را برحسب نقطه می‌گیرد. خواندن **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | مختصات x گوشه بالایی-چپ شکل را برحسب نقطه می‌گیرد. خواندن **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | مختصات y گوشه بالایی-چپ شکل را برحسب نقطه می‌گیرد. خواندن **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل پشتتر در ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلویتر را برمی‌گرداند. فقط-خواندنی **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | یک شکل جای‌گیر پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث می‌برد). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | نمادک شکل را برمی‌گرداند. نوع محدوده نمادک شکل [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) به‌طور پیش‌فرض استفاده می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | نمادک شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | حدود بصری شکل را که از محتوای رندر شده محاسبه می‌شود، می‌گیرد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت کپی ساخته شوند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت کپی ساخته شوند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | تعریف می‌کند که این شکل یک جای‌گیر نیست. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | خواص تعیین می‌کند شکل چگونه در حالت نمایش سیاه-سفید رندر شود. نوشتن [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) override | روش رسم سلول‌های خالی در یک نمودار را تنظیم می‌کند. نوشتن [DisplayBlanksAsType](../displayblanksastype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های فریم شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_HasDataTable](./set_hasdatatable/)(**bool**) override | تعیین می‌کند آیا یک نمودار جدول داده دارد یا خیر. نوشتن **bool**. |
| void [set_HasLegend](./set_haslegend/)(**bool**) override | تعیین می‌کند آیا یک نمودار لِجند دارد یا خیر. نوشتن **bool**. |
| void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) override | مشخص می‌کند ناحیه نمودار گوشه‌های گرد داشته باشد. نوشتن **bool**. |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | تعیین می‌کند آیا عنوان نمودار قابل مشاهده است یا خیر. نوشتن **bool**. |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ارتفاع شکل را برحسب نقطه تنظیم می‌کند. نوشتن **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | تعیین می‌کند آیا شکل پنهان است یا خیر. نوشتن **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند تعریف‌شده برای کلیک موس را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | پیوند تعریف‌شده برای حرکت موس فوق را تنظیم می‌کند. نوشتن [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | نام یک شکل را تنظیم می‌کند. نباید null باشد. در صورت نیاز از رشته خالی استفاده کنید. نوشتن [System::String](../../system/string/). |
| void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) override | تعیین می‌کند آیا فقط سلول‌های قابل مشاهده رسم شوند. برای رسم هم سلول‌های قابل مشاهده و هم مخفی false باشد. نوشتن **bool**. |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ویژگی‌های فریم خام شکل را تنظیم می‌کند. نوشتن [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | تعداد درجاتی که شکل مشخص شده حول محور z چرخیده است را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. نوشتن **float**. |
| void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) override | مشخص می‌کند برچسب‌های داده‌ای بیش از حداکثر نمودار نمایش داده شوند. نوشتن **bool**. |
| void [set_Style](./set_style/)([StyleType](../styletype/)) override | سبک نمودار را تنظیم می‌کند. نوشتن [StyleType](../styletype/). |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | نوع نمودار را تنظیم می‌کند. نوشتن [ChartType](../charttype/). |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | عرض شکل را برحسب نقطه تنظیم می‌کند. نوشتن **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | مختصات x گوشه بالایی-چپ شکل را برحسب نقطه تنظیم می‌کند. نوشتن **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | مختصات y گوشه بالایی-چپ شکل را برحسب نقطه تنظیم می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو n'th را به یک پوینتر ضعیف (به جای Shared) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار جاری شمارنده مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی با دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| void [ValidateChartLayout](./validatechartlayout/)() override | مقدارهای واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط [IActualLayout](../iactuallayout/) را پیاده‌سازی می‌کنند ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) و مقادیر واقعی محورها ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | محتویات [Shape](../../aspose.slides/shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | محتویات [Shape](../../aspose.slides/shape/) را به‌عنوان فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject/)
* کلاس [IChart](../ichart/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)