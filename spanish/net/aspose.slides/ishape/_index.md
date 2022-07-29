---
title: IShape
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una forma en una diapositiva.
type: docs
weight: 6370
url: /es/net/aspose.slides/ishape/
---
## IShape interface

Representa una forma en una diapositiva.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Devuelve o establece el título de texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permite obtener la interfaz base IHyperlinkContainer. Solo lectura[`IHyperlinkContainer`](../ihyperlinkcontainer) . |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura[`ISlideComponent`](../islidecomponent) . |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en el modo de visualización en blanco y negro.. Lectura/escritura[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lecturaInt32 . |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura[`ICustomData`](../icustomdata) . |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. Solo lectura[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Devuelve o establece las propiedades del marco de forma. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escrituraSingle . |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escrituraBoolean . |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lecturaBoolean . |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determina si la forma es TextHolder. Solo lecturaBoolean . |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Solo lectura[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Devuelve o establece el nombre de una forma. Lectura/escrituraString . |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Obtiene un identificador de forma único en el alcance de la diapositiva. Solo lecturaUInt32 . Ver también[`UniqueId`](./uniqueid) para obtener un identificador de forma único en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Devuelve el objeto principal GroupShape si la forma está agrupada. De lo contrario, devuelve null. Solo lectura[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Devuelve el marcador de posición de una forma. Solo lectura[`IPlaceholder`](../iplaceholder) . |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin formato. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Devuelve o establece el número de grados que gira la forma especificada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escrituraSingle . |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IBaseShapeLock`](../ibaseshapelock) . |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene propiedades de formato de línea para una forma. Solo lectura[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Obtiene un identificador de forma único en el ámbito de la presentación. Solo lecturaUInt32 . Ver también[`OfficeInteropShapeId`](./officeinteropshapeid) para obtener un identificador de forma único en el alcance de la diapositiva. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escrituraSingle . |
| [X](../../aspose.slides/ishape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte delantera del z- order. Solo lecturaInt32 . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no lo hay y establece las propiedades del marcador de posición en una especificada. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail)() | Devuelve la miniatura de la forma. ShapeThumbnailBounds. El tipo de límites de la miniatura de la forma se usa de forma predeterminada. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Guarda el contenido de Shape como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de Shape como archivo SVG. |

### Ver también

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
