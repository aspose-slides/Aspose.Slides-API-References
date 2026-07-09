---
title: Chart
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 1260
url: /ru/aspose.slides.charts/chart/
---
## Chart класс

Представляет графическую диаграмму на слайде.

```csharp
public class Chart : GraphicalObject, IChart
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задаёт альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задаёт заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только чтение [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Позволяет получить базовый интерфейс IThemeable. Только чтение [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Предоставляет доступ к осям диаграммы. Только чтение [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Возвращает объект, позволяющий изменить формат задней стенки 3D-диаграммы. Только чтение [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в чёрно-белом режиме. Чтение/запись [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только чтение [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Возвращает таблицу данных диаграммы. Только чтение [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Возвращает или задаёт заголовок диаграммы. Только чтение [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на фигуре. Только чтение Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только чтение [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Возвращает или задаёт способ отображения пустых ячеек на диаграмме. Чтение/запись [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффекта. Только чтение [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства заливки фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заливки. Только чтение [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Возвращает объект, позволяющий изменить формат дна 3D-диаграммы. Только чтение [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задаёт свойства кадра фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только чтение [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Определяет, имеет ли диаграмма таблицу данных. Чтение/запись Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Определяет, есть ли у диаграммы легенда. Чтение/запись Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Указывает, что область диаграммы должна иметь скруглённые углы. Чтение/запись Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Определяет, отображается ли заголовок диаграммы. Чтение/запись Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задаёт высоту фигуры в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задаёт гиперссылку, определённую для клика мышью. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только чтение [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задаёт гиперссылку, определённую для наведения мыши. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Возвращает или задаёт параметр 'Mark as decorative'. Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, входит ли фигура в группу. Только чтение Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только чтение Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Возвращает или задаёт легенду для диаграммы. Только чтение [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линий фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линии. Только чтение [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задаёт имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор в пределах слайда, остающийся постоянным в течение жизни фигуры и позволяющий PowerPoint или коду межоперации надёжно ссылаться на фигуру из любой части документа. Только чтение UInt32. См. также [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает объект родительской GroupShape, если фигура входит в группу. В противном случае возвращает null. Только чтение [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры отсутствует заполнитель. Только чтение [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Представляет область построения диаграммы. Только чтение [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Определяет, отображаются ли только видимые ячейки. False — отображать как видимые, так и скрытые ячейки. Чтение/запись Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только чтение [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задаёт свойства необработанного кадра фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задаёт количество градусов, на которое указанная фигура вращается вокруг оси Z. Положительное значение — вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Возвращает 3D-вращение диаграммы. Только чтение [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только чтение [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 свойства) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Указывает, что подписи данных выше максимального значения диаграммы должны отображаться. Чтение/запись Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Возвращает объект, позволяющий изменить формат боковой стенки 3D-диаграммы. Только чтение [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только чтение [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Возвращает или задаёт стиль диаграммы. Чтение/запись [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Возвращает формат текста диаграммы. Свойство не применимо к следующим типам: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Только чтение [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Возвращает менеджер тем. Только чтение [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффекта для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3D-свойств. Только чтение [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Возвращает или задаёт тип диаграммы. Чтение/запись [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только чтение UInt32. См. также [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Указывает фигуры, нарисованные поверх диаграммы. Только чтение [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задаёт ширину фигуры в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задаёт координату X верхнего-левого угла фигуры в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задаёт координату Y верхнего-левого угла фигуры в пунктах. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру, находящуюся в самом заднем положении, а Shapes[Shapes.Count - 1] — в самом переднем. Только чтение Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Возвращает эффективную тему для этой диаграммы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (форму из макета и/или мастер-слайда, от которой наследуется текущая форма). Возвращает null, если текущая форма не наследуется. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Получает визуальные границы формы, рассчитанные по её отрисованному содержимому. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что данная форма не является заполнительным элементом. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Вычисляет фактические значения элементов диаграммы. Фактические значения включают позицию элементов, реализующих интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в файл SVG. |

### Смотрите также

* класс [GraphicalObject](../../aspose.slides/graphicalobject)
* интерфейс [IChart](../ichart)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->