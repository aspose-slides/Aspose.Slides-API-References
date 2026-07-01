---
title: Table
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una tabella in una diapositiva.
type: docs
weight: 10840
url: /it/aspose.slides/table/
---
## Classe Table

Rappresenta una tabella in una diapositiva.

```csharp
public sealed class Table : GraphicalObject, ITable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà renderizzata in modalità di visualizzazione in bianco e nero. Lettura/Scrittura [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | Restituisce la raccolta di colonne. Sola lettura [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Sola lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Sola lettura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di effetto. Sola lettura [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Restituisce un oggetto TableFormat.FillFormat che contiene la formattazione di riempimento per la Table. Sola lettura [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | Determina se la prima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/Scrittura Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | Determina se la prima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/Scrittura Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del riquadro della forma. Lettura/Scrittura [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Ottiene o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/Scrittura Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | Determina se le righe pari devono essere disegnate con una formattazione differente. Lettura/Scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse. Lettura/Scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore del collegamento ipertestuale. Sola lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/Scrittura [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Ottiene o imposta l'opzione 'Segna come decorativo'. Lettura/Scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Sola lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Sola lettura Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | Restituisce la cella negli indici di colonna e riga specificati. Sola lettura [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | Determina se l'ultima colonna di una tabella deve essere disegnata con una formattazione speciale. Lettura/Scrittura Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | Determina se l'ultima riga di una tabella deve essere disegnata con una formattazione speciale. Lettura/Scrittura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà di linea. Sola lettura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Non deve essere null. Utilizzare una stringa vuota se necessario. Lettura/Scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di riferirsi in modo affidabile alla forma da qualsiasi punto del documento. Sola lettura UInt32. Vedi anche [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape genitore se la forma è raggruppata. Altrimenti restituisce null. Sola lettura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il segnaposto per una forma. Restituisce null se la forma non ha un segnaposto. Sola lettura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione genitore di una diapositiva. Sola lettura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del riquadro della forma. Lettura/Scrittura [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | Determina se la tabella ha ordine di lettura da destra a sinistra. Lettura/Scrittura Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | Restituisce la raccolta di righe. Sola lettura [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 proprietà) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva genitore di una forma. Sola lettura [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | Ottiene o imposta lo stile di tabella incorporato. Lettura/Scrittura [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | Restituisce l'oggetto TableFormat che contiene le proprietà di formattazione per questa tabella. Sola lettura [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forma che non hanno proprietà 3D. Sola lettura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave univoca persistente. Sola lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | Determina se le colonne pari devono essere disegnate con una formattazione differente. Lettura/Scrittura Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Ottiene o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Ottiene o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/Scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Ottiene o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/Scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine Z. Shapes[0] restituisce la forma più in fondo nell'ordine Z, e Shapes[Shapes.Count - 1] restituisce la forma più in primo piano nell'ordine Z. Sola lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non ce n'è e imposta le proprietà del segnaposto su quello specificato. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è utilizzato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Ottiene i limiti visivi della forma calcolati dal suo contenuto renderizzato. |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | Unisce le celle vicine. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | Imposta le proprietà di formattazione del paragrafo definite su tutti i paragrafi delle celle della tabella. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | Imposta le proprietà di formattazione della porzione definite su tutte le porzioni delle celle della tabella. |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | Imposta le proprietà di formattazione del riquadro di testo definite su tutti i riquadri di testo delle celle della tabella. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* classe [GraphicalObject](../graphicalobject)
* interfaccia [ITable](../itable)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->