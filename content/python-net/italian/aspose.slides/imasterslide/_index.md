---
title: IMasterSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/imasterslide/
---
## IMasterSlide classe

Rappresenta una master slide in una presentazione.

Il tipo IMasterSlide espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/imasterslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della master slide.<br/>            Sola lettura [`IMasterSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/it/aspose.slides/imasterslide/title_style/) | Restituisce lo stile di un testo titolo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/it/aspose.slides/imasterslide/body_style/) | Restituisce lo stile di un testo corpo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/it/aspose.slides/imasterslide/other_style/) | Restituisce lo stile di un altro testo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/it/aspose.slides/imasterslide/layout_slides/) | Restituisce la raccolta di layout slide figlie per questa master slide.<br/>            Sola lettura [`IMasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/it/aspose.slides/imasterslide/preserve/) | Determina se il master corrispondente viene eliminato quando tutte <br/>            le slide che seguono quel master vengono eliminate.<br/>            Nota: Aspose.Slides non rimuoverà mai alcun master inutilizzato da solo, <br/>            per rimuovere effettivamente i master inutilizzati chiamare **Aspose.Slides.IMasterSlideCollection.RemoveUnused(Syste**<br/>            Lettura/scrittura **bool**. |
| [`has_depending_slides`](/slides/python-net/it/aspose.slides/imasterslide/has_depending_slides/) | Restituisce vero se esiste almeno una slide che dipende da questa master slide.<br/>            Sola lettura **bool**. |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/imasterslide/drawing_guides/) | Restituisce una raccolta di guide di disegno per la master slide.<br/>            Sola lettura [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/it/aspose.slides/imasterslide/shapes/) |  |
| [`controls`](/slides/python-net/it/aspose.slides/imasterslide/controls/) |  |
| [`name`](/slides/python-net/it/aspose.slides/imasterslide/name/) |  |
| [`slide_id`](/slides/python-net/it/aspose.slides/imasterslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/imasterslide/custom_data/) |  |
| [`timeline`](/slides/python-net/it/aspose.slides/imasterslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/imasterslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/it/aspose.slides/imasterslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/imasterslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/imasterslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/imasterslide/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/imasterslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/it/aspose.slides/imasterslide/theme_manager/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/it/aspose.slides/imasterslide/apply_external_theme_to_depending_slides/#str) | Crea una nuova master slide basata su quella corrente, applicando un tema esterno <br/>            e applica la master slide creata a tutte le slide dipendenti. |
| [`get_depending_slides(self)`](/slides/python-net/it/aspose.slides/imasterslide/get_depending_slides/#) | Restituisce un array con tutte le slide che dipendono da questa master slide. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/imasterslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/imasterslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/imasterslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/imasterslide/create_theme_effective/#) |  |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)