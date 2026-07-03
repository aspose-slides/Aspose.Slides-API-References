---
title: Chart
second_title: Aspose.Sildes برای .NET مرجع API
description: یک نمودار گرافیکی را بر روی اسلاید نشان می‌دهد.
type: docs
weight: 1260
url: /fa/aspose.slides.charts/chart/
---
## Chart کلاس

نمایش یک نمودار گرافیکی بر روی یک اسلاید.

```csharp
public class Chart : GraphicalObject, IChart
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | دسترسی به رابط پایه IFormattedTextContainer را فراهم می‌کند. فقط‌خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | دسترسی به رابط پایه IThemeable را فراهم می‌کند. فقط‌خواندنی [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | دسترسی به محورهاى نمودار را فراهم می‌کند. فقط‌خواندنی [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار پشت یک نمودار 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سبز رندر می‌شود. خواندنی/نوشتنی [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | اطلاعات مربوط به داده‌های پیوند داده یا جاسازی‌شده مرتبط با یک نمودار را برمی‌گرداند. فقط‌خواندنی [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | جدول داده‌ای یک نمودار را برمی‌گرداند. فقط‌خواندنی [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | عنوان یک نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | روش رسم سلول‌های خالی روی یک نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را که شامل اثرات پیکسل اعمال‌شده به یک شکل است، برمی‌گرداند. نکته: برای برخی انواع شکلی که ویژگی اثر ندارند، ممکن است null بازگردد. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است، برمی‌گرداند. نکته: برای برخی انواع شکلی که ویژگی پر کردن ندارند، ممکن است null بازگردد. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب کف یک نمودار 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | مشخص می‌کند که آیا یک نمودار جدول داده دارد یا خیر. خواندنی/نوشتنی Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | مشخص می‌کند که آیا یک نمودار راهنمای (legend) دارد یا خیر. خواندنی/نوشتنی Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. خواندنی/نوشتنی Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | مشخص می‌کند که آیا عنوان نمایان برای نمودار وجود دارد یا خیر. خواندنی/نوشتنی Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقاط اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | مشخص می‌کند که شکل مخفی باشد یا خیر. خواندنی/نوشتنی Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر Hyperlink را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس روی آن را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | مشخص می‌کند که شکل گروه‌بندی شده باشد یا خیر. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | مشخص می‌کند که شکل TextHolder_PPT است یا خیر. فقط‌خواندنی Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | راهنمایی برای یک نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است، برمی‌گرداند. نکته: برای برخی انواع شکلی که ویژگی خط ندارند، ممکن است null بازگردد. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. نمی‌تواند null باشد. در صورت نیاز از مقدار رشته خالی استفاده کنید. خواندنی/نوشتنی String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | یک شناسه یکتا scoped به اسلاید را که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع مطمئن به شکل از هر نقطه‌ای در سند را می‌دهد، برمی‌گرداند. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر شکل گروه‌بندی شده باشد، شیء والد GroupShape را برمی‌گرداند. در غیر اینصورت null باز می‌گردد. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | فاصل‌نگهدار (placeholder) برای یک شکل را برمی‌گرداند. اگر شکل فاصل‌نگهدار نداشته باشد null باز می‌گردد. فقط‌خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | ناحیه نمودار را نمایان می‌کند. فقط‌خواندنی [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | مشخص می‌کند که آیا فقط سلول‌های قابل رؤیت رسم شوند یا خیر. False برای رسم هم سلول‌های قابل رؤیت و هم مخفی. خواندنی/نوشتنی Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائه والد یک اسلاید را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. خواندنی/نوشتنی Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | چرخش 3D یک نمودار را برمی‌گرداند. فقط‌خواندنی [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | مشخص می‌کند که برچسب‌های داده‌ای بالای حداکثر نمودار نمایش داده شوند. خواندنی/نوشتنی Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار کناری یک نمودار 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | سبک نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | قالب متن نمودار را برمی‌گرداند. این ویژگی برای انواع زیر قابل اعمال نیست: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. فقط‌خواندنی [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | مدیر تم را برمی‌گرداند. فقط‌خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را که ویژگی‌های اثر 3D برای یک شکل را دارد، برمی‌گرداند. نکته: برای برخی انواع شکلی که ویژگی 3D ندارند، ممکن است null بازگردد. فقط‌خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | نوع نمودار را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | یک شناسه داخلی scoped به ارائه را که برای استفاده افزونه‌ها یا کدهای دیگر منظور شده است، برمی‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی مجدداً اختصاص یابد، نباید به‌عنوان کلید یکتا ثابت در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | شکل‌هایی که روی نمودار کشیده می‌شوند را مشخص کنید. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقاط اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالای چپ شکل را که بر حسب نقاط است، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالای چپ شکل را که بر حسب نقاط است، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل را در ترتیب z برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | یک تم مؤثر برای این نمودار را برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را برمی‌گرداند (شکلی از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث می‌برد). اگر شکل فعلی ارث‌برده نشود، null باز می‌گردد. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر بندانگشتی شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape برای محدوده تصویر بندانگشتی به‌صورت پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | محدوده بصری شکل را که بر پایه محتوای رندر شده‌اش محاسبه می‌شود، دریافت می‌کند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این شکل placeholder نیست. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | مقدارهای واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به‌عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IChart](../ichart)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->