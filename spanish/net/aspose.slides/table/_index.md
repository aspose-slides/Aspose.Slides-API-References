---
title: Table
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una tabla en una diapositiva.
type: docs
weight: 10050
url: /es/net/aspose.slides/table/
---
## Table class

Representa una tabla en una diapositiva.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título de texto alternativo asociado a una forma. Lectura/escrituraString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en el modo de visualización en blanco y negro.. Lectura/escritura[`BlackWhiteMode`](../blackwhitemode) . |
| [Columns](../../aspose.slides/table/columns) { get; } | Devuelve la colección de columnas. Solo lectura[`IColumnCollection`](../icolumncollection) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lecturaInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de efectos. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Determina si la primera columna de una tabla debe dibujarse con un formato especial. Lectura/escrituraBoolean . |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Determina si la primera fila de una tabla debe dibujarse con un formato especial. Lectura/escrituraBoolean . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de forma. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escrituraSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escrituraBoolean . |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Determina si las filas pares deben dibujarse con un formato diferente. Lectura/escrituraBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lecturaBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lecturaBoolean . |
| [Item](../../aspose.slides/table/item) { get; } | Devuelve la celda en los índices de columna y fila especificados. Solo lectura[`Cell`](../cell) . |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Determina si la última columna de una tabla debe dibujarse con un formato especial. Lectura/escrituraBoolean . |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Determina si la última fila de una tabla debe dibujarse con un formato especial. Lectura/escrituraBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Utilice un valor de cadena vacío si es necesario. Lectura/escrituraString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene un identificador de forma único en el alcance de la diapositiva. Solo lecturaUInt32 . Ver también[`UniqueId`](../shape/uniqueid) para obtener un identificador de forma único en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto principal GroupShape si la forma está agrupada. De lo contrario, devuelve null. Solo lectura[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición de una forma. Devuelve nulo si la forma no tiene marcador de posición. Solo lectura[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin formato. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Determina si la tabla tiene un orden de lectura de derecha a izquierda. Lectura-escrituraBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que gira la forma especificada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escrituraSingle . |
| [Rows](../../aspose.slides/table/rows) { get; } | Devuelve la colección de filas. Solo lectura[`IRowCollection`](../irowcollection) . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva principal de una forma. Solo lectura[`IBaseSlide`](../ibaseslide) . |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Obtiene o establece el estilo de tabla integrado. Lectura/escritura[`TableStylePreset`](../tablestylepreset) . |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Devuelve el objeto TableFormat que contiene las propiedades de formato de esta tabla. Solo lectura[`ITableFormat`](../itableformat) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que tiene propiedades de efecto 3D para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene un identificador de forma único en el ámbito de la presentación. Solo lecturaUInt32 . Ver también[`OfficeInteropShapeId`](../shape/officeinteropshapeid) para obtener un identificador de forma único en el alcance de la diapositiva. |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Determina si las columnas pares deben dibujarse con un formato diferente. Lectura/escrituraBoolean . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escrituraSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte delantera del z- order. Solo lecturaInt32 . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no lo hay y establece las propiedades del marcador de posición en una especificada. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Devuelve la miniatura de la forma. ShapeThumbnailBounds. El tipo de límites de la miniatura de la forma se usa de forma predeterminada. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Fusiona celdas vecinas. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Establece propiedades de formato de párrafo definidas para todos los párrafos de las celdas de la tabla. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Establece propiedades de formato de porción definida para todas las porciones de las celdas de la tabla. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Establece propiedades de formato de marco de texto definidas para todos los marcos de texto de las celdas de la tabla. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de Shape como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de Shape como archivo SVG. |

### Ver también

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
