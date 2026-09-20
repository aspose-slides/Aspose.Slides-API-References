---
title: ILayoutSlide class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ilayoutslide/
---
## ILayoutSlide classe

Rappresenta una diapositiva di layout.

Il tipo ILayoutSlide espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/it/aspose.slides/ilayoutslide/header_footer_manager/) | Restituisce il gestore HeaderFooter della diapositiva di layout.<br/>            Read-only [`ILayoutSlideHeaderFooterManager`](/slides/python-net/it/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/it/aspose.slides/ilayoutslide/placeholder_manager/) | Restituisce il gestore dei placeholder della diapositiva di layout.<br/>            Read-only [`ILayoutPlaceholderManager`](/slides/python-net/it/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/it/aspose.slides/ilayoutslide/master_slide/) | Restituisce o imposta la diapositiva master per un layout.<br/>            Read/write [`IMasterSlide`](/slides/python-net/it/aspose.slides/imasterslide). |
| [`layout_type`](/slides/python-net/it/aspose.slides/ilayoutslide/layout_type/) | Restituisce il tipo di layout di questa diapositiva di layout.<br/>            Read-only [`SlideLayoutType`](/slides/python-net/it/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/it/aspose.slides/ilayoutslide/has_depending_slides/) | Restituisce vero se esiste almeno una diapositiva che dipende da questa diapositiva di layout.<br/>            Read-only **bool**. |
| [`drawing_guides`](/slides/python-net/it/aspose.slides/ilayoutslide/drawing_guides/) | Restituisce una collezione di guide di disegno per la diapositiva di layout.<br/>            Read-only [`IDrawingGuidesCollection`](/slides/python-net/it/aspose.slides/idrawingguidescollection) |
| [`shapes`](/slides/python-net/it/aspose.slides/ilayoutslide/shapes/) |  |
| [`controls`](/slides/python-net/it/aspose.slides/ilayoutslide/controls/) |  |
| [`name`](/slides/python-net/it/aspose.slides/ilayoutslide/name/) |  |
| [`slide_id`](/slides/python-net/it/aspose.slides/ilayoutslide/slide_id/) |  |
| [`custom_data`](/slides/python-net/it/aspose.slides/ilayoutslide/custom_data/) |  |
| [`timeline`](/slides/python-net/it/aspose.slides/ilayoutslide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/it/aspose.slides/ilayoutslide/slide_show_transition/) |  |
| [`background`](/slides/python-net/it/aspose.slides/ilayoutslide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/it/aspose.slides/ilayoutslide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/it/aspose.slides/ilayoutslide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/it/aspose.slides/ilayoutslide/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/ilayoutslide/presentation/) |  |
| [`theme_manager`](/slides/python-net/it/aspose.slides/ilayoutslide/theme_manager/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_depending_slides(self)`](/slides/python-net/it/aspose.slides/ilayoutslide/get_depending_slides/#) | Restituisce un array con tutte le diapositive che dipendono da questa diapositiva di layout. |
| [`remove(self)`](/slides/python-net/it/aspose.slides/ilayoutslide/remove/#) | Rimuove il layout dalla presentazione. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/it/aspose.slides/ilayoutslide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/it/aspose.slides/ilayoutslide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/it/aspose.slides/ilayoutslide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/it/aspose.slides/ilayoutslide/create_theme_effective/#) |  |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)