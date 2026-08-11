---
title: IChart
second_title: مرجع API Aspose.Slides برای C++
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 573
url: /fa/aspose.slides.charts/ichart/
---
## IChart کلاس

نمایش یک نمودار گرافیکی روی اسلاید.

```cpp
class IChart : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::Charts::IFormattedTextContainer,
               public Aspose::Slides::Theme::IOverrideThemeable
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | اگر نگهدارنده‌ای وجود نداشته باشد یک نگهدارندهٔ جدید اضافه می‌کند و ویژگی‌های نگهدارنده را به مقدار مشخص‌شده تنظیم می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | تم مؤثری برای این شی قابل تم‌گذاری برمی‌گرداند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عددی نقطه‌عشنا به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عددی نقطه‌عشنا به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | متن جایگزین مرتبط با یک شکل را باز می‌گرداند. ببینید [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | عنوان متن جایگزین مرتبط با یک شکل را باز می‌گرداند. ببینید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxesManager](../iaxesmanager/)\> [get_Axes](./get_axes/)() | دسترسی به محورهای نمودار را فراهم می‌کند. فقط-خواندنی [IAxesManager](../iaxesmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_BackWall](./get_backwall/)() | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار پشت یک نمودار سه‌بعدی را می‌دهد. فقط-خواندنی [IChartWall](../ichartwall/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-و-سفید رندر شود. ببینید [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](./)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را باز می‌گرداند. فقط-خواندنی [IChart](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartData](../ichartdata/)\> [get_ChartData](./get_chartdata/)() | اطلاعات دربارهٔ دادهٔ پیوندی یا جاسازی‌شده مرتبط با یک نمودار را باز می‌گرداند. فقط-خواندنی [IChartData](../ichartdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataTable](../idatatable/)\> [get_ChartDataTable](./get_chartdatatable/)() | جدول داده‌های یک نمودار را باز می‌گرداند. فقط-خواندنی [IDataTable](../idatatable/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_ChartTitle](./get_charttitle/)() | عنوان نمودار را باز می‌گرداند. فقط-خواندنی [IChartTitle](../icharttitle/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | تعداد نقاط اتصال روی شکل را باز می‌گرداند. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | دادهٔ سفارشی شکل را باز می‌گرداند. فقط-خواندنی [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [DisplayBlanksAsType](../displayblanksastype/) [get_DisplayBlanksAs](./get_displayblanksas/)() | روش ترسیم سلول‌های خالی روی یک نمودار را باز می‌گرداند. ببینید [DisplayBlanksAsType](../displayblanksastype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | شیٔ [EffectFormat](../../aspose.slides/effectformat/) را که شامل اثرات پیکسلی اعمال‌شده بر یک شکل است، باز می‌گرداند. فقط-خواندنی [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | شیٔ [FillFormat](../../aspose.slides/fillformat/) را که شامل ویژگی‌های قالب‌بندی پر شدن برای یک شکل است، باز می‌گرداند. فقط-خواندنی [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_Floor](./get_floor/)() | شیئی را که امکان تغییر قالب کف یک نمودار سه‌بعدی را می‌دهد، باز می‌گرداند. فقط-خواندنی [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | ویژگی‌های چارچوب شکل را باز می‌گرداند. ببینید [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | قفل‌های شکل را باز می‌گرداند. فقط-خواندنی [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **bool** [get_HasDataTable](./get_hasdatatable/)() | تعیین می‌کند که آیا نمودار جدول داده دارد یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_HasLegend](./get_haslegend/)() | تعیین می‌کند که آیا نمودار افسانه (legend) دارد یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_HasRoundedCorners](./get_hasroundedcorners/)() | مشخص می‌کند که ناحیهٔ نمودار گوشه‌های گرد داشته باشد. فقط-خواندنی **bool**. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | تعیین می‌کند که آیا عنوان نمودار قابل مشاهده است یا نه. فقط-خواندنی **bool**. |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود باز می‌گرداند. فقط-خواندنی **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | تعیین می‌کند که آیا شکل مخفی است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهای تعریف‌شده برای کلیک موس را باز می‌گرداند. ببینید [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها. فقط-خواندنی [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندهای تعریف‌شده برای حرکت ماوس فوق را باز می‌گرداند. ببینید [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | گزینه «Mark as decorative» را دریافت می‌کند. خواندن/نوشتن **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا نه. فقط-خواندنی **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | تعیین می‌کند که آیا شکل TextHolder است یا نه. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegend](../ilegend/)\> [get_Legend](./get_legend/)() | یک افسانه (legend) برای نمودار را باز می‌گرداند. فقط-خواندنی [ILegend](../ilegend/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | شیٔ [LineFormat](../../aspose.slides/lineformat/) را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است، باز می‌گرداند. فقط-خواندنی [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | نام یک شکل را باز می‌گرداند. ببینید [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | شناسهٔ یکتا در محدودهٔ اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد که به‌صورت قابل اطمینان از هرجای سند به شکل ارجاع دهند. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | اگر شکل گروه‌بندی شده باشد، شیٔ والد [GroupShape](../../aspose.slides/groupshape/) را باز می‌گرداند؛ در غیر این‌صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | نگهدارندهٔ یک شکل را باز می‌گرداند. فقط-خواندنی [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartPlotArea](../ichartplotarea/)\> [get_PlotArea](./get_plotarea/)() | منطقهٔ نمودار (plot area) را نشان می‌دهد. فقط-خواندنی [IChartPlotArea](../ichartplotarea/). |
| virtual **bool** [get_PlotVisibleCellsOnly](./get_plotvisiblecellsonly/)() | تعیین می‌کند که فقط سلول‌های قابل مشاهده ترسیم شوند. برای ترسیم هم سلول‌های قابل مشاهده و هم مخفی مقدار False است. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه (presentation) را باز می‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | ویژگی‌های خام چارچوب شکل را باز می‌گرداند. ببینید [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | تعداد درجاتی که شکل مشخص شده دور محور z می‌چرخد را باز می‌گرداند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRotation3D](../irotation3d/)\> [get_Rotation3D](./get_rotation3d/)() | چرخش سه‌بعدی یک نمودار را باز می‌گرداند. فقط-خواندنی [IRotation3D](../irotation3d/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | قفل‌های شکل را باز می‌گرداند. فقط-خواندنی [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual **bool** [get_ShowDataLabelsOverMaximum](./get_showdatalabelsovermaximum/)() | مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نمایش داده شوند. فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartWall](../ichartwall/)\> [get_SideWall](./get_sidewall/)() | شیئی را که امکان تغییر قالب دیوار جانبی یک نمودار سه‌بعدی را می‌دهد، باز می‌گرداند. فقط-خواندنی [IChartWall](../ichartwall/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را باز می‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [StyleType](../styletype/) [get_Style](./get_style/)() | سبک نمودار را باز می‌گرداند. ببینید [StyleType](../styletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را باز می‌گرداند. فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | مدیر تم‌جایگزین (override) را باز می‌گرداند. فقط-خواندنی [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | شیٔ [ThreeDFormat](../../aspose.slides/threedformat/) را که شامل ویژگی‌های قالب‌بندی خطوط برای یک شکل است، باز می‌گرداند. فقط-خواندنی [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | نوع نمودار را باز می‌گرداند. ببینید [ChartType](../charttype/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | شناسهٔ داخلی در محدودهٔ ارائه‌ای که برای استفادهٔ افزونه‌ها یا کدهای دیگر منظور شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازتعین شود، نباید به‌عنوان کلید یکتا دائمی درنظر گرفته شود. فقط-خواندنی **uint32_t**. همچنین ببینید [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_UserShapes](./get_usershapes/)() | مشخص می‌کند که اشکال در بالای نمودار رسم شوند. فقط-خواندنی [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود باز می‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود باز می‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود باز می‌گرداند. فقط-خواندنی **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | موقعیت یک شکل در ترتیب z را باز می‌گرداند. Shapes[0] شکل انتهایی ترتیب را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل جلوی ترتیب را. فقط-خواندنی **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | یک شکل نگهدارندهٔ پایه‌ای (شکل از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث می‌برد) را باز می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. هش‌کردن اشیا سفارشی را ممکن می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | تصویر بند انگشتی شکل را برمی‌گرداند. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) نوع مرزهای تصویر بند انگشتی شکل به‌صورت پیش‌فرض استفاده می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | تصویر بند انگشتی شکل را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمایندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل اپراتور C# 'is' است. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری عبارت C# lock() را انجام می‌دهد. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان شبیه‌سازی (clone) انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ویژۀ خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ویژۀ خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | تعریف می‌کند که این شکل نگهدارنده نیست. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | عنوان متن جایگزین مرتبط با یک شکل را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-و-سفید رندر شود. بنویسید [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_DisplayBlanksAs](./set_displayblanksas/)([DisplayBlanksAsType](../displayblanksastype/)) | روش ترسیم سلول‌های خالی روی یک نمودار را تنظیم می‌کند. بنویسید [DisplayBlanksAsType](../displayblanksastype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ویژگی‌های چارچوب شکل را تنظیم می‌کند. بنویسید [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_HasDataTable](./set_hasdatatable/)(**bool**) | تعیین می‌کند که آیا نمودار جدول داده دارد یا نه. بنویسید **bool**. |
| virtual void [set_HasLegend](./set_haslegend/)(**bool**) | تعیین می‌کند که آیا نمودار افسانه (legend) دارد یا نه. بنویسید **bool**. |
| virtual void [set_HasRoundedCorners](./set_hasroundedcorners/)(**bool**) | مشخص می‌کند که ناحیهٔ نمودار گوشه‌های گرد داشته باشد. بنویسید **bool**. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | تعیین می‌کند که آیا عنوان نمودار قابل مشاهده است یا نه. بنویسید **bool**. |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. بنویسید **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | تعیین می‌کند که آیا شکل مخفی است یا نه. بنویسید **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند تعریف‌شده برای کلیک موس را تنظیم می‌کند. بنویسید [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | پیوند تعریف‌شده برای حرکت ماوس فوق را تنظیم می‌کند. بنویسید [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | گزینه 'Mark as decorative' را تنظیم می‌کند. خواندن/نوشتن **bool**. |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | نام یک شکل را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_PlotVisibleCellsOnly](./set_plotvisiblecellsonly/)(**bool**) | تعیین می‌کند که آیا فقط سلول‌های قابل مشاهده ترسیم شوند. برای ترسیم هم سلول‌های قابل مشاهده و هم مخفی مقدار False است. بنویسید **bool**. |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ویژگی‌های خام چارچوب شکل را تنظیم می‌کند. بنویسید [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | تعداد درجاتی که شکل مشخص شده دور محور z می‌چرخد را تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پاد ساعت‌گرد است. بنویسید **float**. |
| virtual void [set_ShowDataLabelsOverMaximum](./set_showdatalabelsovermaximum/)(**bool**) | مشخص می‌کند که برچسب‌های داده بالای حداکثر نمودار نمایش داده شوند. بنویسید **bool**. |
| virtual void [set_Style](./set_style/)([StyleType](../styletype/)) | سبک نمودار را تنظیم می‌کند. بنویسید [StyleType](../styletype/). |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | نوع نمودار را تنظیم می‌کند. بنویسید [ChartType](../charttype/). |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. بنویسید **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. بنویسید **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقاط اندازه‌گیری می‌شود تنظیم می‌کند. بنویسید **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تعویض اشاره‌گرها در مجموعه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری (unlock) عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual void [ValidateChartLayout](./validatechartlayout/)() | مقدارهای واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط [IActualLayout](../iactuallayout/) را پیاده‌سازی می‌کنند ([IActualLayout::get_ActualX](../iactuallayout/get_actualx/), [IActualLayout::get_ActualY](../iactuallayout/get_actualy/), [IActualLayout::get_ActualWidth](../iactuallayout/get_actualwidth/), [IActualLayout::get_ActualHeight](../iactuallayout/get_actualheight/)) و مقادیر واقعی محورها ([IAxis::get_ActualMaxValue](../iaxis/get_actualmaxvalue/), [IAxis::get_ActualMinValue](../iaxis/get_actualminvalue/), [IAxis::get_ActualMajorUnit](../iaxis/get_actualmajorunit/), [IAxis::get_ActualMinorUnit](../iaxis/get_actualminorunit/), [IAxis::get_ActualMajorUnitScale](../iaxis/get_actualmajorunitscale/), [IAxis::get_ActualMinorUnitScale](../iaxis/get_actualminorunitscale/)). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | محتویات [Shape](../../aspose.slides/shape/) را به‌صورت فایل SVG ذخیره می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* کلاس [IFormattedTextContainer](../iformattedtextcontainer/)
* کلاس [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)