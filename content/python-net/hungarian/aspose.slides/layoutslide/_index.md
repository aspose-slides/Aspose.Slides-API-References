---
title: LayoutSlide class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/layoutslide/
---
## LayoutSlide osztály

A LayoutSlide típus a következő tagokat teszi közzé:

**Öröklés:**[`LayoutSlide`](/slides/python-net/hu/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/layoutslide/shapes/) | Visszaadja a dia alakzatait.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/layoutslide/controls/) | Visszaadja a dián lévő ActiveX vezérlők gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/layoutslide/name/) | Visszaadja vagy beállítja a dia nevét.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/layoutslide/slide_id/) | Visszaadja a dia azonosítóját.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/layoutslide/custom_data/) | Visszaadja a dia egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/layoutslide/timeline/) | Visszaadja az animáció idővonal objektumot.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/layoutslide/slide_show_transition/) | Visszaadja a Transition objektumot, amely információkat tartalmaz arról, hogyan halad előre a megadott dia a bemutató során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/layoutslide/background/) | Visszaadja a dia háttérét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/layoutslide/hyperlink_queries/) | Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/layoutslide/show_master_shapes/) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem.<br/>            Olvasás/írás **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/layoutslide/presentation/) | Visszaadja az IPresentation interfészt.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/layoutslide/header_footer_manager/) | Visszaadja a layout dia HeaderFooter kezelőjét.<br/>            Csak olvasható [`ILayoutSlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/hu/aspose.slides/layoutslide/placeholder_manager/) | Visszaadja a layout dia helyőrző kezelőjét.<br/>            Csak olvasható [`ILayoutPlaceholderManager`](/slides/python-net/hu/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/hu/aspose.slides/layoutslide/master_slide/) | Visszaadja vagy beállítja a layout mesterdiáját.<br/>            Olvasás/írás [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/layoutslide/theme_manager/) | Visszaadja a felülbíráló téma kezelőt.<br/>            Csak olvasható [`IOverrideThemeManager`](/slides/python-net/hu/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/hu/aspose.slides/layoutslide/layout_type/) | Visszaadja ennek a layout diának a layout típusát.<br/>            Csak olvasható [`SlideLayoutType`](/slides/python-net/hu/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/hu/aspose.slides/layoutslide/has_depending_slides/) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely ettől a layout diáktól függ.<br/>            Csak olvasható **bool**. |
| [`drawing_guides`](/slides/python-net/hu/aspose.slides/layoutslide/drawing_guides/) | Visszaadja a layout dia rajzolási útmutatóinak gyűjteményét.<br/>            Csak olvasható [`IDrawingGuidesCollection`](/slides/python-net/hu/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/hu/aspose.slides/layoutslide/slide/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Összevonja az azonos formázású futamokat minden bekezdésben az összes elfogadható alakzaton. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Összevonja az azonos formázású futamokat minden bekezdésben az összes elfogadható alakzaton. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/layoutslide/equals/#ibaseslide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérő értéket a dia szerkezete és statikus tartalma alapján számítják ki.<br/>            Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. A összehasonlítás nem veszi figyelembe az egyedi azonosítóértékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátum helyőrzőben lévő aktuális dátumértéket. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/layoutslide/create_theme_effective/#) | Visszaad egy hatékony témát ehhez a diához. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Megkeresi az első olyan alakzatot, amely rendelkezik a megadott alternatív szöveggel. |
| [`remove(self)`](/slides/python-net/hu/aspose.slides/layoutslide/remove/#) | Eltávolítja a layoutot a prezentációból. |
| [`get_depending_slides(self)`](/slides/python-net/hu/aspose.slides/layoutslide/get_depending_slides/#) | Visszaad egy tömböt az összes diával, amelyek ettől a layout diáktól függenek. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`LayoutSlide`](/slides/python-net/hu/aspose.slides/layoutslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)