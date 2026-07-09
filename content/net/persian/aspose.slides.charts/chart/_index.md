---
title: Chart
second_title: مرجع API Aspose.Sildes برای .NET
description: نمایانگر یک نمودار گرافیکی روی اسلاید است.
type: docs
weight: 1260
url: /fa/aspose.slides.charts/chart/
---
## کلاس Chart

نمایش یک نمودار گرافیکی روی یک اسلاید.

```csharp
public class Chart : GraphicalObject, IChart
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک shape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | امکان دریافت رابط پایه IFormattedTextContainer را فراهم می‌کند. فقط‌خواندنی [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | امکان دریافت رابط پایه IThemeable را فراهم می‌کند. فقط‌خواندنی [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | دسترسی به محورهای chart را فراهم می‌کند. فقط‌خواندنی [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار پشت یک chart 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک shape چگونه در حالت نمایش سیاه-سفید رندر شود. قابل‌خواندن/قابل‌نوشتن [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | اطلاعات مربوط به داده‌های لینک شده یا جاسازی شده مرتبط با یک chart را برمی‌گرداند. فقط‌خواندنی [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | جدول داده‌ای یک chart را برمی‌گرداند. فقط‌خواندنی [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | عنوان chart را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی shape را برمی‌گرداند. فقط‌خواندنی Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی shape را برمی‌گرداند. فقط‌خواندنی [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | روش رسم سلول‌های خالی روی chart را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را برمی‌گرداند که شامل اثرهای پیکسلی اعمال شده بر یک shape است. نکته: برای برخی انواع shape که ویژگی‌های اثر ندارند ممکن است null برگرداند. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی پرش برای یک shape است. نکته: برای برخی انواع shape که ویژگی‌های پرش ندارند ممکن است null برگرداند. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب کف یک chart 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب shape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های shape را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | تعیین می‌کند آیا chart جدول داده دارد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | تعیین می‌کند آیا chart افسانه (legend) دارد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | مشخص می‌کند ناحیه chart گوشه‌های گرد داشته باشد. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | تعیین می‌کند آیا chart عنوان قابل مشاهده دارد یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع shape را برمی‌گرداند یا تنظیم می‌کند، بر حسب point. قابل‌خواندن/قابل‌نوشتن Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند آیا shape مخفی است یا نه. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند (hyperlink) تعریف شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر hyperlink را برمی‌گرداند. فقط‌خواندنی [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف شده برای عبور ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند آیا shape گروه‌بندی شده است یا نه. فقط‌خواندنی Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند آیا shape از نوع TextHolder_PPT است یا نه. فقط‌خواندنی Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | افسانه (legend) برای chart را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک shape است. نکته: برای برخی نوع‌های shape که ویژگی خط ندارند ممکن است null برگرداند. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک shape را برمی‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز می‌توانید رشته خالی استفاده کنید. قابل‌خواندن/قابل‌نوشتن String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسه یکتا scoped به اسلاید را برمی‌گرداند که برای طول عمر shape ثابت می‌ماند و به PowerPoint یا کد interop اجازه می‌دهد به طور قابل اعتماد shape را از هر جای سند ارجاع دهد. فقط‌خواندنی UInt32. همچنین ببینید [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | اگر shape گروه‌بندی شده باشد شیء parent GroupShape را برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | placeholder مربوط به یک shape را برمی‌گرداند. اگر shape placeholder نداشته باشد null برمی‌گرداند. فقط‌خواندنی [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | نواحی رسم chart را نمایندگی می‌کند. فقط‌خواندنی [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | تعیین می‌کند آیا تنها سلول‌های قابل مشاهده رسم شوند یا نه. برای رسم هم سلول‌های قابل مشاهده و هم مخفی False تنظیم شود. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | پیشنهاد والد (parent) یک slide را برمی‌گرداند. فقط‌خواندنی [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های فریم raw shape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجه‌های چرخش shape مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعت‌گرد؛ مقدار منفی نشانگر چرخش پادساعت‌گرد است. قابل‌خواندن/قابل‌نوشتن Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | چرخش 3D یک chart را برمی‌گرداند. فقط‌خواندنی [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های shape را برمی‌گرداند. فقط‌خواندنی [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 ویژگی) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | مشخص می‌کند برچسب‌های داده‌ای بالای حداکثر chart نشان داده شوند. قابل‌خواندن/قابل‌نوشتن Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | شیئی را برمی‌گرداند که امکان تغییر قالب دیوار جانبی یک chart 3D را فراهم می‌کند. فقط‌خواندنی [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک shape را برمی‌گرداند. فقط‌خواندنی [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | سبک chart را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | قالب متن chart را برمی‌گرداند. این ویژگی برای انواع زیر قابل اعمال نیست: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. فقط‌خواندنی [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | مدیر تم را برمی‌گرداند. فقط‌خواندنی [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را برمی‌گرداند که ویژگی‌های اثر 3d برای یک shape را شامل می‌شود. نکته: برای برخی نوع‌های shape که ویژگی‌های 3d ندارند ممکن است null برگرداند. فقط‌خواندنی [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | نوع chart را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسه داخلی scoped به presentation را برمی‌گرداند که برای استفاده افزونه‌ها یا کدهای دیگر هدف‌گذاری شده است. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به عنوان کلید یکتای دائمی در نظر گرفته شود. فقط‌خواندنی UInt32. همچنین ببینید [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | شکل‌های کشیده شده بر روی chart را مشخص می‌کند. فقط‌خواندنی [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض shape را برمی‌گرداند یا تنظیم می‌کند، بر حسب point. قابل‌خواندن/قابل‌نوشتن Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشه بالا-چپ shape را برمی‌گرداند یا تنظیم می‌کند، بر حسب point. قابل‌خواندن/قابل‌نوشتن Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشه بالا-چپ shape را برمی‌گرداند یا تنظیم می‌کند، بر حسب point. قابل‌خواندن/قابل‌نوشتن Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک shape در ترتیب z را برمی‌گرداند. Shapes[0] shape در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] shape در جلوی ترتیب z را برمی‌گرداند. فقط‌خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | در صورتی که placeholder وجود نداشته باشد، placeholder جدیدی اضافه می‌کند و ویژگی‌های placeholder را به یک مورد مشخص تنظیم می‌کند. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | یک تم مؤثر برای این chart را برمی‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک shape placeholder پایه را برمی‌گرداند (shape ای از layout و/یا master slide که shape فعلی از آن ارث می‌برد). اگر shape فعلی ارث نباشد null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | نمای کوچک (thumbnail) shape را برمی‌گرداند. نوع bounds ShapeThumbnailBounds.Shape به طور پیش‌فرض استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | نمای کوچک shape را برمی‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری shape را که از محتوای رندر شده محاسبه شده است، برمی‌گرداند. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | تعریف می‌کند که این shape یک placeholder نیست. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | مقدارهای واقعی عناصر chart را محاسبه می‌کند. مقدارهای واقعی شامل موقعیت عناصری که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) می‌شود. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتوای Shape را به عنوان فایل SVG ذخیره می‌کند. |

### مراجع

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IChart](../ichart)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->