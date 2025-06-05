---
title: Chart
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa un gráfico en una diapositiva.
type: docs
weight: 1180
url: /es/aspose.slides.charts/chart/
---

## Clase Chart

Representa un gráfico en una diapositiva.

```csharp
public class Chart : GraphicalObject, IChart
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado con una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado con una forma. Lectura/escritura String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Permite obtener la interfaz base IFormattedTextContainer. Solo lectura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Permite obtener la interfaz base IThemeable. Solo lectura [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Proporciona acceso a los ejes del gráfico. Solo lectura [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Devuelve un objeto que permite cambiar el formato de la pared trasera de un gráfico 3D. Solo lectura [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Devuelve información sobre los datos vinculados o incrustados asociados con un gráfico. Solo lectura [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Devuelve una tabla de datos de un gráfico. Solo lectura [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Devuelve o establece un título para el gráfico. Solo lectura [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Devuelve o establece la forma en que se trazarán las celdas en blanco en un gráfico. Lectura/escritura [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Devuelve un objeto que permite cambiar el formato del suelo de un gráfico 3D. Solo lectura [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Determina si un gráfico tiene una tabla de datos. Lectura/escritura Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Determina si un gráfico tiene una leyenda. Lectura/escritura Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Especifica que el área del gráfico tendrá esquinas redondeadas. Lectura/escritura Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Determina si un gráfico tiene un título visible. Lectura/escritura Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para hacer clic con el mouse. Lectura/escritura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse por encima. Lectura/escritura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativo'. Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es un TextHolder_PPT. Solo lectura Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Devuelve o establece una leyenda para un gráfico. Solo lectura [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Utilice una cadena vacía si es necesario. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene el identificador único de la forma en el ámbito de la diapositiva. Solo lectura UInt32. Véase también [`UniqueId`](../../aspose.slides/shape/uniqueid) para obtener el identificador único de la forma en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario, devuelve null. Solo lectura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene un marcador de posición. Solo lectura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Representa el área de trazado de un gráfico. Solo lectura [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Determina si solo se trazan las celdas visibles. Falso para trazar tanto celdas visibles como ocultas. Lectura/escritura Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin procesar. Lectura/escritura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados en que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Devuelve una rotación 3D de un gráfico. Solo lectura [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 propiedades) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Especifica que las etiquetas de datos sobre el máximo del gráfico deben mostrarse. Lectura/escritura Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Devuelve un objeto que permite cambiar el formato de la pared lateral de un gráfico 3D. Solo lectura [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva principal de una forma. Solo lectura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Devuelve o establece el estilo del gráfico. Lectura/escritura [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Devuelve el formato de texto del gráfico. La propiedad no es aplicable para los siguientes tipos: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Solo lectura [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Devuelve el administrador de temas. Solo lectura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Devuelve o establece el tipo de gráfico. Lectura/escritura [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene el identificador único de la forma en el ámbito de la presentación. Solo lectura UInt32. Véase también [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) para obtener el identificador único de la forma en el ámbito de la diapositiva. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Especifica las formas dibujadas en la parte superior del gráfico. Solo lectura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escritura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden z. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a uno especificado. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Devuelve un tema efectivo para este gráfico. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual). Se devuelve null si la forma actual no se hereda. |
| [GetImage](../../aspose.slides/shape/getimage)() | Devuelve la miniatura de la forma. Se utiliza el tipo de límite de miniatura de forma ShapeThumbnailBounds por defecto. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Calcula los valores reales de los elementos del gráfico. Los valores reales incluyen la posición de los elementos que implementan la interfaz IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) y los valores de ejes reales (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de la forma como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de la forma como un archivo SVG. |

### Ver También

* clase [GraphicalObject](../../aspose.slides/graphicalobject)
* interfaz [IChart](../ichart)
* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->