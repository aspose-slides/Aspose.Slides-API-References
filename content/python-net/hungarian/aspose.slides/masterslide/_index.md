---
title: MasterSlide class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozáson keresztül
description: 
type: docs
url: /hu/aspose.slides/masterslide/
---
## MasterSlide osztály

Egy prezentációban a master dia képviseli.

**Inheritance:**[`MasterSlide`](/slides/python-net/hu/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)

A MasterSlide típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/masterslide/shapes/) | Visszaadja egy dia alakzatait.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/masterslide/controls/) | Visszaadja egy dia ActiveX vezérlőinek gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/masterslide/name/) | Visszaadja vagy beállítja egy master dia nevét.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/masterslide/slide_id/) | Visszaadja egy dia azonosítóját.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/masterslide/custom_data/) | Visszaadja a dia egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/masterslide/timeline/) | Visszaadja az animáció idővonal objektumát.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/masterslide/slide_show_transition/) | Visszaadja a Transition objektumot, amely információkat tartalmaz arról,<br/>            hogyan halad tovább a megadott dia a diavetítés során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/masterslide/background/) | Visszaadja a dia hátterét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/masterslide/hyperlink_queries/) | Könnyű hozzáférést biztosít a benne lévő hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/masterslide/show_master_shapes/) | Megadja, hogy a master dián található alakzatok megjelenjenek-e a diákon vagy sem.<br/>            Maga a master dia esetén ez a tulajdonság mindig `false` értéket ad vissza.<br/>            Olvasás/írás **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/masterslide/presentation/) | Visszaadja az IPresentation interfészt.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/masterslide/header_footer_manager/) | Visszaadja a master dia HeaderFooter kezelőjét.<br/>            Csak olvasható [`IMasterSlideHeaderFooterManager`](/slides/python-net/hu/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/hu/aspose.slides/masterslide/title_style/) | Visszaadja egy címszöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/hu/aspose.slides/masterslide/body_style/) | Visszaadja egy törzsszöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/hu/aspose.slides/masterslide/other_style/) | Visszaadja egy egyéb szöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/masterslide/layout_slides/) | Visszaadja ennek a master diáknak a gyermek elrendezési diák gyűjteményét.<br/>            Csak olvasható [`IMasterLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/hu/aspose.slides/masterslide/preserve/) | Meghatározza, hogy a megfelelő master törlésre kerül-e, amikor az azt követő összes dia törlésre kerül.<br/>            Megjegyzés: Az Aspose.Slides soha nem távolít el önmagától semmilyen használaton kívüli master diát; a használaton kívüli master diák tényleges eltávolításához hívja meg a **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste** függvényt.<br/>            Olvasás/írás **bool**. |
| [`has_depending_slides`](/slides/python-net/hu/aspose.slides/masterslide/has_depending_slides/) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely ettől a master diáktól függ.<br/>            Csak olvasható **bool**. |
| [`theme_manager`](/slides/python-net/hu/aspose.slides/masterslide/theme_manager/) | Visszaadja a téma kezelőt.<br/>            Csak olvasható [`IMasterThemeManager`](/slides/python-net/hu/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/hu/aspose.slides/masterslide/drawing_guides/) | Visszaadja a master dia rajzolási segédvonalainak gyűjteményét.<br/>            Csak olvasható [`IDrawingGuidesCollection`](/slides/python-net/hu/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/hu/aspose.slides/masterslide/slide/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Összevonja a futásokat azonos formázással minden bekezdésben és minden elfogadható alakzatban. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Összevonja a futásokat azonos formázással minden bekezdésben és minden elfogadható alakzatban. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/masterslide/equals/#ibaseslide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérő értéket a dia szerkezete és statikus tartalma alapján számítják ki.<br/>            Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátumhelyőrzőben jelen lévő aktuális dátumértéket. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/masterslide/create_theme_effective/#) | Visszaad egy hatékony témát ennek a diáknak. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Megkeresi az első előfordulását annak a alakzatnak, amely a megadott alternatív szöveggel rendelkezik. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/hu/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Új master diát hoz létre az aktuális alapján, egy külső témát alkalmaz rá <br/>            és a létrehozott master diát minden függő diához alkalmazza. |
| [`get_depending_slides(self)`](/slides/python-net/hu/aspose.slides/masterslide/get_depending_slides/#) | Visszaad egy tömböt az összes diával, amelyek ettől a master diáktól függenek. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`MasterSlide`](/slides/python-net/hu/aspose.slides/masterslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)