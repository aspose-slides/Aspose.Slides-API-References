---
title: LayoutSlide
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta una diapositiva di layout.
type: docs
weight: 7620
url: /it/aspose.slides/layoutslide/
---
## LayoutSlide classe

Rappresenta una diapositiva di layout.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Restituisce lo sfondo della diapositiva. Solo lettura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Restituisce la raccolta dei controlli ActiveX su una diapositiva. Solo lettura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Restituisce i dati personalizzati della diapositiva. Solo lettura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Restituisce una raccolta di guide di disegno per la diapositiva di layout. Solo lettura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Restituisce vero se esiste almeno una diapositiva che dipende da questa diapositiva di layout. Solo lettura Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Restituisce il gestore HeaderFooter della diapositiva di layout. Solo lettura [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Solo lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Restituisce il tipo di layout di questa diapositiva di layout. Solo lettura [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Restituisce o imposta la diapositiva master per un layout. Lettura/scrittura [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Restituisce o imposta il nome di una diapositiva. Lettura/scrittura String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Restituisce il gestore dei segnaposto della diapositiva di layout. Solo lettura [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Restituisce l'interfaccia IPresentation. Solo lettura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Restituisce le forme di una diapositiva. Solo lettura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Specifica se le forme sulla diapositiva master devono essere mostrate sulle diapositive o meno. Lettura/scrittura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Restituisce l'ID di una diapositiva. Solo lettura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. Solo lettura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Restituisce il gestore del tema sovrascrivente. Solo lettura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Restituisce l'oggetto timeline di animazione. Solo lettura [`IAnimationTimeLine`](../ianimationtimeline). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Restituisce un tema efficace per questa diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se le due istanze di IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e le altre impostazioni, ecc., sono uguali. Il confronto non prende in considerazione i valori degli identificatori unici, ad esempio SlideId e i contenuti dinamici, ad esempio il valore della data corrente nel segnaposto Data. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Unisce le run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Unisce le run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Rimuove il layout dalla presentazione. |

### Vedi anche

* classe [BaseSlide](../baseslide)
* interfaccia [ILayoutSlide](../ilayoutslide)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->