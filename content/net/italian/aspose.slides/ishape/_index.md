---
title: IShape
second_title: Riferimento API di Aspose.Sildes per .NET
description: Rappresenta una forma su una diapositiva.
type: docs
weight: 6930
url: /it/aspose.slides/ishape/
---
## IShape interfaccia

Rappresenta una forma su una diapositiva.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Read/write String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Consente di ottenere l'interfaccia base IHyperlinkContainer. Read-only [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Consente di ottenere l'interfaccia base ISlideComponent. Read-only [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero. Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Restituisce il numero di punti di collegamento sulla forma. Read-only Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Restituisce i dati personalizzati della forma. Read-only [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Read-only [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Restituisce o imposta le proprietà del frame della forma. Read/write [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Restituisce o imposta l'altezza della forma, misurata in punti. Read/write Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determina se la forma è nascosta. Read/write Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Restituisce o imposta l'opzione 'Mark as decorative'. Read/write Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determina se la forma è raggruppata. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determina se la forma è TextHolder. Read-only Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Restituisce o imposta il nome di una forma. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Restituisce un identificatore unico a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento. Read-only UInt32. Vedi anche [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce null. Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Restituisce il segnaposto per una forma. Read-only [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Read/write [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Read/write Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Restituisce i blocchi della forma. Read-only [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di formattazione della linea per una forma. Read-only [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di add-in o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere trattato come una chiave unica persistente. Read-only UInt32. Vedi anche [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Restituisce o imposta la larghezza della forma, misurata in punti. Read/write Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Restituisce o imposta la coordinata x dell'angolo superiore sinistro della forma, misurata in punti. Read/write Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Restituisce o imposta la coordinata y dell'angolo superiore sinistro della forma, misurata in punti. Read/write Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine z. Shapes[0] restituisce la forma più arretrata nell'ordine z, e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine z. Read-only Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo segnaposto se non esiste e imposta le proprietà del segnaposto su quello specificato. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Restituisce una forma segnaposto di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape per i limiti della miniatura della forma è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Definisce che questa forma non è un segnaposto. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Salva il contenuto della Forma come file SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Salva il contenuto della Forma come file SVG. |

### Vedi anche

* interfaccia [IHyperlinkContainer](../ihyperlinkcontainer)
* interfaccia [ISlideComponent](../islidecomponent)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->