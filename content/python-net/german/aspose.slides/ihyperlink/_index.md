---
title: IHyperlink class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ihyperlink/
---
## IHyperlink Klasse

Stellt einen Hyperlink dar.

Der IHyperlink-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`action_type`](/slides/python-net/de/aspose.slides/ihyperlink/action_type/) | Gibt den Typ der Aktion von HyperLinkEx zurück.<br/>            Nur lesbar [`HyperlinkActionType`](/slides/python-net/de/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/de/aspose.slides/ihyperlink/external_url/) | Gibt die externe URL an<br/>            Wenn diese Eigenschaft nicht None wird, dann wird die Eigenschaft TargetSlide None.<br/>            Nur lesbar **str**. |
| [`external_url_original`](/slides/python-net/de/aspose.slides/ihyperlink/external_url_original/) | Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ohne Rücksicht auf den tatsächlichen Inhalt des Abschnitts.<br/>            <br/>            PowerPoint verhält sich speziell für Links und deren zugehörigen Text in einem Abschnitt. Es ermöglicht, Text für den Hyperlink in<br/>            Form einer gültigen URL zu erstellen, die von der tatsächlichen Adresse des Links abweicht. In diesem Fall wird beim Betrachten des Links im Bearbeitungsfenster der Text<br/>            angepasst, um dem Textabschnitt zu entsprechen. Diese Eigenschaft stellt den ursprünglichen Wert des Hyperlinks dar. |
| [`target_slide`](/slides/python-net/de/aspose.slides/ihyperlink/target_slide/) | Wenn HyperlinkEx eine bestimmte Folie anvisiert, gibt diese Folie zurück.<br/>            Wenn die Eigenschaft nicht None wird, dann wird die Eigenschaft ExternalUrl None.<br/>            Nur lesbar [`ISlide`](/slides/python-net/de/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/de/aspose.slides/ihyperlink/target_frame/) | Gibt das Frame im übergeordneten HTML-Frameset für das Ziel<br/>            des übergeordneten Hyperlinks zurück, falls vorhanden.<br/>            Lese/Schreib **str**. |
| [`tooltip`](/slides/python-net/de/aspose.slides/ihyperlink/tooltip/) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche angezeigt werden kann<br/>            und mit dem übergeordneten Hyperlink verknüpft ist.<br/>            Lese/Schreib **str**. |
| [`history`](/slides/python-net/de/aspose.slides/ihyperlink/history/) | Legt fest, ob das Ziel des übergeordneten Hyperlinks zu einer Liste der angezeigten Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird.<br/>            Lese/Schreib **bool**. |
| [`highlight_click`](/slides/python-net/de/aspose.slides/ihyperlink/highlight_click/) | Legt fest, ob der Hyperlink beim Klicken hervorgehoben werden soll.<br/>            Lese/Schreib **bool**. |
| [`stop_sound_on_click`](/slides/python-net/de/aspose.slides/ihyperlink/stop_sound_on_click/) | Legt fest, ob der Ton beim Klicken auf den Hyperlink gestoppt werden soll.<br/>            Lese/Schreib **bool**. |
| [`sound`](/slides/python-net/de/aspose.slides/ihyperlink/sound/) | Stellt den abgespielten Ton des Hyperlinks dar.<br/>            Lese/Schreib [`IAudio`](/slides/python-net/de/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/de/aspose.slides/ihyperlink/color_source/) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat.<br/>            Lese/Schreib [`HyperlinkColorSource`](/slides/python-net/de/aspose.slides/hyperlinkcolorsource). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/de/aspose.slides/ihyperlink/equals/#ihyperlink) | Legt fest, ob die beiden Hyperlink-Instanzen gleich sind. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)