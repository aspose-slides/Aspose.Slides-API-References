---
title: Hyperlink
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Hyperlink dar.
type: docs
weight: 5120
url: /de/aspose.slides/hyperlink/
---
## Hyperlink Klasse

Stellt einen Hyperlink dar.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert. |
| [Hyperlink](hyperlink#constructor_2)(string) | Erstellt eine Instanz eines Hyperlinks. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gibt einen Hyperlink zurück, der die Präsentation beendet. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Gibt einen Hyperlink zur zuletzt angezeigten Folie zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Gibt einen speziellen "play mediafile"-Hyperlink zurück. Wird in AudioFrame und VideoFrame verwendet. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Gibt einen Hyperlink zur nächsten Folie zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Gibt einen speziellen "do nothing"-Hyperlink zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Gibt einen Hyperlink zur vorherigen Folie zurück. Nur lesbar [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Gibt den Typ der Hyperlink-Aktion zurück. Nur lesbar [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Abschnittsformat. Lese-/Schreibzugriff [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Gibt die externe URL an. Nur lesbarer String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Stellt einen Hyperlink dar, der für diesen Abschnitt festgelegt ist, ohne Rücksicht auf den tatsächlichen Inhalt des Abschnitts. PowerPoint verhält sich speziell für Links und den zugehörigen Text in einem Abschnitt. Es ermöglicht, Text für den Hyperlink in Form einer gültigen URL zu erstellen, die von der tatsächlichen Adresse des Links abweicht. In diesem Fall wird beim Anzeigen des Links im Bearbeitungsfenster der Textanteil angepasst. Diese Eigenschaft stellt den ursprünglichen Wert des Hyperlinks dar. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestimmt, ob der Hyperlink beim Klick hervorgehoben werden soll. Lese-/Schreib-Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestimmt, ob das Ziel des übergeordneten Hyperlinks zur Liste der angesehenen Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. Lese-/Schreib-Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Stellt den Abtastsound des Hyperlinks dar. Lese-/Schreib-[`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestimmt, ob der Sound beim Klick auf den Hyperlink gestoppt werden soll. Lese-/Schreib-Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Gibt den Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, falls vorhanden. Lese-/Schreib-String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Wenn der Hyperlink auf eine bestimmte Folie zielt, wird diese Folie zurückgegeben. Nur lesbar [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Gibt die Zeichenkette zurück, die in einer Benutzeroberfläche als mit dem übergeordneten Hyperlink assoziiert angezeigt werden kann. Lese-/Schreib-String. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als Hashfunktion für einen bestimmten Typ und ist geeignet für den Einsatz in Hash-Algorithmen und Datenstrukturen wie einer Hashtabelle. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testet zwei Hyperlinks auf Gleichheit. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testet zwei Hyperlinks auf Ungleichheit. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IHyperlink](../ihyperlink)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->