---
title: AutoShape
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta un'AutoShape.
type: docs
weight: 880
url: /it/aspose.slides/autoshape/
---
## AutoShape classe

Rappresenta un'AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Restituisce una raccolta di valori di regolazione della forma. Solo lettura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/scrittura String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Restituisce i blocchi dell'autoshape. Solo lettura [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà renderizzata nella modalità di visualizzazione in bianco e nero. Lettura/scrittura [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Solo lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Solo lettura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di effetto. Solo lettura [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione del riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di riempimento. Solo lettura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce le proprietà del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Restituisce o imposta l'altezza della forma, misurata in punti. Lettura/scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Solo lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Restituisce o imposta l'opzione 'Segna come decorativo'. Lettura/scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Solo lettura Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Specificare se la forma è una casella di testo. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Solo lettura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di linea. Solo lettura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Non deve essere null. Utilizzare una stringa vuota se necessario. Lettura/scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Solo lettura UInt32. Vedi anche [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce null. Solo lettura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha segnaposto. Solo lettura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione padre di una diapositiva. Solo lettura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/scrittura Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Restituisce i blocchi della forma. Solo lettura [`IAutoShapeLock`](../iautoshapelock). (2 proprietà) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Restituisce l'oggetto stile della forma. Solo lettura [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Restituisce o imposta il tipo predefinito di geometria. Nota: al cambiamento del valore tutti i valori di regolazione verranno ripristinati ai valori predefiniti. Lettura/scrittura [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva padre di una forma. Solo lettura [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Restituisce l'oggetto TextFrame per l'AutoShape. Solo lettura [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3D. Solo lettura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato una chiave univoca persistente. Solo lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Determina se questa autoshape deve essere riempita con il riempimento di sfondo della diapositiva invece di quello specificato dallo stile o dal formato di riempimento. Lettura/scrittura Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Restituisce o imposta la larghezza della forma, misurata in punti. Lettura/scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Restituisce o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Restituisce o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più in fondo all'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano dell'ordine Z. Solo lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non ne esiste e imposta le proprietà del segnaposto a quello specificato. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Aggiunge un nuovo TextFrame a una forma. Se la forma ha già un TextFrame, ne cambia semplicemente il testo. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Crea e restituisce un array degli elementi della forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Restituisce la copia del percorso della forma geometrica. Le coordinate sono relative all'angolo superiore sinistro della forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Restituisce i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) a Personalizzata. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Aggiorna la geometria della forma dall'array di [`IGeometryPath`](../igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`ShapeType`](../geometryshape/shapetype)) a Personalizzata. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* classe [GeometryShape](../geometryshape)
* interfaccia [IAutoShape](../iautoshape)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->