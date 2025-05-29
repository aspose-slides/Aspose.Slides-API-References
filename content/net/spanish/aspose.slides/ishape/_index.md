---
title: IShape
second_title: Aspose.Slides para .NET Referencia de API
description: Representa una forma en una diapositiva.
type: docs
weight: 6730
url: /es/aspose.slides/ishape/
---

## Interfaz IShape

Representa una forma en una diapositiva.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado con una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado con una forma. Lectura/escritura String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permite obtener la interfaz base IHyperlinkContainer. Solo lectura [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Propiedad que especifica cómo se renderizará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Solo lectura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativa'. Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determina si la forma es un TextHolder. Solo lectura Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Solo lectura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Devuelve o establece el nombre de una forma. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Obtiene el identificador único de la forma en el contexto de la diapositiva. Solo lectura UInt32. Véase también [`UniqueId`](./uniqueid) para obtener el identificador único de la forma en el contexto de la presentación. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario, devuelve null. Solo lectura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Devuelve el marcador de posición para una forma. Solo lectura [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de la forma sin procesar. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Devuelve o establece el número de grados que se ha rotado la forma especificada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido contrario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene propiedades de formato de línea para una forma. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Obtiene el identificador único de la forma en el contexto de la presentación. Solo lectura UInt32. Véase también [`OfficeInteropShapeId`](./officeinteropshapeid) para obtener el identificador único de la forma en el contexto de la diapositiva. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escritura Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden z. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a uno especificado. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual se hereda). Se devuelve null si la forma actual no se hereda. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Devuelve la miniatura de la forma. Se usa el tipo de límites de miniatura de la forma ShapeThumbnailBounds por defecto. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Guarda el contenido de la Forma como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de la Forma como un archivo SVG. |

### Véase También

* interfaz [IHyperlinkContainer](../ihyperlinkcontainer)
* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->