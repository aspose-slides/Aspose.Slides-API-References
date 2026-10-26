---
title: Hyperlink class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/hyperlink/
---
## Hyperlink osztály

Egy hiperhivatkozást képvisel.

**Inheritance:**[`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)

A Hyperlink típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/hu/aspose.slides/hyperlink/__init__/#str) | Létrehoz egy hiperhivatkozás példányt. |
| [`__init__(self, slide)`](/slides/python-net/hu/aspose.slides/hyperlink/__init__/#islide) | Létrehoz egy hiperhivatkozás példányt, amely egy adott diára mutat.<br/>            Megjegyzés: a létrehozott hiperhivatkozást a bemutató ugyanabból a prezentációból származó objektumhoz kell rendelni, különben a hivatkozás NoActionként lesz mentve. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/hu/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Létrehoz egy hiperhivatkozás példányt egy másik hiperhivatkozás forrásaként, felülírva a másodlagos tulajdonságokat. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`no_action`](/slides/python-net/hu/aspose.slides/hyperlink/no_action/) | Visszaad egy speciális „ne tegyen semmit” hiperhivatkozást.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/hu/aspose.slides/hyperlink/media/) | Visszaad egy speciális „mediafájlt lejátszó” hiperhivatkozást. Az AudioFrame és a VideoFrame használja.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/hu/aspose.slides/hyperlink/next_slide/) | Visszaad egy hiperhivatkozást a következő diára.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/hu/aspose.slides/hyperlink/previous_slide/) | Visszaad egy hiperhivatkozást az előző diára.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/hu/aspose.slides/hyperlink/first_slide/) | Visszaad egy hiperhivatkozást a bemutató első diájára.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/hu/aspose.slides/hyperlink/last_slide/) | Visszaad egy hiperhivatkozást a bemutató utolsó diájára.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/hu/aspose.slides/hyperlink/last_vieved_slide/) | Visszaad egy hiperhivatkozást az utoljára megtekintett diára.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/hu/aspose.slides/hyperlink/end_show/) | Visszaad egy hiperhivatkozást, amely befejezi a bemutatót.<br/>            Csak olvasható [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/hu/aspose.slides/hyperlink/action_type/) | Visszaad a Hyperlink műveletének típusát.<br/>            Csak olvasható [`HyperlinkActionType`](/slides/python-net/hu/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/hu/aspose.slides/hyperlink/external_url/) | Meghatározza a külső URL-t.<br/>            Csak olvasható **str**. |
| [`target_slide`](/slides/python-net/hu/aspose.slides/hyperlink/target_slide/) | Ha a Hyperlink egy adott diára mutat, visszaadja ezt a diát.<br/>            Csak olvasható [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/hu/aspose.slides/hyperlink/external_url_original/) | Képvisel egy hiperhivatkozást, amelyet ennek a résznek állítanak be a tényleges tartalomtól függetlenül.<br/>            <br/>            A PowerPoint különböző módon kezeli a hivatkozásokat és a hozzájuk tartozó szöveget egy részben. Lehetővé teszi, hogy a hiperhivatkozás szövegét egy érvényes URL formájában hozzák létre, amely eltér a hivatkozás valós címétől. Ebben az esetben, amikor megtekinti a hivatkozást a szerkesztőablakban, az a szövegrésszel megegyezővé lesz módosítva. Ez a tulajdonság a hiperhivatkozás eredeti értékét jelenti. |
| [`target_frame`](/slides/python-net/hu/aspose.slides/hyperlink/target_frame/) | Visszaad azt a keretet a szülő HTML keretcsoporton belül, amely a szülő hiperhivatkozás célja, ha létezik.<br/>            Olvasható/írható **str**. |
| [`tooltip`](/slides/python-net/hu/aspose.slides/hyperlink/tooltip/) | Visszaad egy karakterláncot, amely megjelenhet a felhasználói felületen a szülő hiperhivatkozással összefüggésben.<br/>            Olvasható/írható **str**. |
| [`history`](/slides/python-net/hu/aspose.slides/hyperlink/history/) | Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívják.<br/>            Olvasható/írható **bool**. |
| [`highlight_click`](/slides/python-net/hu/aspose.slides/hyperlink/highlight_click/) | Meghatározza, hogy a hiperhivatkozás kattintáskor legyen-e kiemelve.<br/>            Olvasható/írható **bool**. |
| [`stop_sound_on_click`](/slides/python-net/hu/aspose.slides/hyperlink/stop_sound_on_click/) | Meghatározza, hogy a hang le legyen-e állítva a hiperhivatkozásra kattintáskor.<br/>            Olvasható/írható **bool**. |
| [`sound`](/slides/python-net/hu/aspose.slides/hyperlink/sound/) | A hiperhivatkozás lejátszott hangját jelenti.<br/>            Olvasható/írható [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/hu/aspose.slides/hyperlink/color_source/) | A hiperhivatkozás színének forrását jelenti – akár stílusok, akár részformátum.<br/>            Olvasható/írható [`HyperlinkColorSource`](/slides/python-net/hu/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/hu/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/hyperlink/presentation/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/hu/aspose.slides/hyperlink/equals/#ihyperlink) | Meghatározza, hogy a két Hyperlink példány egyenlő-e. |

### Lásd még
* osztály [`Hyperlink`](/slides/python-net/hu/aspose.slides/hyperlink)
* osztály [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)