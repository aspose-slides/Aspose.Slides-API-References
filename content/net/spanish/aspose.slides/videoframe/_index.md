---
title: VideoFrame
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un videoclip en una diapositiva.
type: docs
weight: 11410
url: /es/aspose.slides/videoframe/
---

## Clase VideoFrame

Representa un videoclip en una diapositiva.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Devuelve una colección de valores de ajuste de la forma. Solo lectura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado a una forma. Lectura/escritura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Devuelve la colección de subtítulos del video. Solo lectura [`ICaptionsCollection`](../icaptionscollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene los efectos de píxeles aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Devuelve o establece el objeto de video incrustado. Lectura/escritura [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Determina si un video se muestra en modo de pantalla completa. Lectura/escritura Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Determina si un VideoFrame está oculto. Lectura/escritura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para el mouse sobre. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina si el PictureFrame es un objeto Cameo o no. Solo lectura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es un TextHolder_PPT. Solo lectura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Devuelve o establece el nombre de un archivo de video que está vinculado a un VideoFrame. Lectura/escritura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Usa un valor de cadena vacío si es necesario. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene el identificador único de la forma en el ámbito de la diapositiva. Solo lectura UInt32. Consulta también [`UniqueId`](../shape/uniqueid) para obtener el identificador único de la forma en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. En caso contrario, devuelve null. Solo lectura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Devuelve el objeto PictureFillFormat para un marco de imagen. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene un marcador de posición. Solo lectura [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Determina si un video se repite. Lectura/escritura Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Devuelve o establece el modo de reproducción del video. Lectura/escritura [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de la forma sin procesar. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura/escritura Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Determina si un video se rebobina automáticamente al inicio tan pronto como se ha terminado de reproducir. Lectura/escritura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que la forma especificada está rota alrededor del eje z. Un valor positivo indica rotación en el sentido de las agujas del reloj; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IPictureFrameLock`](../ipictureframelock). (2 propiedades) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Devuelve el objeto de estilo de la forma. Solo lectura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Devuelve o establece el tipo de AutoShape para un PictureFrame. Se permiten todos los elementos del conjunto [`ShapeType`](../shapetype), excepto todo tipo de líneas: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva principal de una forma. Solo lectura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene propiedades de efecto 3d para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3d. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Recortar final [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Recortar inicio [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene el identificador único de la forma en el ámbito de la presentación. Solo lectura UInt32. Consulta también [`OfficeInteropShapeId`](../shape/officeinteropshapeid) para obtener el identificador único de la forma en el ámbito de la diapositiva. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Devuelve o establece el volumen de audio. Lectura/escritura [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escritura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte posterior del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden z. Solo lectura Int32. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a un especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea y devuelve una matriz de elementos de la forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual está heredada). Se devuelve un null si la forma actual no está heredada. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Devuelve la copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Devuelve la miniatura de la forma. Por defecto se usa el tipo de límites de miniatura ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Actualiza la geometría de la forma desde el objeto [`IGeometryPath`](../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype)) a Personalizado. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Actualiza la geometría de la forma desde una matriz de [`IGeometryPath`](../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype)) a Personalizado. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de la forma como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de la forma como un archivo SVG. |

### Vea también

* clase [PictureFrame](../pictureframe)
* interfaz [IVideoFrame](../ivideoframe)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->