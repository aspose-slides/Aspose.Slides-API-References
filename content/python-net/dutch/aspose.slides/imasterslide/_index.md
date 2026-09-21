---
title: IMasterSlide class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/imasterslide/
---
## IMasterSlide klasse

Stelt een master slide voor in een presentatie.

Het IMasterSlide-type biedt de volgende leden weer:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/nl/aspose.slides/imasterslide/header_footer_manager/) | Retourneert HeaderFooter manager van de master slide.<br/>            Alleen-lezen [`IMasterSlideHeaderFooterManager`](/slides/python-net/nl/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/nl/aspose.slides/imasterslide/title_style/) | Retourneert de stijl van een titeltekst.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/nl/aspose.slides/imasterslide/body_style/) | Retourneert de stijl van een hoofdtekst.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/nl/aspose.slides/imasterslide/other_style/) | Retourneert de stijl van een andere tekst.<br/>            Alleen-lezen [`ITextStyle`](/slides/python-net/nl/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/nl/aspose.slides/imasterslide/layout_slides/) | Retourneert de collectie van onderliggende lay-outdia's voor deze master slide.<br/>            Alleen-lezen [`IMasterLayoutSlideCollection`](/slides/python-net/nl/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/nl/aspose.slides/imasterslide/preserve/) | Bepaalt of de overeenkomstige master wordt verwijderd wanneer alle <br/>            de dia's die op die master volgen, worden verwijderd.<br/>            Opmerking: Aspose.Slides zal nooit zelf een ongebruikte master verwijderen, <br/>            om ongebruikte masters daadwerkelijk te verwijderen, roep **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste** aan.<br/>            Lezen/Schrijven **bool**. |
| [`has_depending_slides`](/slides/python-net/nl/aspose.slides/imasterslide/has_depending_slides/) | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze master slide.<br/>            Alleen-lezen **bool**. |
| [`drawing_guides`](/slides/python-net/nl/aspose.slides/imasterslide/drawing_guides/) | Retourneert een collectie van tekengidsen voor de master slide.<br/>            Alleen-lezen [`IDrawingGuidesCollection`](/slides/python-net/nl/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/nl/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/nl/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/nl/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/nl/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/nl/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/nl/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/nl/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/nl/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/nl/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/nl/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/nl/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/nl/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/nl/aspose.slides/imasterslide/theme_manager/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/nl/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Maakt een nieuwe master slide op basis van de huidige, door een extern thema toe te passen op deze <br/>            en past de gemaakte master slide toe op alle afhankelijke dia's. |
| [`get_depending_slides(self)`](/slides/python-net/nl/aspose.slides/imasterslide/get_depending_slides/#) | Retourneert een array met alle dia's die afhankelijk zijn van deze master slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/nl/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/nl/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/nl/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/nl/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)