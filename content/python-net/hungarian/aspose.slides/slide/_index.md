---
title: Slide class
second_title: Aspose.Slides a Pythonhoz .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/slide/
---
## Slide osztály

Egy slide-t képvisel egy bemutatóban.

**Öröklődés:**[`Slide`](/slides/python-net/hu/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

A Slide típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/slide/shapes/) | Visszaadja a slide alakzatokat.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/slide/controls/) | Visszaadja egy slide ActiveX vezérlők gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/slide/name/) | Visszaadja vagy beállítja egy slide nevét.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/slide/slide_id/) | Visszaadja egy slide ID-jét.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/slide/custom_data/) | Visszaadja a slide egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/slide/timeline/) | Visszaadja az animáció idővonal objektumot.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/slide/slide_show_transition/) | Visszaadja a Transition objektumot, amely információkat tartalmaz arról, hogyan halad a megadott slide a diavetítés során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/slide/background/) | Visszaadja a slide háttérét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/slide/hyperlink_queries/) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/slide/show_master_shapes/) | Megadja, hogy a master slide alakzatai megjelenjenek-e a diákon vagy sem.<br/>            Olvasás/írás **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/slide/presentation/) | Visszaadja az IPresentation interfészt.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/slide/header_footer_manager/) | Visszaadja a slide HeaderFooter kezelőjét.<br/>            Csak olvasható [`ISlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/slide/theme_manager/) | Visszaadja az felülíró témakezelőt.<br/>            Csak olvasható [`IOverrideThemeManager`](/slides/python-net/hu/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/hu/aspose.slides/slide/slide_number/) | Visszaadja a slide számát.<br/>            A slide indexe a [`Presentation.slides`](/slides/python-net/hu/aspose.slides/presentation/slides) gyűjteményben mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékével.<br/>            Olvasás/írás **int**. |
| [`hidden`](/slides/python-net/hu/aspose.slides/slide/hidden/) | Megállapítja, hogy a megadott slide rejtett-e a diavetítés során.<br/>            Olvasás/írás **bool**. |
| [`layout_slide`](/slides/python-net/hu/aspose.slides/slide/layout_slide/) | Visszaadja vagy beállítja az aktuális slide elrendezési slide-át.<br/>            Olvasás/írás [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/hu/aspose.slides/slide/notes_slide_manager/) | Lehetővé teszi a jegyzet slide elérését, hozzáadását és eltávolítását.<br/>            Csak olvasható [`INotesSlideManager`](/slides/python-net/hu/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/hu/aspose.slides/slide/slide/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/slide/join_portions_with_same_formatting/#) | Összefűzi a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Összefűzi a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/slide/get_image/#float-float) | Visszaad egy Miniatűr Kép objektumot egyedi méretezéssel. |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/slide/get_image/#) | Visszaad egy Miniatűr Kép objektumot (a valós méret 20%-a). |
| [`get_image(self, image_size)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposepydrawingsize) | Visszaad egy Miniatűr Kép objektumot a megadott mérettel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Visszaad egy Miniatűr tiff kép objektumot a megadott paraméterekkel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Visszaad egy Miniatűr Kép objektumot. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Visszaad egy Miniatűr Kép objektumot egyedi méretezéssel. |
| [`get_image(self, options, image_size)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Visszaad egy Miniatűr Kép objektumot a megadott mérettel. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/slide/write_as_svg/#iorawiobase) | Mentési a slide tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Mentési a slide tartalmát SVG fájlként. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/slide/equals/#ibaseslide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérő érték a slide szerkezete és statikus tartalma alapján számított.<br/>            Két slide egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmakat, például a Dátum helyőrzőben lévő aktuális dátumértéket. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/slide/create_theme_effective/#) | Visszaad egy hatékony témát ehhez a slide-hoz. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/slide/find_shape_by_alt_text/#str) | Megkeresi egy alakzat első előfordulását a megadott alternatív szöveggel. |
| [`write_as_emf(self, stream)`](/slides/python-net/hu/aspose.slides/slide/write_as_emf/#iorawiobase) | Mentés a slide tartalmát EMF fájlként. |
| [`remove(self)`](/slides/python-net/hu/aspose.slides/slide/remove/#) | Eltávolítja a slide-ot a prezentációból. |
| [`reset(self)`](/slides/python-net/hu/aspose.slides/slide/reset/#) | Visszaállítja minden olyan alakzat pozícióját, méretét és formázását, amelynek prototípusa van a LayoutSlide-on. |
| [`get_slide_comments(self, author)`](/slides/python-net/hu/aspose.slides/slide/get_slide_comments/#icommentauthor) | Visszaadja az adott szerző által hozzáadott összes slide megjegyzést. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)