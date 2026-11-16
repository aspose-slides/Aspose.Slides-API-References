---
title: Chart
second_title: مرجع API Aspose.Sildes برای .NET
description: نمودار گرافیکی را بر روی یک اسلاید نشان می‌دهد.
type: docs
weight: 1270
url: /fa/aspose.slides.charts/chart/
---
## کلاس Chart
یک نمودار گرافیکی را بر روی یک اسلاید نشان می‌دهد.

```csharp
public class Chart : GraphicalObject, IChart
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | عنوان متن جایگزین مرتبط با یک شکل را بر می‌گرداند یا تنظیم می‌کند. Read/write String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | امکان دریافت رابط پایه IFormattedTextContainer را فراهم می‌آورد. Read-only [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | امکان دریافت رابط پایه IThemeable را فراهم می‌آورد. Read-only [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | دسترسی به محورهای نمودار را فراهم می‌کند. Read-only [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | شیئی را بر می‌گرداند که امکان تغییر قالب دیوار پشت یک نمودار 3D را فراهم می‌کند. Read-only [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه‌سفید رندر می‌شود. Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | اطلاعات مربوط به داده‌های پیوندی یا جاسازی‌شده مرتبط با یک نمودار را بر می‌گرداند. Read-only [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | جدول داده‌ای یک نمودار را بر می‌گرداند. Read-only [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | عنوان یک نمودار را بر می‌گرداند یا تنظیم می‌کند. Read-only [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | تعداد نقاط اتصال روی شکل را بر می‌گرداند. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | داده‌های سفارشی شکل را بر می‌گرداند. Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | نحوه ترسیم سلول‌های خالی در یک نمودار را بر می‌گرداند یا تنظیم می‌کند. Read/write [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | شیء EffectFormat را بر می‌گرداند که حاوی اثرات پیکسلی اعمال‌شده به یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات اثر ندارند، مقدار null برگردد. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | شیء FillFormat را بر می‌گرداند که حاوی خصوصیات قالب‌برداری پرکردن برای یک شکل است. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های پرکردن ندارند، مقدار null برگردد. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | شیئی را بر می‌گرداند که امکان تغییر قالب کف یک نمودار 3D را فراهم می‌کند. Read-only [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | ویژگی‌های قاب شکل را بر می‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | قفل‌های شکل را بر می‌گرداند. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | تعیین می‌کند که آیا یک نمودار جدول داده دارد یا خیر. Read/write Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | تعیین می‌کند که آیا یک نمودار لِژند دارد یا خیر. Read/write Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | مشخص می‌کند که ناحیه نمودار گوشه‌های گرد داشته باشد. Read/write Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | تعیین می‌کند که آیا یک نمودار عنوان قابل مشاهده دارد یا خیر. Read/write Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | تعیین می‌کند که آیا شکل مخفی است یا خیر. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | پیوند تعریف‌شده برای کلیک ماوس را بر می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | مدیر پیوندها را بر می‌گرداند. Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | پیوند تعریف‌شده برای حرکت ماوس را بر می‌گرداند یا تنظیم می‌کند. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | گزینه 'Mark as decorative' را بر می‌گرداند یا تنظیم می‌کند. Reed/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | تعیین می‌کند که آیا شکل گروه‌بندی شده است یا خیر. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | تعیین می‌کند که آیا شکل TextHolder_PPT است یا خیر. Read-only Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | لِژند برای یک نمودار را بر می‌گرداند یا تنظیم می‌کند. Read-only [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | شیء LineFormat را بر می‌گرداند که خصوصیات قالب‌برداری خط را برای یک شکل فراهم می‌کند. نکته: ممکن است برای برخی انواع شکل‌ها که ویژگی‌های خط ندارند، مقدار null برگردد. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | نام یک شکل را بر می‌گرداند یا تنظیم می‌کند. نباید null باشد. در صورت نیاز مقدار رشته خالی استفاده شود. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | شناسهٔ یکتای اسلاید-محور را بر می‌گرداند که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای تعاملی اجازه می‌دهد شکل را از هر نقطه‌ای در سند به‌صورت قابل اطمینان ارجاع دهند. Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | شیء GroupShape والد را در صورتی که شکل گروه‌بندی شده باشد بر می‌گرداند. در غیر این صورت مقدار null برمی‌گردد. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | مکان‌نگهدار (placeholder) شکل را بر می‌گرداند. اگر شکل هیچ placeholderی نداشته باشد مقدار null برمی‌گردد. Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | ناحیه رسم یک نمودار را نشان می‌دهد. Read-only [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | تعیین می‌کند که آیا تنها سلول‌های قابل مشاهده ترسیم شوند. برای ترسیم هر دو سلول قابل مشاهده و مخفی مقدار False است. Read/write Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | ارائهٔ ارائهٔ والد یک اسلاید را بر می‌گرداند. Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | ویژگی‌های قاب شکل خام را بر می‌گرداند یا تنظیم می‌کند. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | تعداد درجاتی که شکل مشخص شده حول محور z می‌چرخد را بر می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. Read/write Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | یک چرخش 3D از یک نمودار را بر می‌گرداند. Read-only [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | قفل‌های شکل را بر می‌گرداند. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | مشخص می‌کند که برچسب‌های داده بالاتر از حداکثر نمودار نشان داده شوند. Read/write Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | شیئی را بر می‌گرداند که امکان تغییر قالب دیوار جانبی یک نمودار 3D را فراهم می‌کند. Read-only [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | اسلاید والد یک شکل را بر می‌گرداند. Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | سبک نمودار را بر می‌گرداند یا تنظیم می‌کند. Read/write [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | قالب متن نمودار را بر می‌گرداند. این ویژگی برای انواع زیر اعمال نمی‌شود: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Read-only [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | مدیر تم را بر می‌گرداند. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | شیء ThreeDFormat را بر می‌گرداند که خصوصیات اثر 3D برای یک شکل را فراهم می‌کند. نکته: ممکن است برای برخی انواع شکل‌ها که خصوصیات 3D ندارند، مقدار null برگردد. Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | نوع نمودار را بر می‌گرداند یا تنظیم می‌کند. Read/write [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | شناسهٔ داخلی، اسلاید-محور را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، بر می‌گرداند. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویسی دوباره اختصاص یابد، نباید به‌عنوان کلید یکتا دائمی در نظر گرفته شود. Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | شکل‌هایی که بر روی نمودار کشیده می‌شوند را مشخص می‌کند. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، بر می‌گرداند یا تنظیم می‌کند. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | موقعیت یک شکل در ترتیب z را بر می‌گرداند. Shapes[0] شکل را در پشت ترتیب z بر می‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلو ترتیب z بر می‌گرداند. Read-only Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | اگر هیچ placeholderی وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص تنظیم می‌نماید. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | یک تم مؤثر برای این نمودار را بر می‌گرداند. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | یک شکل placeholder پایه را بر می‌گرداند (شکلی که از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن ارث برده می‌شود). اگر شکل فعلی ارث‌بری نشده باشد، مقدار null برگردانده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)() | تصویر کوچک شکل را بر می‌گرداند. به‌طور پیش‌فرض نوع ShapeThumbnailBounds.Shape برای مرزهای تصویر کوچک استفاده می‌شود. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | تصویر کوچک شکل را بر می‌گرداند. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | مرزهای بصری شکل که از محتوای رندر شده آن محاسبه می‌شود را به‌دست می‌آورد. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | مشخص می‌کند که این شکل placeholder نیست. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | مقادیر واقعی عناصر نمودار را محاسبه می‌کند. مقادیر واقعی شامل موقعیت عناصری است که رابط IActualLayout را پیاده‌سازی می‌کنند (IActualLayout.ActualX، IActualLayout.ActualY، IActualLayout.ActualWidth، IActualLayout.ActualHeight) و مقادیر واقعی محورها (IAxis.ActualMaxValue، IAxis.ActualMinValue، IAxis.ActualMajorUnit، IAxis.ActualMinorUnit، IAxis.ActualMajorUnitScale، IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | محتویات Shape را به عنوان فایل SVG ذخیره می‌کند. |

### موارد مرتبط

* کلاس [GraphicalObject](../../aspose.slides/graphicalobject)
* رابط [IChart](../ichart)
* فضای نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->