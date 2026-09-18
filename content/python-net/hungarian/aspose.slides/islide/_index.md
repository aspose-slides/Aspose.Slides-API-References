---
title: ISlide class
second_title: Aspose.Slides Pythonhoz .NET-on keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/islide/
---
## ISlide osztály

Egy diát képvisel egy bemutatóban.

Az ISlide típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/islide/header_footer_manager/) | Visszaadja a diák HeaderFooter kezelőjét.<br/>            Csak olvasható [`ISlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/islideheaderfootermanager). |
| [`slide_number`](/slides/python-net/hu/aspose.slides/islide/slide_number/) | Visszaadja a dia számát.<br/>            A [`IPresentation.slides`](/slides/python-net/hu/aspose.slides/ipresentation/slides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - 1-vel.<br/>            Olvasás/írás **int**. |
| [`hidden`](/slides/python-net/hu/aspose.slides/islide/hidden/) | Meghatározza, hogy a megadott dia rejtett-e a diavetítés során.<br/>            Olvasás/írás **bool**. |
| [`layout_slide`](/slides/python-net/hu/aspose.slides/islide/layout_slide/) | Visszaadja vagy beállítja az aktuális dia elrendezését.<br/>            Olvasás/írás [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/hu/aspose.slides/islide/notes_slide_manager/) | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását.<br/>            Csak olvasható [`INotesSlideManager`](/slides/python-net/hu/aspose.slides/inotesslidemanager). |
| [`shapes`](/slides/python-net/hu/aspose.slides/islide/shapes/) |  |
| [`controls`](/slides/python-net/hu/aspose.slides/islide/controls/) |  |
| [`name`](/slides/python-net/hu/aspose.slides/islide/name/) |  |
| [`slide_id`](/slides/python-net/hu/aspose.slides/islide/slide_id/) |  |
| [`custom_data`](/slides/python-net/hu/aspose.slides/islide/custom_data/) |  |
| [`timeline`](/slides/python-net/hu/aspose.slides/islide/timeline/) |  |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/islide/slide_show_transition/) |  |
| [`background`](/slides/python-net/hu/aspose.slides/islide/background/) |  |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/islide/hyperlink_queries/) |  |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/islide/show_master_shapes/) |  |
| [`slide`](/slides/python-net/hu/aspose.slides/islide/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/islide/presentation/) |  |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/islide/theme_manager/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/islide/get_image/#float-float) | Visszaad egy képtárgyat egyedi méretezéssel. |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/islide/get_image/#) | Visszaad egy bélyegkép objektumot (a valós méret 20%-a). |
| [`get_image(self, image_size)`](/slides/python-net/hu/aspose.slides/islide/get_image/#asposepydrawingsize) | Visszaad egy képtárgyat a megadott mérettel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/islide/get_image/#asposeslidesexportitiffoptions) | Visszaad egy bélyegkép tiff bitmap objektumot a megadott paraméterekkel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions) | Visszaad egy bélyegkép bitmap objektumot. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-float-float) | Visszaad egy bélyegkép bitmap objektumot egyedi méretezéssel. |
| [`get_image(self, options, image_size)`](/slides/python-net/hu/aspose.slides/islide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Visszaad egy bélyegkép bitmap objektumot a megadott mérettel. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/islide/write_as_svg/#iorawiobase) | A dia tartalmát SVG fájlként menti. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/islide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | A dia tartalmát SVG fájlként menti. |
| [`get_slide_comments(self, author)`](/slides/python-net/hu/aspose.slides/islide/get_slide_comments/#icommentauthor) | Visszaadja az adott szerző által hozzáadott összes diamegjegyzést. |
| [`write_as_emf(self, stream)`](/slides/python-net/hu/aspose.slides/islide/write_as_emf/#iorawiobase) | A dia tartalmát EMF fájlként menti. |
| [`remove(self)`](/slides/python-net/hu/aspose.slides/islide/remove/#) | Eltávolítja a diát a bemutatóból. |
| [`reset(self)`](/slides/python-net/hu/aspose.slides/islide/reset/#) | Visszaállítja a pozíciót, méretet és formázást minden olyan alakzatnál, amelynek prototípusa a LayoutSlide-on van. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/islide/find_shape_by_alt_text/#str) |  |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/islide/join_portions_with_same_formatting/#) |  |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/islide/equals/#ibaseslide) |  |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/islide/create_theme_effective/#) |  |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)