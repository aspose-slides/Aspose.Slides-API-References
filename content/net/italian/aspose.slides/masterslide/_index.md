---
title: MasterSlide
second_title: Aspose.Sildes per .NET - Riferimento API
description: Rappresenta una diapositiva master in una presentazione.
type: docs
weight: 8050
url: /it/aspose.slides/masterslide/
---
## MasterSlide classe

Rappresenta una diapositiva master in una presentazione.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Restituisce lo sfondo della diapositiva. Solo lettura [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Restituisce lo stile del testo del corpo. Solo lettura [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Restituisce la raccolta di controlli ActiveX su una diapositiva. Solo lettura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Restituisce i dati personalizzati della diapositiva. Solo lettura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Restituisce una raccolta di guide di disegno per la diapositiva master. Solo lettura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Restituisce true se esiste almeno una diapositiva che dipende da questa master slide. Solo lettura Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Restituisce il gestore HeaderFooter della master slide. Solo lettura [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornisce un accesso facile ai collegamenti ipertestuali contenuti. Solo lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Restituisce la raccolta di layout slide figlio per questa master slide. Solo lettura [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Restituisce o imposta il nome di una master slide. Lettura/Scrittura String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Restituisce lo stile di un altro testo. Solo lettura [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Restituisce l'interfaccia IPresentation. Solo lettura [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determina se la master corrispondente viene eliminata quando tutte le slide che seguono quella master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcuna master inutilizzata da solo; per rimuovere realmente le master inutilizzate chiamare [`RemoveUnused`](../masterslidecollection/removeunused) Lettura/Scrittura Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Restituisce le forme di una diapositiva. Solo lettura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Specifica se le forme sulla master slide devono essere mostrati sulle slide o meno. Per la master slide stessa questa proprietà restituisce sempre `false`. Lettura/Scrittura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Restituisce l'ID di una diapositiva. Solo lettura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante una presentazione. Solo lettura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Restituisce il gestore del tema. Solo lettura [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Restituisce l'oggetto della timeline di animazione. Solo lettura [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Restituisce lo stile del testo del titolo. Solo lettura [`ITextStyle`](../itextstyle). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crea una nuova master slide basata su quella corrente, applicando un tema esterno e applica la master slide creata a tutte le slide dipendenti. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Restituisce un tema efficace per questa slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se le due istanze IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della slide e al contenuto statico. Due slide sono uguali se tutte le forme, stili, testi, animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad es. SlideId e contenuto dinamico, ad es. valore della data corrente nel segnaposto Data. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Restituisce un array con tutte le slide che dipendono da questa master slide. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Unisce le esecuzioni con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Unisce le esecuzioni con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |

### Vedi anche

* classe [BaseSlide](../baseslide)
* interfaccia [IMasterSlide](../imasterslide)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->