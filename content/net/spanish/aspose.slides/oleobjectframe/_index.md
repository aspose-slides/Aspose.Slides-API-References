---
title: OleObjectFrame
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un objeto OLE en una diapositiva.
type: docs
weight: 8500
url: /es/aspose.slides/oleobjectframe/
---
## OleObjectFrame class

Representa un objeto OLE en una diapositiva.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título de texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permite obtener la interfaz base IGraphicalObject. Solo lectura[`IGraphicalObject`](../igraphicalobject) . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en el modo de visualización en blanco y negro.. Lectura/escritura[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lecturaInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de efectos. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtiene o establece información sobre datos incrustados OLE. Lectura/escritura[`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo) . |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Devuelve el nombre de archivo del objeto OLE incrustado |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Devuelve la ruta del objeto OLE incrustado |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de forma. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escrituraSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escrituraBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lecturaBoolean . |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Determina si un objeto es visible como icono. Lectura/escrituraBoolean . |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Determina si un objeto está vinculado a un archivo externo. Solo lecturaBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lecturaBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura[`ILineFormat`](../ilineformat) . |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Devuelve la ruta completa a un archivo vinculado. Se usará un nombre de archivo corto. Solo lecturaString . |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Devuelve la ruta completa a un archivo vinculado. Se usará un nombre de archivo largo. Lectura/escrituraString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Utilice un valor de cadena vacío si es necesario. Lectura/escrituraString . |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Devuelve o establece el nombre de un objeto. Lectura/escrituraString . |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Devuelve el ProgID de un objeto. Solo lecturaString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene un identificador de forma único en el alcance de la diapositiva. Solo lecturaUInt32 . Ver también[`UniqueId`](../shape/uniqueid) para obtener un identificador de forma único en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto principal GroupShape si la forma está agrupada. De lo contrario, devuelve null. Solo lectura[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición de una forma. Devuelve nulo si la forma no tiene marcador de posición. Solo lectura[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin formato. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que gira la forma especificada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escrituraSingle . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva principal de una forma. Solo lectura[`IBaseSlide`](../ibaseslide) . |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Devuelve el objeto de propiedades de relleno de imagen de OleObject. Solo lectura[`IPictureFillFormat`](../ipicturefillformat) . |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Devuelve o establece el título del icono de OleObject. Lectura/escrituraString . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que tiene propiedades de efecto 3D para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene un identificador de forma único en el ámbito de la presentación. Solo lecturaUInt32 . Ver también[`OfficeInteropShapeId`](../shape/officeinteropshapeid) para obtener un identificador de forma único en el alcance de la diapositiva. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando se abre o imprime la presentación. Lectura/escrituraBoolean . |
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
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Establece información sobre datos incrustados OLE.  Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece el indicador IsObjectLink en falso, lo que indica que el objeto OLE está incrustado. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de Shape como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de Shape como archivo SVG. |

### Ver también

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
