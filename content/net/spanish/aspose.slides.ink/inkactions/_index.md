---
title: InkActions
second_title: Aspose.Sildes para .NET Referencia de la API
description: Representa la raíz de las acciones de tinta.
type: docs
weight: 7330
url: /es/aspose.slides.ink/inkactions/
---

## Clase InkActions

Representa la raíz de las acciones de tinta.

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado con una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado con una forma. Lectura/escritura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativa'. Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lectura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Usa un valor de cadena vacío si es necesario. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene el identificador único de la forma en el ámbito de la diapositiva. Solo lectura UInt32. Véase también [`UniqueId`](../../aspose.slides/shape/uniqueid) para obtener el identificador único de la forma en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario, devuelve null. Solo lectura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene un marcador de posición. Solo lectura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación padre de una diapositiva. Solo lectura [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de la forma sin procesar. Lectura/escritura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 propiedades) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva padre de una forma. Solo lectura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que tiene propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene el identificador único de la forma en el ámbito de la presentación. Solo lectura UInt32. Véase también [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) para obtener el identificador único de la forma en el ámbito de la diapositiva. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escritura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden z. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a uno especificado. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual está heredada). Se devuelve null si la forma actual no está heredada. |
| [GetImage](../../aspose.slides/shape/getimage)() | Devuelve la miniatura de la forma. Los límites de la miniatura de la forma de tipo ShapeThumbnailBounds.Shape se utilizan por defecto. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de la forma como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de la forma como un archivo SVG. |

### Véase También

* clase [GraphicalObject](../../aspose.slides/graphicalobject)
* interfaz [IInkActions](../iinkactions)
* espacio de nombres [Aspose.Slides.Ink](../../aspose.slides.ink)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->