---
title: Slide class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slide/
---
## Slide osztály

Egy diát képvisel egy prezentációban.

**Öröklés:**[`Slide`](/slides/python-net/hu/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

A Slide típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/slide/shapes/) | Visszaadja a dia alakjait.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/slide/controls/) | Visszaadja egy dia ActiveX vezérlőinek gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/slide/name/) | Visszaadja vagy beállítja a dia nevét.<br/>            Olvasható/írható **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/slide/slide_id/) | Visszaadja egy dia azonosítóját.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/slide/custom_data/) | Visszaadja a dia egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/slide/timeline/) | Visszaadja az animáció idővonal objektumát.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/slide/slide_show_transition/) | Visszaadja a Transition objektumot, amely információkat tartalmaz arról,<br/>            hogyan halad az adott dia a diavetítés során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/slide/background/) | Visszaadja a dia háttérképét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/slide/hyperlink_queries/) | Könnyű hozzáférést biztosít a benne lévő hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/slide/show_master_shapes/) | Meghatározza, hogy a mesterdia alakjai megjelenjenek-e a diákon vagy sem.<br/>            Olvasható/írható **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/slide/presentation/) | Visszaadja az IPresentation interfészt.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/slide/header_footer_manager/) | Visszaadja a dia HeaderFooter kezelőjét.<br/>            Csak olvasható [`ISlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/slide/theme_manager/) | Visszaadja a felülíró téma kezelőt.<br/>            Csak olvasható [`IOverrideThemeManager`](/slides/python-net/hu/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/hu/aspose.slides/slide/slide_number/) | Visszaadja a dia számát.<br/>            A dia indexe a [`Presentation.slides`](/slides/python-net/hu/aspose.slides/presentation/slides) gyűjteményben mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékével.<br/>            Olvasható/írható **int**. |
| [`hidden`](/slides/python-net/hu/aspose.slides/slide/hidden/) | Meghatározza, hogy a megadott dia rejtett-e a diavetítés során.<br/>            Olvasható/írható **bool**. |
| [`layout_slide`](/slides/python-net/hu/aspose.slides/slide/layout_slide/) | Visszaadja vagy beállítja az aktuális dia elrendezését.<br/>            Olvasható/írható [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/hu/aspose.slides/slide/notes_slide_manager/) | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását.<br/>            Csak olvasható [`INotesSlideManager`](/slides/python-net/hu/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/hu/aspose.slides/slide/slide/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/slide/join_portions_with_same_formatting/#) | Összevonja az azonos formázású futamokat az összes bekezdésben az összes elfogadható alakban. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Összevonja az azonos formázású futamokat az összes bekezdésben az összes elfogadható alakban. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/slide/get_image/#float-float) | Visszaad egy bélyegkép objektumot egyedi méretezéssel. |
| [`get_image(self)`](/slides/python-net/hu/aspose.slides/slide/get_image/#) | Visszaad egy bélyegkép objektumot (a valós méret 20%-a). |
| [`get_image(self, image_size)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidessize) | Visszaad egy bélyegkép objektumot a megadott mérettel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Visszaad egy bélyegkép tiff kép objektumot a megadott paraméterekkel. |
| [`get_image(self, options)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Visszaad egy bélyegkép objektumot. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Visszaad egy bélyegkép objektumot egyedi méretezéssel. |
| [`get_image(self, options, image_size)`](/slides/python-net/hu/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposeslidessize) | Visszaad egy bélyegkép objektumot a megadott mérettel. |
| [`write_as_svg(self, stream)`](/slides/python-net/hu/aspose.slides/slide/write_as_svg/#iorawiobase) | Elmenti a dia tartalmát SVG fájlként. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/hu/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Elmenti a dia tartalmát SVG fájlként. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/slide/equals/#ibaseslide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérési értéket a dia szerkezete és statikus tartalma alapján számítják ki.<br/>            Két dia akkor egyenlő, ha minden alak, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. A összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmakat, például a Dátumhelyőrzőben szereplő aktuális dátumot. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/slide/create_theme_effective/#) | Visszaad egy hatékony témát ehhez a diához. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/slide/find_shape_by_alt_text/#str) | Megkeresi a megadott alternatív szövegű alak első előfordulását. |
| [`write_as_emf(self, stream)`](/slides/python-net/hu/aspose.slides/slide/write_as_emf/#iorawiobase) | Elmenti a dia tartalmát EMF fájlként. |
| [`remove(self)`](/slides/python-net/hu/aspose.slides/slide/remove/#) | Eltávolítja a diát a prezentációból. |
| [`reset(self)`](/slides/python-net/hu/aspose.slides/slide/reset/#) | Visszaállítja a pozíciót, méretet és formázást minden olyan alak esetén, amelynek prototípusa van a LayoutSlide-on. |
| [`get_slide_comments(self, author)`](/slides/python-net/hu/aspose.slides/slide/get_slide_comments/#icommentauthor) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)