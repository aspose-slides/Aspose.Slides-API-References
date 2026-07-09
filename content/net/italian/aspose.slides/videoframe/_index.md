---
title: VideoFrame
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una clip video su una diapositiva.
type: docs
weight: 11720
url: /it/aspose.slides/videoframe/
---
## VideoFrame classe

Rappresenta una clip video su una diapositiva.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Restituisce una raccolta dei valori di regolazione della forma. Solo lettura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/scrittura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Lettura/scrittura [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Ottiene la raccolta dei sottotitoli chiusi associati al video frame. Questa proprietà è sola lettura e restituisce un [`ICaptionsCollection`](../icaptionscollection) contenente tutte le tracce dei sottotitoli. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Solo lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Solo lettura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di effetto. Solo lettura [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Restituisce o imposta l'oggetto video incorporato. Lettura/scrittura [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di riempimento. Solo lettura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Determina se un video è mostrato a schermo intero. Lettura/scrittura Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/scrittura Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Determina se un VideoFrame è nascosto. Lettura/scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Solo lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina se il PictureFrame è un oggetto Cameo o meno. Solo lettura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ottiene o imposta l'opzione 'Mark as decorative'. Lettura/scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Solo lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Solo lettura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di linea. Solo lettura [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Restituisce o imposta il nome di un file video collegato a un VideoFrame. Lettura/scrittura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Lettura/scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura UInt32. Vedi anche [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Restituisce l'oggetto PictureFillFormat per un picture frame. Solo lettura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha un segnaposto. Solo lettura [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Determina se un video è in loop. Lettura/scrittura Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Restituisce o imposta la modalità di riproduzione video. Lettura/scrittura [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una diapositiva. Solo lettura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Restituisce o imposta la scala dell'altezza (relativa alla dimensione originale dell'immagine) del picture frame. Il valore 1.0 corrisponde al 100%. Lettura/scrittura Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Restituisce o imposta la scala della larghezza (relativa alla dimensione originale dell'immagine) del picture frame. Il valore 1.0 corrisponde al 100%. Lettura/scrittura Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Determina se un video viene riportato automaticamente all'inizio non appena il film termina la riproduzione. Lettura/scrittura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/scrittura Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IPictureFrameLock`](../ipictureframelock). (2 proprietà) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Restituisce l'oggetto stile della forma. Solo lettura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Restituisce o imposta il tipo AutoShape per un PictureFrame. Sono consentiti tutti gli elementi del set [`ShapeType`](../shapetype), ad eccezione di tutti i tipi di linee: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva genitore di una forma. Solo lettura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3d per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3d. Solo lettura [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Ritaglia fine [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Ritaglia inizio [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave univoca persistente. Solo lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Restituisce o imposta il volume audio. Lettura/scrittura [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più in fondo dell'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano dell'ordine Z. Solo lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quella specificata. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea e restituisce un array degli elementi della forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente eredita). Viene restituito null se la forma corrente non è ereditata. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Restituisce una copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo di bordi ShapeThumbnailBounds.Shape per la miniatura della forma è usato di default. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ottiene i limiti visivi della forma calcolati dal contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) in Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) in Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* classe [PictureFrame](../pictureframe)
* interfaccia [IVideoFrame](../ivideoframe)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->