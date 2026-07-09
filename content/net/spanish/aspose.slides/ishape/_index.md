---
title: IShape
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una forma en una diapositiva.
type: docs
weight: 6950
url: /es/aspose.slides/ishape/
---
## IShape interfaz

Representa una forma en una diapositiva.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado a una forma. Lectura/escritura String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permite obtener la interfaz base IHyperlinkContainer. Solo lectura [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permite obtener la interfaz base ISlideComponent. Solo lectura [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. Solo lectura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Obtiene o establece la altura de la forma, medida en puntos. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativo'. Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determina si la forma es TextHolder. Solo lectura Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Solo lectura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Devuelve o establece el nombre de una forma. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Devuelve un identificador único de alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o el código interop haga referencia a la forma de forma fiable desde cualquier parte del documento. Solo lectura UInt32. Ver también [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. En caso contrario devuelve null. Solo lectura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Devuelve el marcador de posición de una forma. Solo lectura [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Devuelve o establece las propiedades en bruto del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene las propiedades de formato de línea para una forma. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Devuelve un identificador interno de alcance de presentación destinado a ser usado por complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura UInt32. Ver también [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Obtiene o establece el ancho de la forma, medido en puntos. Lectura/escritura Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma al fondo del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Añade un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual). Se devuelve null si la forma actual no está heredada. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Devuelve la miniatura de la forma. El tipo ShapeThumbnailBounds.Shape se usa por defecto para los límites de la miniatura de la forma. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Guarda el contenido de la Forma como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de la Forma como archivo SVG. |

### Ver también

* interfaz [IHyperlinkContainer](../ihyperlinkcontainer)
* interfaz [ISlideComponent](../islidecomponent)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->