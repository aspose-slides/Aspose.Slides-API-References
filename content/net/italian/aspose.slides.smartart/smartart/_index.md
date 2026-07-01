---
title: SmartArt
second_title: Aspose.Sildes per il riferimento API .NET
description: Rappresenta un diagramma SmartArt
type: docs
weight: 10580
url: /it/aspose.slides.smartart/smartart/
---
## classe SmartArt

Rappresenta un diagramma SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Proprietà

| Name | Description |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Restituisce le collezioni di tutti i nodi nell'oggetto SmartArt. Sola lettura [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà renderizzata in modalità bianco-nero. Lettura/Scrittura [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Restituisce o imposta lo stile colore dell'oggetto SmartArt. Lettura/Scrittura [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Sola lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Sola lettura [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di effetto. Sola lettura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di riempimento. Sola lettura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del riquadro della forma. Lettura/Scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/Scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/Scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Sola lettura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/Scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ottiene o imposta l'opzione 'Segna come decorativo'. Lettura/Scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Sola lettura Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Restituisce o imposta lo stato del diagramma SmartArt rispetto a LTR (da sinistra a destra) o RTL (da destra a sinistra), se il diagramma supporta l'inversione. Lettura/Scrittura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Sola lettura Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Restituisce o imposta il layout dell'oggetto SmartArt. Lettura/Scrittura [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di linea. Sola lettura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Deve essere non nullo. Utilizzare la stringa vuota se necessario. Lettura/Scrittura String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Restituisce le collezioni di nodi radice nell'oggetto SmartArt. Sola lettura [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento in modo affidabile alla forma da qualsiasi punto del documento. Sola lettura UInt32. Vedi anche [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto parent GroupShape se la forma è raggruppata. Altrimenti restituisce null. Sola lettura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha segnaposto. Sola lettura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una diapositiva. Sola lettura [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Restituisce o imposta lo stile rapido dell'oggetto SmartArt. Lettura/Scrittura [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del riquadro della forma. Lettura/Scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 proprietá) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva genitore di una forma. Sola lettura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà dell'effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3D. Sola lettura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave univoca persistente. Sola lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/Scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più arretrata nell'ordine Z e Shapes[Shapes.Count - 1] restituisce la forma più anteriore. Sola lettura Int32. |

## Metodi

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non ce n'è e imposta le proprietà del segnaposto a quello specificato. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* classe [GraphicalObject](../../aspose.slides/graphicalobject)
* interfaccia [ISmartArt](../ismartart)
* spazio dei nomi [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->