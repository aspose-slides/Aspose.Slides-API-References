---
title: MasterSlide
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una diapositiva master in una presentazione.
type: docs
weight: 8010
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
| [Background](../../aspose.slides/baseslide/background) { get; } | Restituisce lo sfondo della diapositiva. Sola lettura [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Restituisce lo stile di un testo del corpo. Sola lettura [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Restituisce la raccolta di controlli ActiveX su una diapositiva. Sola lettura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Restituisce i dati personalizzati della diapositiva. Sola lettura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Restituisce una raccolta di guide di disegno per la diapositiva master. Sola lettura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Restituisce true se esiste almeno una diapositiva che dipende da questa diapositiva master. Sola lettura Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Restituisce il gestore HeaderFooter della diapositiva master. Sola lettura [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Sola lettura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Restituisce la raccolta di diapositive layout figlio per questa diapositiva master. Sola lettura [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Restituisce o imposta il nome di una diapositiva master. Lettura/scrittura String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Restituisce lo stile di un altro testo. Sola lettura [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Restituisce l'interfaccia IPresentation. Sola lettura [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determina se il master corrispondente viene eliminato quando tutte le diapositive che seguono quel master vengono eliminate. Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo; per rimuovere effettivamente i master inutilizzati chiamare [`RemoveUnused`](../masterslidecollection/removeunused). Lettura/scrittura Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Restituisce le forme di una diapositiva. Sola lettura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Specifica se le forme sulla diapositiva master devono essere visualizzate sulle diapositive o meno. Per la diapositiva master stessa questa proprietà restituisce sempre `false`. Lettura/scrittura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Restituisce l'ID di una diapositiva. Sola lettura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Restituisce l'oggetto Transition che contiene informazioni su come la diapositiva specificata avanza durante la presentazione. Sola lettura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Restituisce il gestore del tema. Sola lettura [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Restituisce l'oggetto timeline dell'animazione. Sola lettura [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Restituisce lo stile di un testo del titolo. Sola lettura [`ITextStyle`](../itextstyle). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crea una nuova diapositiva master basata su quella corrente, applicando un tema esterno e applica la diapositiva master creata a tutte le diapositive dipendenti. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Restituisce un tema efficace per questa diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se le due istanze IBaseSlide sono uguali. Il valore restituito è calcolato in base alla struttura della diapositiva e al contenuto statico. Due diapositive sono uguali se tutte le forme, gli stili, i testi, le animazioni e altre impostazioni, ecc., sono uguali. Il confronto non tiene conto dei valori degli identificatori unici, ad es. SlideId, né del contenuto dinamico, ad es. il valore della data corrente nel segnaposto Data. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Trova la prima occorrenza di una forma con il testo alternativo specificato. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva master. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Unisce le sequenze con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Unisce le sequenze con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili. |

### Vedi anche

* classe [BaseSlide](../baseslide)
* interfaccia [IMasterSlide](../imasterslide)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->