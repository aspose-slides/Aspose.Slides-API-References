---
title: Hyperlink class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/hyperlink/
---
## Hyperlink třída

Reprezentuje hypertextový odkaz.

**Dědičnost:**[`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ Hyperlink uvádí následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/cs/aspose.slides/hyperlink/__init__/#str) | Vytvoří instanci hypertextového odkazu. |
| [`__init__(self, slide)`](/slides/python-net/cs/aspose.slides/hyperlink/__init__/#islide) | Vytvoří instanci hypertextového odkazu, který ukazuje na konkrétní snímek.<br/>            Poznámka: vytvořený hypertextový odkaz by měl být přiřazen k nějakému objektu ze stejné prezentace, jinak bude odkaz uložen jako NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/cs/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepsáním sekundárních vlastností. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`no_action`](/slides/python-net/cs/aspose.slides/hyperlink/no_action/) | Vrací speciální hypertextový odkaz "nic nedělej".<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/cs/aspose.slides/hyperlink/media/) | Vrací speciální hypertextový odkaz "přehrát mediální soubor". Používá se v AudioFrame a VideoFrame.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/cs/aspose.slides/hyperlink/next_slide/) | Vrací hypertextový odkaz na následující snímek.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/cs/aspose.slides/hyperlink/previous_slide/) | Vrací hypertextový odkaz na předchozí snímek.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/cs/aspose.slides/hyperlink/first_slide/) | Vrací hypertextový odkaz na první snímek prezentace.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/cs/aspose.slides/hyperlink/last_slide/) | Vrací hypertextový odkaz na poslední snímek prezentace.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/cs/aspose.slides/hyperlink/last_vieved_slide/) | Vrací hypertextový odkaz na naposledy zobrazený snímek.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/cs/aspose.slides/hyperlink/end_show/) | Vrací hypertextový odkaz, který ukončuje prezentaci.<br/>            Pouze pro čtení [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/cs/aspose.slides/hyperlink/action_type/) | Vrací typ akce hypertextového odkazu.<br/>            Pouze pro čtení [`HyperlinkActionType`](/slides/python-net/cs/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/cs/aspose.slides/hyperlink/external_url/) | Určuje externí URL.<br/>            Pouze pro čtení **str**. |
| [`target_slide`](/slides/python-net/cs/aspose.slides/hyperlink/target_slide/) | Pokud hypertextový odkaz cílí na konkrétní snímek, vrátí tento snímek.<br/>            Pouze pro čtení [`ISlide`](/slides/python-net/cs/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/cs/aspose.slides/hyperlink/external_url_original/) | Representuje hypertextový odkaz, který je nastaven pro tuto část bez ohledu na skutečný obsah části.<br/>            <br/>            PowerPoint se chová specificky pro odkazy a jejich odpovídající text v části. Umožňuje vytvořit text pro hypertextový odkaz ve formě platné URL, odlišné od skutečné adresy odkazu. V tomto případě, když si odkaz zobrazíte v editačním okně, bude změněn tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu. |
| [`target_frame`](/slides/python-net/cs/aspose.slides/hyperlink/target_frame/) | Vrací rámec v rámci nadřazeného HTML framesetu pro cíl<br/>            nadřazeného hypertextového odkazu, pokud existuje.<br/>            Čtení/Zápis **str**. |
| [`tooltip`](/slides/python-net/cs/aspose.slides/hyperlink/tooltip/) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní<br/>            jako související s nadřazeným hypertextovým odkazem.<br/>            Čtení/Zápis **str**. |
| [`history`](/slides/python-net/cs/aspose.slides/hyperlink/history/) | Určuje, zda bude cíl nadřazeného hypertextového odkazu přidán<br/>            do seznamu zobrazených hypertextových odkazů při jeho vyvolání.<br/>            Čtení/Zápis **bool**. |
| [`highlight_click`](/slides/python-net/cs/aspose.slides/hyperlink/highlight_click/) | Určuje, zda má být hypertextový odkaz po kliknutí zvýrazněn.<br/>            Čtení/Zápis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/cs/aspose.slides/hyperlink/stop_sound_on_click/) | Určuje, zda má být zvuk při kliknutí na hypertextový odkaz zastaven.<br/>            Čtení/Zápis **bool**. |
| [`sound`](/slides/python-net/cs/aspose.slides/hyperlink/sound/) | Representuje přehrávaný zvuk hypertextového odkazu.<br/>            Čtení/Zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/cs/aspose.slides/hyperlink/color_source/) | Representuje zdroj barvy hypertextového odkazu – buď styly nebo formát části.<br/>            Čtení/Zápis [`HyperlinkColorSource`](/slides/python-net/cs/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/cs/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/hyperlink/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/cs/aspose.slides/hyperlink/equals/#ihyperlink) | Určuje, zda jsou dvě instance Hyperlink rovny. |

### Viz také
* třída [`Hyperlink`](/slides/python-net/cs/aspose.slides/hyperlink)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)