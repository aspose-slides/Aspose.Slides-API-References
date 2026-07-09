---
title: Slide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een dia in een presentatie voor.
type: docs
weight: 9960
url: /nl/aspose.slides/slide/
---
## Slide klasse

Representeert een dia in een presentatie.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Geeft de achtergrond van de dia terug. Alleen-lezen [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Geeft de verzameling van ActiveX-besturingselementen op een dia terug. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Geeft de aangepaste gegevens van de dia terug. Alleen-lezen [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Geeft de HeaderFooter-manager van de dia terug. Alleen-lezen [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/Schrijven Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot de ingesloten hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Geeft de lay-outdia voor de huidige dia terug of stelt deze in. Lezen/Schrijven [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Geeft de naam van een dia terug of stelt deze in. Lezen/Schrijven String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Staat toegang tot de notitiesdia toe, en maakt toevoegen en verwijderen mogelijk. Alleen-lezen [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Geeft de IPresentation-interface terug. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Geeft de vormen van een dia terug. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Geeft aan of vormen op de meesterdia al dan niet op dia's moeten worden weergegeven. Lezen/Schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Geeft de ID van een dia terug. Alleen-lezen UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Geeft een nummer van de dia terug. De index van een dia in [`Slides`](../presentation/slides)-collectie is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/Schrijven Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Geeft het Transition-object terug dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Geeft de overschrijfende themamanager terug. Alleen-lezen [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Geeft het animatie-tijdlijnobject terug. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |

## Methodes

| Naam | Beschrijving |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Geeft een effectief thema voor deze dia terug. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur van de dia en statische inhoud. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz. gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, bijvoorbeeld SlideId, en dynamische inhoud, bijvoorbeeld de huidige datumwaarde in Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Zoekt de eerste verschijning van een vorm met de opgegeven alternatieve tekst. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Geeft een Thumbnail Image-object terug (20 % van de werkelijke grootte). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Geeft een Thumbnail Image-object terug. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Geeft een Thumbnail-tiff-image-object terug met opgegeven parameters. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Geeft een Thumbnail Image-object terug met opgegeven grootte. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Geeft een Thumbnail Image-object terug met aangepaste schaling. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Geeft een Thumbnail Image-object terug met opgegeven grootte. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Geeft een Thumbnail Image-object terug met aangepaste schaling. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Geeft alle dia-opmerkingen terug die door een specifieke auteur zijn toegevoegd. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen. |
| [Remove](../../aspose.slides/slide/remove)() | Verwijdert de dia uit de presentatie. |
| [Reset](../../aspose.slides/slide/reset)() | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Slaat de inhoud van de dia op als een EMF-bestand. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slaat de inhoud van de dia op als een SVG-bestand. |

### Zie ook

* klasse [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->