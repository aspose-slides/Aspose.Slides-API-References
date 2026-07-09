---
title: Table
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una tabella su una diapositiva.
type: docs
weight: 10860
url: /it/aspose.slides/table/
---
## Table classe

Rappresenta una tabella su una diapositiva.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/scrittura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà visualizzata in modalità bianco-nero. Lettura/scrittura [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Restituisce la raccolta di colonne. Sola lettura [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di collegamento sulla forma. Sola lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Sola lettura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di effetto. Sola lettura [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Restituisce un oggetto TableFormat.FillFormat contenente la formattazione di riempimento per la Table. Sola lettura [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Restituisce o imposta l'altezza della forma, misurata in punti. Lettura/scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/scrittura Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Determina se le righe pari devono essere disegnate con una formattazione diversa. Lettura/scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Sola lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Restituisce o imposta l'opzione 'Mark as decorative'. Lettura/scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Sola lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Sola lettura Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Restituisce la cella negli indici di colonna e riga specificati. Sola lettura [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/scrittura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà di linea. Sola lettura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Non deve essere nullo. Utilizzare una stringa vuota se necessario. Lettura/scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore unico a livello di diapositiva che rimane costante per tutta la durata della forma e consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento. Sola lettura UInt32. Vedi anche [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Sola lettura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha un segnaposto. Sola lettura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una diapositiva. Sola lettura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Lettura/scrittura [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Determina se la tabella ha l'ordine di lettura da destra a sinistra. Lettura/scrittura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/scrittura Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Restituisce la raccolta di righe. Sola lettura [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 proprietà) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva genitore di una forma. Sola lettura [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Restituisce o imposta lo stile tabella incorporato. Lettura/scrittura [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. Sola lettura [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà degli effetti 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non possiedono proprietà 3D. Sola lettura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno, a livello di presentazione, destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato una chiave unica persistente. Sola lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Determina se le colonne pari devono essere disegnate con una formattazione diversa. Lettura/scrittura Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Restituisce o imposta la larghezza della forma, misurata in punti. Lettura/scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Restituisce o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Restituisce o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Lettura/scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più in fondo nell'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano nell'ordine Z. Sola lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non presente e imposta le proprietà del segnaposto a quella specificata. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Restituisce i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Unisce le celle vicine. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Imposta le proprietà del formato di paragrafo definiti a tutti i paragrafi delle celle della tabella. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Imposta le proprietà del formato di porzione definiti a tutte le porzioni delle celle della tabella. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Imposta le proprietà del formato del frame di testo definiti a tutti i frame di testo delle celle della tabella. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Shape in un file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Shape in un file SVG. |

### Vedi anche

* classe [GraphicalObject](../graphicalobject)
* interfaccia [ITable](../itable)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->