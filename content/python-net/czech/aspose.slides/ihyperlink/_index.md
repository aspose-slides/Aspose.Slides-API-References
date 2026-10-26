---
title: IHyperlink class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ihyperlink/
---
## IHyperlink třída

Představuje hypertextový odkaz.

Typ IHyperlink vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/cs/aspose.slides/ihyperlink/action_type/) | Vrací typ akce HyperLinkEx.<br/>            Jen ke čtení [`HyperlinkActionType`](/slides/python-net/cs/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/cs/aspose.slides/ihyperlink/external_url/) | Určuje externí URL<br/>            Pokud se tato vlastnost nestane None, pak se vlastnost TargetSlide stane None.<br/>            Jen ke čtení **str**. |
| [`external_url_original`](/slides/python-net/cs/aspose.slides/ihyperlink/external_url_original/) | Představuje hypertextový odkaz nastavený pro tuto část bez ohledu na skutečný obsah části.<br/>            <br/>            PowerPoint se chová specificky pro odkazy a jejich odpovídající text v části. Umožňuje vytvořit text pro hypertextový odkaz ve formě platné URL, odlišné od skutečné adresy odkazu. V tomto případě, když zobrazíte odkaz v editačním okně, bude změněn tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu. |
| [`target_slide`](/slides/python-net/cs/aspose.slides/ihyperlink/target_slide/) | Pokud HyperlinkEx cílí na konkrétní snímek, vrátí tento snímek.<br/>            Pokud se tato vlastnost nestane None, pak se vlastnost ExternalUrl stane None.<br/>            Jen ke čtení [`ISlide`](/slides/python-net/cs/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/cs/aspose.slides/ihyperlink/target_frame/) | Vrací rámec v rámci nadřazené HTML sady rámců pro cíl<br/>            nadřazeného hypertextového odkazu, pokud existuje.<br/>            Čtení/zápis **str**. |
| [`tooltip`](/slides/python-net/cs/aspose.slides/ihyperlink/tooltip/) | Vrací řetězec, který může být zobrazen v uživatelském rozhraní<br/>            jako související s nadřazeným hypertextovým odkazem.<br/>            Čtení/zápis **str**. |
| [`history`](/slides/python-net/cs/aspose.slides/ihyperlink/history/) | Určuje, zda cíl nadřazeného hypertextového odkazu bude přidán<br/>            do seznamu zobrazených hypertextových odkazů při jeho vyvolání.<br/>            Čtení/zápis **bool**. |
| [`highlight_click`](/slides/python-net/cs/aspose.slides/ihyperlink/highlight_click/) | Určuje, zda má být hypertextový odkaz zvýrazněn po kliknutí.<br/>            Čtení/zápis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/cs/aspose.slides/ihyperlink/stop_sound_on_click/) | Určuje, zda má být zvuk při kliknutí na hypertextový odkaz zastaven.<br/>            Čtení/zápis **bool**. |
| [`sound`](/slides/python-net/cs/aspose.slides/ihyperlink/sound/) | Představuje přehrávaný zvuk hypertextového odkazu.<br/>            Čtení/zápis [`IAudio`](/slides/python-net/cs/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/cs/aspose.slides/ihyperlink/color_source/) | Představuje zdroj barvy hypertextového odkazu – buď styly nebo formát části.<br/>            Čtení/zápis [`HyperlinkColorSource`](/slides/python-net/cs/aspose.slides/hyperlinkcolorsource). |

## Metody

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/cs/aspose.slides/ihyperlink/equals/#ihyperlink) | Určuje, zda jsou dvě instance Hyperlink stejné. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)