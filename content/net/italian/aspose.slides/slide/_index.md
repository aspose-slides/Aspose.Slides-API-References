---
title: Slide
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta una diapositiva in una presentazione.
type: docs
weight: 9940
url: /it/aspose.slides/slide/
---
## Slide classe

Rappresenta una diapositiva in una presentazione.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Proprietà

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Restituisce lo sfondo della diapositiva. Solo lettura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Restituisce la raccolta di controlli ActiveX su una diapositiva. Solo lettura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Restituisce i dati personalizzati della diapositiva. Solo lettura [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Restituisce il gestore HeaderFooter della diapositiva. Solo lettura [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Determina se la diapositiva specificata è nascosta durante la presentazione. Lettura/scrittura Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Solo lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Restituisce o imposta la diapositiva di layout per la diapositiva corrente. Lettura/scrittura [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Restituisce o imposta il nome di una diapositiva. Lettura/scrittura String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla. Solo lettura [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Restituisce l'interfaccia IPresentation. Solo lettura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Restituisce le forme di una diapositiva. Solo lettura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o no. Lettura/scrittura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Restituisce l'ID di una diapositiva. Solo lettura UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Restituisce il numero di una diapositiva. L'indice della diapositiva nella collezione [`Slides`](../presentation/slides) è sempre uguale a SlideNumber - Presentation.FirstSlideNumber. Lettura/scrittura Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante la presentazione. Solo lettura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Restituisce il gestore del tema sovrascrivente. Solo lettura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Restituisce l'oggetto della linea temporale di animazione. Solo lettura [`IAnimationTimeLine`](../ianimationtimeline). |

## Metodi

| Name | Description |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Restituisce un tema efficace per questa diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se le due istanze IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori di identificatori unici, ad esempio SlideId, né del contenuto dinamico, ad esempio il valore della data corrente nel Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Restituisce un oggetto Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Restituisce un oggetto immagine tiff Thumbnail con i parametri specificati. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Restituisce un oggetto Thumbnail Image con la dimensione specificata. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Restituisce un oggetto Thumbnail Image con la dimensione specificata. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Unisce le sequenze con lo stesso formato in tutti i paragrafi di tutte le forme ammissibili. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Unisce le sequenze con lo stesso formato in tutti i paragrafi di tutte le forme ammissibili. |
| [Remove](../../aspose.slides/slide/remove)() | Rimuove la diapositiva dalla presentazione. |
| [Reset](../../aspose.slides/slide/reset)() | Ripristina posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Salva il contenuto della diapositiva come file EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Salva il contenuto della diapositiva come file SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Salva il contenuto della diapositiva come file SVG. |

### Vedi anche

* classe [BaseSlide](../baseslide)
* interfaccia [ISlide](../islide)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->