---
title: BaseSlide class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referenciája
description: 
type: docs
url: /hu/aspose.slides/baseslide/
---
## BaseSlide osztály

Közös adatokat képvisel az összes dia típushoz.

A BaseSlide típus a következő tagokat biztosítja:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/baseslide/shapes/) | Visszaadja a dia alakzatait.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/baseslide/controls/) | Visszaadja a dia ActiveX vezérlőinek gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/baseslide/name/) | Visszaadja vagy beállítja a dia nevét.<br/>            Olvasható/írható **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/baseslide/slide_id/) | Visszaadja a dia azonosítóját.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/baseslide/custom_data/) | Visszaadja a dia egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/baseslide/timeline/) | Visszaadja az animáció idővonal objektumot.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/baseslide/slide_show_transition/) | Visszaadja a Transition objektumot, amely információt tartalmaz arról,<br/>            hogyan halad a megadott dia a diavetítés során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/baseslide/background/) | Visszaadja a dia háttérét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/baseslide/hyperlink_queries/) | Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/baseslide/show_master_shapes/) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem.<br/>            A mesterdia esetén ez a tulajdonság mindig `false`-t ad vissza.<br/>            Olvasható/írható **bool**. |
| [`presentation`](/slides/python-net/hu/aspose.slides/baseslide/presentation/) | Visszaadja az IPresentation interfészt.<br/>            Csak olvasható [`IPresentation`](/slides/python-net/hu/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/hu/aspose.slides/baseslide/slide/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Összevonja a futamokat azonos formázással minden bekezdésben az összes elfogadható alakzatban. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/hu/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Összevonja a futamokat azonos formázással minden bekezdésben az összes elfogadható alakzatban. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/baseslide/equals/#ibaseslide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérési érték a dia szerkezete és statikus tartalma alapján kerül kiszámításra.<br/>            Két dia egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás, stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, pl. SlideId és a dinamikus tartalmat, pl. a Dátum helyőrzőben lévő aktuális dátum értékét. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/baseslide/create_theme_effective/#) | Visszaad egy hatékony témát ehhez a diához. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Megkeresi az első olyan alakzatot, amelyik a megadott alternatív szöveget tartalmazza. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)