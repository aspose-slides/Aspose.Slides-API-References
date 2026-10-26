---
title: IHyperlink class
second_title: Aspose.Slides a Python számára a .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/ihyperlink/
---
## IHyperlink osztály

Egy hiperhivatkozást képvisel.

Az IHyperlink típus a következő tagokkal rendelkezik:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`action_type`](/slides/python-net/hu/aspose.slides/ihyperlink/action_type/) | Visszaadja a HyperLinkEx műveletének típusát.<br/>            Csak olvasható [`HyperlinkActionType`](/slides/python-net/hu/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/hu/aspose.slides/ihyperlink/external_url/) | Megadja a külső URL-t<br/>            Ha ez a tulajdonság nem None értékre vált, akkor a TargetSlide tulajdonság None lesz.<br/>            Csak olvasható **str**. |
| [`external_url_original`](/slides/python-net/hu/aspose.slides/ihyperlink/external_url_original/) | Az adott részhez beállított hiperhivatkozást jelöli, függetlenül a rész tényleges tartalmától.<br/>            <br/>            A PowerPoint speciálisan viselkedik a hivatkozásokkal és a hozzájuk tartozó szöveggel egy részben. Lehetővé teszi, hogy a hiperhivatkozás szövegét egy érvényes URL formájában hozzuk létre, amely eltér a hivatkozás valódi címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinti a hivatkozást, az a szövegrésznek megfelelően lesz módosítva. Ez a tulajdonság a hiperhivatkozás eredeti értékét jelöli. |
| [`target_slide`](/slides/python-net/hu/aspose.slides/ihyperlink/target_slide/) | Ha a HyperlinkEx egy adott diára mutat, visszaadja ezt a diát.<br/>            Ha a tulajdonság nem None értékre vált, akkor az ExternalUrl tulajdonság None lesz.<br/>            Csak olvasható [`ISlide`](/slides/python-net/hu/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/hu/aspose.slides/ihyperlink/target_frame/) | Visszaadja a szülő HTML keretcsoportban a cél keretet, ha létezik a szülő hiperhivatkozás esetén.<br/>            Olvasás/írás **str**. |
| [`tooltip`](/slides/python-net/hu/aspose.slides/ihyperlink/tooltip/) | Visszaadja azt a karakterláncot, amely a felhasználói felületen megjelenhet a szülő hiperhivatkozással összefüggésben.<br/>            Olvasás/írás **str**. |
| [`history`](/slides/python-net/hu/aspose.slides/ihyperlink/history/) | Meghatározza, hogy a szülő hiperhivatkozás célja fel legyen-e véve a megtekintett hiperhivatkozások listájába, amikor meghívásra kerül.<br/>            Olvasás/írás **bool**. |
| [`highlight_click`](/slides/python-net/hu/aspose.slides/ihyperlink/highlight_click/) | Meghatározza, hogy a hiperhivatkozás kattintáskor legyen-e kiemelve.<br/>            Olvasás/írás **bool**. |
| [`stop_sound_on_click`](/slides/python-net/hu/aspose.slides/ihyperlink/stop_sound_on_click/) | Meghatározza, hogy a hang le legyen-e állítva a hiperhivatkozásra kattintáskor.<br/>            Olvasás/írás **bool**. |
| [`sound`](/slides/python-net/hu/aspose.slides/ihyperlink/sound/) | A hiperhivatkozás lejátszott hangját jelöli.<br/>            Olvasás/írás [`IAudio`](/slides/python-net/hu/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/hu/aspose.slides/ihyperlink/color_source/) | A hiperhivatkozás színének forrását jelöli – akár stílusok, akár részformátum.<br/>            Olvasás/írás [`HyperlinkColorSource`](/slides/python-net/hu/aspose.slides/hyperlinkcolorsource). |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/hu/aspose.slides/ihyperlink/equals/#ihyperlink) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)