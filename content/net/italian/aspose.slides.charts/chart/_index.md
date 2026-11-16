---
title: Chart
second_title: Aspose.Sildes per .NET API Reference
description: Rappresenta un grafico su una diapositiva.
type: docs
weight: 1270
url: /it/aspose.slides.charts/chart/
---
## Chart classe

Rappresenta un grafico su una diapositiva.

```csharp
public class Chart : GraphicalObject, IChart
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Restituisce o imposta il testo alternativo associato a una forma. Lettura/Scrittura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Restituisce o imposta il titolo del testo alternativo associato a una forma. Lettura/Scrittura String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Permette di ottenere l'interfaccia IFormattedTextContainer di base. Sola lettura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Permette di ottenere l'interfaccia IThemeable di base. Sola lettura [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Fornisce l'accesso agli assi del grafico. Sola lettura [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Restituisce un oggetto che consente di modificare il formato della parete posteriore di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La proprietà specifica come una forma verrà visualizzata in modalità bianco e nero.. Lettura/Scrittura [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Restituisce informazioni sui dati collegati o incorporati associati a un grafico. Sola lettura [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Restituisce una tabella dei dati di un grafico. Sola lettura [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Restituisce o imposta il titolo del grafico. Sola lettura [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Restituisce il numero di punti di connessione sulla forma. Sola lettura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Restituisce i dati personalizzati della forma. Sola lettura [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Restituisce o imposta il modo di tracciare le celle vuote su un grafico. Lettura/Scrittura [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Restituisce l'oggetto EffectFormat che contiene gli effetti pixel applicati a una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di effetto. Sola lettura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di riempimento. Sola lettura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Restituisce un oggetto che consente di modificare il formato del pavimento di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Restituisce o imposta le proprietà del frame della forma. Lettura/Scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Determina se un grafico ha una tabella dei dati. Lettura/Scrittura Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Determina se un grafico ha una legenda. Lettura/Scrittura Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Specifica se l'area del grafico deve avere angoli arrotondati. Lettura/Scrittura Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Determina se un grafico ha un titolo visibile. Lettura/Scrittura Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Restituisce o imposta l'altezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se la forma è nascosta. Lettura/Scrittura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il clic del mouse. Lettura/Scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Restituisce il gestore dei collegamenti ipertestuali. Sola lettura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/Scrittura [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Restituisce o imposta l'opzione 'Mark as decorative'. Lettura/Scrittura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se la forma è raggruppata. Sola lettura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se la forma è TextHolder_PPT. Sola lettura Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Restituisce o imposta una legenda per un grafico. Sola lettura [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Restituisce l'oggetto LineFormat che contiene le proprietà di formattazione della linea per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà di linea. Sola lettura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Restituisce o imposta il nome di una forma. Non deve essere null. Usa una stringa vuota se necessario. Lettura/Scrittura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Restituisce un identificatore univoco a livello di diapositiva che rimane costante per la durata della forma e consente a PowerPoint o al codice interop di fare riferimento alla forma in modo affidabile da qualsiasi punto del documento. Sola lettura UInt32. Vedi anche [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Restituisce l'oggetto GroupShape padre se la forma è raggruppata. Altrimenti restituisce null. Sola lettura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Restituisce il placeholder per una forma. Restituisce null se la forma non ha placeholder. Sola lettura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Rappresenta l'area di tracciamento di un grafico. Sola lettura [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Determina se vengono tracciate solo le celle visibili. False per tracciare sia le celle visibili che quelle nascoste. Lettura/Scrittura Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Restituisce la presentazione padre di una diapositiva. Sola lettura [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Restituisce o imposta le proprietà grezze del frame della forma. Lettura/Scrittura [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Restituisce o imposta il numero di gradi di rotazione della forma specificata attorno all'asse z. Un valore positivo indica rotazione in senso orario; un valore negativo indica rotazione in senso antiorario. Lettura/Scrittura Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Restituisce una rotazione 3D di un grafico. Sola lettura [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Restituisce i blocchi della forma. Sola lettura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Specifica se devono essere visualizzate le etichette dei dati oltre il massimo del grafico. Lettura/Scrittura Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Restituisce un oggetto che consente di modificare il formato della parete laterale di un grafico 3D. Sola lettura [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Restituisce la diapositiva padre di una forma. Sola lettura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Restituisce o imposta lo stile del grafico. Lettura/Scrittura [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Restituisce il formato del testo del grafico. La proprietà non è applicabile per i seguenti tipi: Treemap, Sunburst, Waterfall, Histogram, Funnel,BoxAndWhisker. Sola lettura [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Restituisce il gestore del tema. Sola lettura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che contiene le proprietà di effetto 3D per una forma. Nota: può restituire null per alcuni tipi di forme che non hanno proprietà 3D. Sola lettura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Restituisce o imposta il tipo di grafico. Lettura/Scrittura [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Restituisce un identificatore interno a livello di presentazione destinato all'uso da parte di componenti aggiuntivi o altro codice. Poiché questo valore può essere riassegnato dall'utente o programmaticamente, non deve essere considerato una chiave univoca persistente. Sola lettura UInt32. Vedi anche [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Specifica le forme disegnate sopra il grafico. Sola lettura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Restituisce o imposta la larghezza della forma, misurata in punti. Lettura/Scrittura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Restituisce o imposta la coordinata x dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/Scrittura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Restituisce o imposta la coordinata y dell'angolo in alto a sinistra della forma, misurata in punti. Lettura/Scrittura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Restituisce la posizione di una forma nell'ordine z. Shapes[0] restituisce la forma più arretrata nell'ordine z, e Shapes[Shapes.Count - 1] restituisce la forma più in avanti nell'ordine z. Sola lettura Int32. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Aggiunge un nuovo placeholder se non esiste e imposta le proprietà del placeholder su quello specificato. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Restituisce un tema efficace per questo grafico. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Restituisce una forma placeholder di base (forma dal layout e/o dalla diapositiva master da cui la forma corrente è ereditata). Viene restituito null se la forma corrente non è ereditata. |
| [GetImage](../../aspose.slides/shape/getimage)() | Restituisce la miniatura della forma. Il tipo ShapeThumbnailBounds.Shape è usato per impostazione predefinita. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Restituisce la miniatura della forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Restituisce i confini visivi della forma calcolati dal contenuto renderizzato. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definisce che questa forma non è un placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Calcola i valori effettivi degli elementi del grafico. I valori effettivi includono la posizione degli elementi che implementano l'interfaccia IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e i valori reali degli assi (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva il contenuto della Shape in un file SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva il contenuto della Shape in un file SVG. |

### Vedi anche

* classe [GraphicalObject](../../aspose.slides/graphicalobject)
* interfaccia [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->