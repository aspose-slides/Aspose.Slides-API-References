---
title: AudioFrame
second_title: Aspose.Sildes per la Documentazione API .NET
description: Rappresenta una clip audio in una diapositiva.
type: docs
weight: 870
url: /it/aspose.slides/audioframe/
---
## AudioFrame classe

Rappresenta una clip audio in una diapositiva.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Restituisce una collezione dei valori di regolazione della forma. Solo lettura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/scrittura String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Restituisce o imposta l'indice dell'ultima traccia. Lettura/scrittura Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Restituisce o imposta il tempo dell'ultima traccia. Lettura/scrittura Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Restituisce o imposta l'indice della traccia iniziale. Lettura/scrittura Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Restituisce o imposta il tempo della traccia iniziale. Lettura/scrittura Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà visualizzata in modalità bianco-e-nero. Lettura/scrittura [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | Ottiene la collezione dei sottotitoli chiusi associati al frame audio. Questa proprietà è solo lettura e restituisce un [`ICaptionsCollection`](../icaptionscollection) contenente tutte le tracce di sottotitoli. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Solo lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Solo lettura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di effetto. Solo lettura [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Determina se un suono è incorporato in una presentazione. Solo lettura Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Restituisce o imposta l'oggetto audio incorporato. Lettura/scrittura [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Specifica la durata in millisecondi della dissolvenza iniziale del media. Lettura/scrittura Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Specifica la durata in millisecondi della dissolvenza finale del media. Lettura/scrittura Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di riempimento. Solo lettura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/scrittura Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Determina se un AudioFrame è nascosto. Lettura/scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta l'ipertesto definito per il clic del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore degli ipertesti. Solo lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta l'ipertesto definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina se il PictureFrame è un oggetto Cameo o meno. Solo lettura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ottiene o imposta l'opzione 'Segna come decorativo'. Lettura/scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Solo lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Solo lettura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di linea. Solo lettura [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Restituisce o imposta il nome di un file audio collegato a un AudioFrame. Lettura/scrittura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Non deve essere nullo. Utilizzare una stringa vuota se necessario. Lettura/scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura UInt32. Vedi anche [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Restituisce l'oggetto PictureFillFormat per un frame immagine. Solo lettura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha un segnaposto. Solo lettura [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Determina se l'audio è riprodotto attraverso le diapositive. Lettura/scrittura Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Determina se l'audio è ripetuto in loop. Lettura/scrittura Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Restituisce o imposta la modalità di riproduzione audio. Lettura/scrittura [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una diapositiva. Solo lettura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Restituisce o imposta la scala dell'altezza (relativa alle dimensioni dell'immagine originale) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Restituisce o imposta la scala della larghezza (relativa alle dimensioni dell'immagine originale) del frame immagine. Il valore 1.0 corrisponde al 100%. Lettura/scrittura Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Determina se l'audio è riportato automaticamente all'inizio dopo la riproduzione. Lettura/scrittura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/scrittura Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IPictureFrameLock`](../ipictureframelock). (2 proprietà) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Restituisce l'oggetto stile della forma. Solo lettura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Restituisce o imposta il tipo AutoShape per un PictureFrame. Sono consentiti tutti gli elementi del set [`ShapeType`](../shapetype), tranne tutti i tipi di linee: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva padre di una forma. Solo lettura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà 3D. Solo lettura [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Specifica la durata da rimuovere dalla fine del media durante la riproduzione, in millisecondi. Lettura/scrittura Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Specifica la durata da rimuovere dall'inizio del media durante la riproduzione, in millisecondi. Lettura/scrittura Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come chiave unica persistente. Solo lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Restituisce o imposta il volume audio. Lettura/scrittura [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Restituisce o imposta il volume audio in percentuale. Lettura/scrittura Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più indietro nell'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in avanti. Solo lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto su quello specificato. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea e restituisce un array degli elementi della forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo di limiti della miniatura ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aggiorna la geometria della forma dal oggetto [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) in Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) in Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Esempi

Il seguente esempio mostra come modificare le opzioni di riproduzione audio.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Ottiene la forma AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Imposta la modalità di riproduzione su riproduci al clic
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Imposta il volume su Basso
    audioFrame.Volume = AudioVolumeMode.Low;
    // Imposta l'audio per riprodursi attraverso le diapositive
    audioFrame.PlayAcrossSlides = true;
    // Disabilita il loop per l'audio
    audioFrame.PlayLoopMode = false;
    // Nasconde l'AudioFrame durante la presentazione
    audioFrame.HideAtShowing = true;
    // Riavvolge l'audio all'inizio dopo la riproduzione
    audioFrame.RewindAudio = true;
    // Salva il file PowerPoint su disco
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* classe [PictureFrame](../pictureframe)
* interfaccia [IAudioFrame](../iaudioframe)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->