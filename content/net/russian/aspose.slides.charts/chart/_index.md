---
title: Chart
second_title: Aspose.Sildes для .NET API Reference
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 1180
url: /ru/aspose.slides.charts/chart/
---

## Chart class

Представляет графическую диаграмму на слайде.

```csharp
public class Chart : GraphicalObject, IChart
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Позволяет получить базовый интерфейс IThemeable. Только для чтения [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Предоставляет доступ к осям диаграммы. Только для чтения [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Возвращает объект, который позволяет изменить формат задней стены 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство, указывающее, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только для чтения [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Возвращает таблицу данных диаграммы. Только для чтения [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Возвращает или задает заголовок диаграммы. Только для чтения [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Возвращает или задает способ отображения пустых ячеек на диаграмме. Чтение/запись [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств эффектов. Только для чтения [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства заполнения для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств заполнения. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Возвращает объект, который позволяет изменить формат пола 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Определяет, имеет ли диаграмма таблицу данных. Чтение/запись Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Определяет, имеет ли диаграмма легенду. Чтение/запись Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Указывает, будет ли область диаграммы иметь закругленные углы. Чтение/запись Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Определяет, имеет ли диаграмма видимый заголовок. Чтение/запись Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задает опцию 'Отметить как декоративную' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Возвращает или задает легенду для диаграммы. Только для чтения [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств линий. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Не должно быть null. Используйте пустое строковое значение, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайда. Только для чтения UInt32. См. также [`UniqueId`](../../aspose.slides/shape/uniqueid) для получения уникального идентификатора фигуры в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Представляет область графика диаграммы. Только для чтения [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Определяет, отображаются ли только видимые ячейки. False для отображения как видимых, так и скрытых ячеек. Чтение/запись Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства исходной рамки фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое заданная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Возвращает 3D-вращение диаграммы. Только для чтения [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 свойства) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Указывает, должны ли отображаться метки данных, превышающие максимум диаграммы. Чтение/запись Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Возвращает объект, который позволяет изменить формат боковой стены 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Возвращает или задает стиль диаграммы. Чтение/запись [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Возвращает текстовый формат диаграммы. Свойство не применимо к следующим типам: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Только для чтения [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Возвращает менеджер тем. Только для чтения [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства эффектов 3D для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств 3D. Только для чтения [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Возвращает или задает тип диаграммы. Чтение/запись [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) для получения уникального идентификатора фигуры в области слайда. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Указывает фигуры, нарисованные поверх диаграммы. Только для чтения [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает x-координату верхнего левого угла фигуры. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает y-координату верхнего левого угла фигуры. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в самом конце порядка z, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане порядка z. Только для чтения Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя для указанного. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Возвращает эффективную тему для этой диаграммы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или главного слайда, от которой наследуется текущая фигура). Возвращается null, если текущая фигура не наследуется. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. Тип миниатюры ShapeThumbnailBounds.Shape используется по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Расчитывает фактические значения элементов диаграммы. Фактические значения включают положение элементов, которые реализуют интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры как файл SVG. |

### See Also

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->