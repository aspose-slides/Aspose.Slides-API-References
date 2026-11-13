---
title: Slide
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een dia in een presentatie voor.
type: docs
weight: 9980
url: /nl/aspose.slides/slide/
---
## Slide klasse

Stelt een dia in een presentatie voor.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retourneert de achtergrond van de dia. Alleen-lezen [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retourneert de verzameling ActiveX-besturingselementen op een dia. Alleen-lezen [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retourneert de aangepaste gegevens van de dia. Alleen-lezen [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Retourneert de HeaderFooter-beheerder van de dia. Alleen-lezen [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/Schrijven Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Biedt gemakkelijke toegang tot de opgenomen hyperlinks. Alleen-lezen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Retourneert of stelt de layout-dia voor de huidige dia in. Lezen/Schrijven [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Retourneert of stelt de naam van een dia in. Lezen/Schrijven String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Staat toe om de notitiedia te benaderen, toe te voegen en te verwijderen. Alleen-lezen [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retourneert de IPresentation-interface. Alleen-lezen [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retourneert de vormen van een dia. Alleen-lezen [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Bepaalt of vormen op de hoofd-dia getoond moeten worden op dia’s. Lezen/Schrijven Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retourneert de ID van een dia. Alleen-lezen UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Retourneert een volgnummer van de dia. Index van de dia in de [`Slides`](../presentation/slides)-verzameling is altijd gelijk aan SlideNumber - Presentation.FirstSlideNumber. Lezen/Schrijven Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling vordert. Alleen-lezen [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Retourneert de overschrijvende themabeheerder. Alleen-lezen [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retourneert het animatietijdlijn-object. Alleen-lezen [`IAnimationTimeLine`](../ianimationtimeline). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retourneert een effectief thema voor deze dia. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De teruggegeven waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia’s zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. Bij de vergelijking worden unieke identifier-waarden, zoals SlideId, en dynamische inhoud, zoals de huidige datumwaarde in een Datum-placeholder, niet meegenomen. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Vindt de eerste instantie van een vorm met de opgegeven alternatieve tekst. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Retourneert een miniatuur-afbeeldingsobject (20 % van de werkelijke grootte). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Retourneert een miniatuur-afbeeldingsobject. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Retourneert een miniatuur-tiff-afbeeldingsobject met de opgegeven parameters. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Retourneert een miniatuur-afbeeldingsobject met de opgegeven grootte. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Retourneert een miniatuur-afbeeldingsobject met aangepaste schaling. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Retourneert een miniatuur-afbeeldingsobject met de opgegeven grootte. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Retourneert een miniatuur-afbeeldingsobject met aangepaste schaling. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Retourneert alle dia-commentaren die door een specifieke auteur zijn toegevoegd. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Voegt runs met dezelfde opmaak samen in alle alinea’s in alle geschikte vormen. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Voegt runs met dezelfde opmaak samen in alle alinea’s in alle geschikte vormen. |
| [Remove](../../aspose.slides/slide/remove)() | Verwijdert de dia uit de presentatie. |
| [Reset](../../aspose.slides/slide/reset)() | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Slaat de inhoud van de dia op als een EMF-bestand. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Slaat de inhoud van de dia op als een SVG-bestand. |

### Zie ook

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->