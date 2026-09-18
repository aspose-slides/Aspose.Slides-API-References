---
title: IBaseSlide class
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ibaseslide/
---
## IBaseSlide osztály

Represents common data for all slide types.

The IBaseSlide type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`shapes`](/slides/python-net/hu/aspose.slides/ibaseslide/shapes/) | Visszaadja egy dia alakjait.<br/>            Csak olvasható [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/hu/aspose.slides/ibaseslide/controls/) | Visszaadja a dia ActiveX vezérlőinek gyűjteményét.<br/>            Csak olvasható [`IControlCollection`](/slides/python-net/hu/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/hu/aspose.slides/ibaseslide/name/) | Visszaadja vagy beállítja egy dia nevét.<br/>            Olvasás/írás **str**. |
| [`slide_id`](/slides/python-net/hu/aspose.slides/ibaseslide/slide_id/) | Visszaadja egy dia azonosítóját.<br/>            Csak olvasható **int**. |
| [`custom_data`](/slides/python-net/hu/aspose.slides/ibaseslide/custom_data/) | Visszaadja a dia egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/hu/aspose.slides/ibaseslide/timeline/) | Visszaadja az animáció idővonal objektumot.<br/>            Csak olvasható [`IAnimationTimeLine`](/slides/python-net/hu/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/hu/aspose.slides/ibaseslide/slide_show_transition/) | Visszaadja a TransitionEx objektumot, amely információt tartalmaz arról,<br/>            hogy a megadott dia hogyan halad tovább a diavetítés során.<br/>            Csak olvasható [`ISlideShowTransition`](/slides/python-net/hu/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/hu/aspose.slides/ibaseslide/background/) | Visszaadja a dia háttérképét.<br/>            Csak olvasható [`IBackground`](/slides/python-net/hu/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/ibaseslide/hyperlink_queries/) | Egyszerű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/hu/aspose.slides/ibaseslide/show_master_shapes/) | Megadja, hogy a mesterdia alakjai megjelenjenek-e a diákon vagy sem.<br/>            A mesterdiára vonatkozóan ez a tulajdonság mindig `false` értéket ad vissza.<br/>            Olvasás/írás **bool**. |
| [`slide`](/slides/python-net/hu/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/ibaseslide/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/hu/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Megkeresi a megadott alternatív szöveggel rendelkező alak első előfordulását. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Egyesíti az azonos formázású futamokat az összes bekezdésben minden megfelelő alakon. |
| [`equals(self, slide)`](/slides/python-net/hu/aspose.slides/ibaseslide/equals/#ibaseslide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e.<br/>            A visszatérő érték a dia struktúrája és statikus tartalma alapján kerül kiszámításra.<br/>            Két dia akkor egyenlő, ha az összes alak, stílus, szöveg, animáció és egyéb beállítások stb. egyenlőek. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátumhelyőrzőben lévő aktuális dátumértéket. |
| [`create_theme_effective(self)`](/slides/python-net/hu/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)