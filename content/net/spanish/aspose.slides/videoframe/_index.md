---
title: VideoFrame
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un clip de video en una diapositiva.
type: docs
weight: 10910
url: /es/aspose.slides/videoframe/
---
## VideoFrame class

Representa un clip de video en una diapositiva.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Devuelve una colección de valores de ajuste de forma. Solo lectura[`IAdjustValueCollection`](../iadjustvaluecollection) . |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escrituraString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título de texto alternativo asociado a una forma. Lectura/escrituraString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en el modo de visualización en blanco y negro.. Lectura/escritura[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lecturaInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxeles aplicados a una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de efectos. Solo lectura[`IEffectFormat`](../ieffectformat) . |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Devuelve o establece el objeto de video incrustado. Lectura/escritura[`IVideo`](../ivideo) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de forma. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Determina si un video se muestra en modo de pantalla completa. Lectura/escrituraBoolean . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escrituraSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escrituraBoolean . |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Determina si un VideoFrame está oculto. Lectura/escrituraBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lecturaBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lecturaBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura[`ILineFormat`](../ilineformat) . |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escrituraString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Utilice un valor de cadena vacío si es necesario. Lectura/escrituraString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene un identificador de forma único en el alcance de la diapositiva. Solo lecturaUInt32 . Ver también[`UniqueId`](../shape/uniqueid) para obtener un identificador de forma único en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto principal GroupShape si la forma está agrupada. De lo contrario, devuelve null. Solo lectura[`IGroupShape`](../igroupshape) . |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Devuelve el objeto PictureFillFormat para un marco de imagen. Solo lectura[`IPictureFillFormat`](../ipicturefillformat) . |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IPictureFrameLock`](../ipictureframelock) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición de una forma. Devuelve nulo si la forma no tiene marcador de posición. Solo lectura[`IPlaceholder`](../iplaceholder) . |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Determina si un video está en bucle. Lectura/escrituraBoolean . |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Devuelve o establece el modo de reproducción de video. Lectura/escritura[`VideoPlayModePreset`](../videoplaymodepreset) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin formato. Lectura/escritura[`IShapeFrame`](../ishapeframe) . |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Devuelve o establece la escala de altura (en relación con el tamaño de la imagen original) del marco de la imagen. El valor 1,0 corresponde al 100%. Lectura/escrituraSingle . |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Devuelve o establece la escala de ancho (en relación con el tamaño de la imagen original) del marco de la imagen. El valor 1,0 corresponde al 100%. Lectura/escrituraSingle . |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Determina si un video se rebobina automáticamente para comenzar tan pronto como la película termina de reproducirse. Lectura/escrituraBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que gira la forma especificada alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escrituraSingle . |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura[`IPictureFrameLock`](../ipictureframelock) . (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Devuelve el objeto de estilo de la forma. Solo lectura[`IShapeStyle`](../ishapestyle) . |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Devuelve o establece el tipo de autoforma para un PictureFrame. Están permitidos todos los elementos del conjunto[`ShapeType`](../shapetype), excepto todo tipo de líneas: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva principal de una forma. Solo lectura[`IBaseSlide`](../ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que tiene propiedades de efecto 3D para una forma. Nota: puede devolver un valor nulo para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene un identificador de forma único en el ámbito de la presentación. Solo lecturaUInt32 . Ver también[`OfficeInteropShapeId`](../shape/officeinteropshapeid) para obtener un identificador de forma único en el alcance de la diapositiva. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Devuelve o establece el volumen de audio. Lectura/escritura[`AudioVolumeMode`](../audiovolumemode) . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escrituraSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escrituraSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte delantera del z- order. Solo lecturaInt32 . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no lo hay y establece las propiedades del marcador de posición en una especificada. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea y devuelve una matriz de elementos de forma. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Devuelve la copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Devuelve la miniatura de la forma. ShapeThumbnailBounds. El tipo de límites de la miniatura de la forma se usa de forma predeterminada. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Actualiza la geometría de la forma de[`IGeometryPath`](../igeometrypath) objeto. Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype) ) aCustom . |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Actualiza la geometría de la forma desde una matriz de[`IGeometryPath`](../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype) ) aCustom . |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de Shape como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de Shape como archivo SVG. |

### Ver también

* class [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
