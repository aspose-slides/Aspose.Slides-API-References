---
title: MasterSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/masterslide/
---
## MasterSlide klasse

Stelt een masterdia voor in een presentatie.

**Erfenis:**[`MasterSlide`](/slides/python-net/nl/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)

Het type MasterSlide geeft de volgende leden weer:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`shapes`](/slides/python-net/nl/aspose.slides/masterslide/shapes/) | Geeft de vormen van een dia terug.<br/>            Alleen-lezen [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/nl/aspose.slides/masterslide/controls/) | Geeft de verzameling ActiveX-besturingselementen op een dia terug.<br/>            Alleen-lezen [`IControlCollection`](/slides/python-net/nl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/nl/aspose.slides/masterslide/name/) | Geeft de naam van een masterdia terug of stelt deze in.<br/>            Lezen/schrijven **str**. |
| [`slide_id`](/slides/python-net/nl/aspose.slides/masterslide/slide_id/) | Geeft de ID van een dia terug.<br/>            Alleen-lezen **int**. |
| [`custom_data`](/slides/python-net/nl/aspose.slides/masterslide/custom_data/) | Geeft de aangepaste gegevens van de dia terug.<br/>            Alleen-lezen [`ICustomData`](/slides/python-net/nl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/nl/aspose.slides/masterslide/timeline/) | Geeft het animatietijdlijnobject terug.<br/>            Alleen-lezen [`IAnimationTimeLine`](/slides/python-net/nl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/masterslide/slide_show_transition/) | Geeft het Transition-object terug dat informatie bevat over<br/>            hoe de opgegeven dia vooruitgaat tijdens een diavoorstelling.<br/>            Alleen-lezen [`ISlideShowTransition`](/slides/python-net/nl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/nl/aspose.slides/masterslide/background/) | Geeft de achtergrond van de dia terug.<br/>            Alleen-lezen [`IBackground`](/slides/python-net/nl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/masterslide/hyperlink_queries/) | Biedt gemakkelijke toegang tot ingesloten hyperlinks.<br/>            Alleen-lezen [`IHyperlinkQueries`](/slides/python-net/nl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/masterslide/show_master_shapes/) | Geeft aan of vormen op de masterdia al dan niet getoond moeten worden op dia's.<br/>            Voor de masterdia zelf retourneert deze eigenschap altijd `false`.<br/>            Lezen/schrijven **bool**. |
| [`presentation`](/slides/python-net/nl/aspose.slides/masterslide/presentation/) | Geeft de IPresentation-interface terug.<br/>            Alleen-lezen [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/masterslide/header_footer_manager/) | Geeft de HeaderFooter-beheerder van de masterdia terug.<br/>            Alleen-lezen [`IMasterSlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/nl/aspose.slides/masterslide/title_style/) | Geeft de stijl van een titeltekst terug.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/nl/aspose.slides/masterslide/body_style/) | Geeft de stijl van een hoofdtekst terug.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/nl/aspose.slides/masterslide/other_style/) | Geeft de stijl van een andere tekst terug.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/nl/aspose.slides/masterslide/layout_slides/) | Geeft de verzameling onderliggende lay-outdia's voor deze masterdia terug.<br/>            Alleen-lezen [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/nl/aspose.slides/masterslide/preserve/) | Bepaalt of de bijbehorende master wordt verwijderd wanneer alle dia's die op die master volgen, worden verwijderd.<br/>            Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen; om ongebruikte masters daadwerkelijk te verwijderen, roept u **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** aan.<br/>            Lezen/schrijven **bool**. |
| [`has_depending_slides`](/slides/python-net/nl/aspose.slides/masterslide/has_depending_slides/) | Geeft true terug als er minstens één dia bestaat die afhankelijk is van deze masterdia.<br/>            Alleen-lezen **bool**. |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/masterslide/theme_manager/) | Geeft de themabeheerder terug.<br/>            Alleen-lezen [`IMasterThemeManager`](/slides/python-net/nl/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/nl/aspose.slides/masterslide/drawing_guides/) | Geeft een verzameling tekengidsen voor de masterdia terug.<br/>            Alleen-lezen [`IDrawingGuidesCollection`](/slides/python-net/nl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/nl/aspose.slides/masterslide/slide/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/nl/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/masterslide/equals/#ibaseslide) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn.<br/>            De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia.<br/>            Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId en dynamische inhoud, bijv. de huidige datumwaarde in Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/masterslide/create_theme_effective/#) | Geeft een effectief thema voor deze dia terug. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Vindt de eerste vondst van een vorm met de opgegeven alternatieve tekst. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/nl/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Maakt een nieuwe masterdia gebaseerd op de huidige, waarbij een extern thema wordt toegepast op deze <br/>            en past de gemaakte masterdia toe op alle afhankelijke dia's. |
| [`get_depending_slides(self)`](/slides/python-net/nl/aspose.slides/masterslide/get_depending_slides/#) | Geeft een array terug met alle dia's die afhankelijk zijn van deze masterdia. |

### Zie ook
* klasse [`BaseSlide`](/slides/python-net/nl/aspose.slides/baseslide)
* klasse [`MasterSlide`](/slides/python-net/nl/aspose.slides/masterslide)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)