---
title: Hyperlink class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/hyperlink/
---
## Hyperlink-Klasse

Stellt einen Hyperlink dar.

**Vererbung:**[`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)

Der Hyperlink-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/de/aspose.slides/hyperlink/__init__/#str) | Erstellt eine Instanz eines Hyperlinks. |
| [`__init__(self, slide)`](/slides/python-net/de/aspose.slides/hyperlink/__init__/#islide) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist.<br/>            Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/de/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Erstellt eine Instanz eines Hyperlinks, der eine andere Hyperlink-Quelle verwendet und sekundäre Eigenschaften überschreibt. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`no_action`](/slides/python-net/de/aspose.slides/hyperlink/no_action/) | Gibt einen speziellen „do nothing“-Hyperlink zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/de/aspose.slides/hyperlink/media/) | Gibt einen speziellen „play mediafile“-Hyperlink zurück. Wird in AudioFrame und VideoFrame verwendet.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/de/aspose.slides/hyperlink/next_slide/) | Gibt einen Hyperlink zur nächsten Folie zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/de/aspose.slides/hyperlink/previous_slide/) | Gibt einen Hyperlink zur vorherigen Folie zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/de/aspose.slides/hyperlink/first_slide/) | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/de/aspose.slides/hyperlink/last_slide/) | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/de/aspose.slides/hyperlink/last_vieved_slide/) | Gibt einen Hyperlink zur zuletzt angezeigten Folie zurück.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/de/aspose.slides/hyperlink/end_show/) | Gibt einen Hyperlink zurück, der die Show beendet.<br/>            Nur-Lesen [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/de/aspose.slides/hyperlink/action_type/) | Gibt den Typ der Hyperlink-Aktion zurück.<br/>            Nur-Lesen [`HyperlinkActionType`](/slides/python-net/de/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/de/aspose.slides/hyperlink/external_url/) | Gibt die externe URL an.<br/>            Nur-Lesen **str**. |
| [`target_slide`](/slides/python-net/de/aspose.slides/hyperlink/target_slide/) | Falls der Hyperlink auf eine bestimmte Folie verweist, wird diese Folie zurückgegeben.<br/>            Nur-Lesen [`ISlide`](/slides/python-net/de/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/de/aspose.slides/hyperlink/external_url_original/) | Stellt einen Hyperlink dar, der für diesen Teilbereich festgelegt ist, unabhängig vom tatsächlichen Inhalt des Teilbereichs.<br/>            <br/>            PowerPoint verhält sich speziell bei Links und dem zugehörigen Text in einem Teilbereich. Es ermöglicht, den Text für den Hyperlink in<br/>            Form einer gültigen URL zu erstellen, die von der tatsächlichen Adresse des Links abweicht. In diesem Fall wird beim Anzeigen des Links im Bearbeitungsfenster der Text<br/>            an den Textteil angepasst. Diese Eigenschaft stellt den ursprünglichen Wert des Hyperlinks dar. |
| [`target_frame`](/slides/python-net/de/aspose.slides/hyperlink/target_frame/) | Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel<br/>            des übergeordneten Hyperlinks zurück, falls vorhanden.<br/>            Read/wite **str**. |
| [`tooltip`](/slides/python-net/de/aspose.slides/hyperlink/tooltip/) | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche angezeigt werden kann<br/>            und mit dem übergeordneten Hyperlink verknüpft ist.<br/>            Lesen/Schreiben **str**. |
| [`history`](/slides/python-net/de/aspose.slides/hyperlink/history/) | Bestimmt, ob das Ziel des übergeordneten Hyperlinks zu einer Liste der angezeigten Hyperlinks hinzugefügt werden soll,<br/>            wenn es aufgerufen wird.<br/>            Lesen/Schreiben **bool**. |
| [`highlight_click`](/slides/python-net/de/aspose.slides/hyperlink/highlight_click/) | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll.<br/>            Lesen/Schreiben **bool**. |
| [`stop_sound_on_click`](/slides/python-net/de/aspose.slides/hyperlink/stop_sound_on_click/) | Bestimmt, ob der Ton beim Klicken auf den Hyperlink gestoppt werden soll.<br/>            Lesen/Schreiben **bool**. |
| [`sound`](/slides/python-net/de/aspose.slides/hyperlink/sound/) | Stellt den abgespielten Ton des Hyperlinks dar.<br/>            Lesen/Schreiben [`IAudio`](/slides/python-net/de/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/de/aspose.slides/hyperlink/color_source/) | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Teilbereichsformat.<br/>            Lesen/Schreiben [`HyperlinkColorSource`](/slides/python-net/de/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/de/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/de/aspose.slides/hyperlink/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/de/aspose.slides/hyperlink/equals/#ihyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |


### Siehe auch
* Klasse [`Hyperlink`](/slides/python-net/de/aspose.slides/hyperlink)
* Klasse [`PVIObject`](/slides/python-net/de/aspose.slides/pviobject)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)