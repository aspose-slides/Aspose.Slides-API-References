---
title: SmartArtShape
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta la forma SmartArt
type: docs
weight: 10660
url: /it/aspose.slides.smartart/smartartshape/
---
## SmartArtShape classe

Rappresenta la forma SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Restituisce una collezione di valori di regolazione della forma. Solo lettura [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/scrittura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà renderizzata in modalità bianco e nero. Lettura/scrittura [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Solo lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Solo lettura [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di effetto. Solo lettura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di riempimento. Solo lettura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del riquadro della forma. Lettura/scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse. Lettura/scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Solo lettura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ottiene o imposta l'opzione 'Mark as decorative'. Lettura/scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Solo lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Solo lettura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di linea. Solo lettura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Deve essere non nullo. Usa una stringa vuota se necessario. Lettura/scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di slide che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di riferirsi in modo affidabile alla forma da qualsiasi parte del documento. Solo lettura UInt32. Vedi anche [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha segnaposto. Solo lettura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una slide. Solo lettura [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del riquadro della forma. Lettura/scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/scrittura Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Restituisce l'oggetto stile della forma. Solo lettura [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Restituisce o imposta il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti. Lettura/scrittura [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la slide genitore di una forma. Solo lettura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Restituisce il testo della forma SmartArt. Solo lettura [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà 3D. Solo lettura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave unica permanente. Solo lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma in fondo all'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma in primo piano dell'ordine Z. Solo lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto a quello specificato. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea e restituisce un array di elementi della forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo in alto a sinistra della forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce l'anteprima della forma. Il tipo di limiti di anteprima ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce l'anteprima della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](../../aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo in alto a sinistra della forma. Cambia il tipo della forma ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) in Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aggiorna la geometria della forma da un array di [`IGeometryPath`](../../aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo in alto a sinistra della forma. Cambia il tipo della forma ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) in Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* classe [GeometryShape](../../aspose.slides/geometryshape)
* interfaccia [ISmartArtShape](../ismartartshape)
* spazio dei nomi [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->