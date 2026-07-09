---
title: AudioFrame
second_title: Referencia de la API de Aspose.Sildes para .NET
description: Representa un clip de audio en una diapositiva.
type: docs
weight: 870
url: /es/aspose.slides/audioframe/
---
## Clase AudioFrame

Representa un clip de audio en una diapositiva.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Propiedades

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Devuelve una colección de valores de ajuste de la forma. Solo lectura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado a una forma. Lectura/escritura String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Devuelve o establece el índice de la última pista. Lectura/escritura Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Devuelve o establece el tiempo de la última pista. Lectura/escritura Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Devuelve o establece el índice de la pista inicial. Lectura/escritura Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Devuelve o establece el tiempo de la pista inicial. Lectura/escritura Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se renderiza una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Obtiene la colección de subtítulos cerrados asociados al marco de audio. Esta propiedad es solo lectura y devuelve un [`ICaptionsCollection`](../icaptionscollection) que contiene todas las pistas de subtítulos. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de puntos de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene los efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Determina si un sonido está incrustado en una presentación. Solo lectura Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Devuelve o establece el objeto de audio incrustado. Lectura/escritura [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Especifica la duración en milisegundos del fundido de entrada inicial de los medios. Lectura/escritura Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Especifica la duración en milisegundos del fundido de salida final de los medios. Lectura/escritura Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene las propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtiene o establece la altura de la forma, medida en puntos. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Determina si un AudioFrame está oculto. Lectura/escritura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para clic del ratón. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para pasar el ratón. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina si el PictureFrame es un objeto Cameo o no. Solo lectura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativo'. Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lectura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene las propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Devuelve o establece el nombre de un archivo de audio vinculado a un AudioFrame. Lectura/escritura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Use una cadena vacía si es necesario. Lectura/escritura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Devuelve un identificador único con ámbito de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o el código interop referencien la forma de forma fiable desde cualquier parte del documento. Solo lectura UInt32. Ver también [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario devuelve null. Solo lectura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Devuelve el objeto PictureFillFormat para un marco de imagen. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Determina si el audio se reproduce en todas las diapositivas. Lectura/escritura Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Determina si un audio está en bucle. Lectura/escritura Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Devuelve o establece el modo de reproducción del audio. Lectura/escritura [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación principal de una diapositiva. Solo lectura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades sin procesar del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Devuelve o establece la escala de altura (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100%. Lectura/escritura Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Devuelve o establece la escala de ancho (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100%. Lectura/escritura Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura/escritura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que la forma especificada se rota alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IPictureFrameLock`](../ipictureframelock). (2 propiedades) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Devuelve el objeto de estilo de la forma. Solo lectura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Devuelve o establece el tipo AutoShape para un PictureFrame. Todos los elementos permitidos del conjunto [`ShapeType`](../shapetype), excepto todo tipo de líneas: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva padre de una forma. Solo lectura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene las propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Especifica la duración en milisegundos que se eliminará del final de los medios durante la reproducción. Lectura/escritura Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Especifica la duración en milisegundos que se eliminará del principio de los medios durante la reproducción. Lectura/escritura Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Devuelve un identificador interno con ámbito de presentación destinado a ser usado por complementos u otro código. Como este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura UInt32. Ver también [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Devuelve o establece el volumen del audio. Lectura/escritura [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Devuelve o establece el volumen del audio en porcentajes. Lectura/escritura Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtiene o establece el ancho de la forma, medido en puntos. Lectura/escritura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtiene o establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtiene o establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura/escritura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma más atrás del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma más al frente del orden Z. Solo lectura Int32. |

## Métodos

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador de posición si no existe y establece sus propiedades al especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea y devuelve una matriz de elementos de la forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que hereda la forma actual). Se devuelve null si la forma actual no hereda. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Devuelve la miniatura de la forma. Por defecto se usa el tipo ShapeThumbnailBounds.Shape para los límites de la miniatura. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador de posición. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Actualiza la geometría de la forma a partir del objeto [`IGeometryPath`](../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype)) a Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Actualiza la geometría de la forma a partir de la matriz de [`IGeometryPath`](../igeometrypath). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([`ShapeType`](../geometryshape/shapetype)) a Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de la Forma como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de la Forma como archivo SVG. |

### Ejemplos

El siguiente ejemplo muestra cómo cambiar las opciones de reproducción de audio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Obtiene la forma AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Establece el modo de reproducción a reproducir al hacer clic
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Establece el volumen a bajo
    audioFrame.Volume = AudioVolumeMode.Low;
    // Configura el audio para reproducirse en todas las diapositivas
    audioFrame.PlayAcrossSlides = true;
    // Desactiva el bucle para el audio
    audioFrame.PlayLoopMode = false;
    // Oculta el AudioFrame durante la presentación
    audioFrame.HideAtShowing = true;
    // Rebobina el audio al inicio después de reproducir
    audioFrame.RewindAudio = true;
    // Guarda el archivo PowerPoint en disco
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Ver también

* clase [PictureFrame](../pictureframe)
* interfaz [IAudioFrame](../iaudioframe)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->