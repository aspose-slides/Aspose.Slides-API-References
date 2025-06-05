---
title: Hyperlink
second_title: Aspose.Slides für .NET API Referenz
description: Stellt einen Hyperlink dar.
type: docs
weight: 4920
url: /de/aspose.slides/hyperlink/
---

## Hyperlink-Klasse

Stellt einen Hyperlink dar.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Erstellt eine Instanz eines Hyperlinks, die auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt aus derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert. |
| [Hyperlink](hyperlink#constructor_2)(string) | Erstellt eine Instanz eines Hyperlinks. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gibt einen Hyperlink zurück, der die Präsentation beendet. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Gibt einen Hyperlink zur zuletzt angesehenen Folie zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Gibt einen speziellen "Play-Mediafile"-Hyperlink zurück. Wird in AudioFrame und VideoFrame verwendet. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Gibt einen Hyperlink zur nächsten Folie zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Gibt einen speziellen "Do nothing"-Hyperlink zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Gibt einen Hyperlink zur vorherigen Folie zurück. Nur lesbarer [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Gibt den Typ der Aktion des Hyperlinks zurück. Nur lesbarer [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur lesbarer [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Stellt die Quelle der Hyperlinkfarbe dar - entweder Stile oder Portionsformat. Lese-/Schreibzugriff [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Gibt die externe URL an. Nur lesbarer String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Stellt einen Hyperlink dar, der für diesen Teil ohne Berücksichtigung des tatsächlichen Inhalts des Teils festgelegt ist. PowerPoint verhält sich speziell für Links und deren entsprechenden Text in einem Teil. Es erlaubt, Text für den Hyperlink in Form einer gültigen URL zu erstellen, die sich von der tatsächlichen Adresse des Links unterscheidet. In diesem Fall wird der Link im Bearbeitungsfenster geändert, um mit dem Textteil übereinzustimmen. Diese Eigenschaft stellt den ursprünglichen Wert des Hyperlinks dar. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestimmt, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lese-/Schreibzugriff Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestimmt, ob das Ziel des übergeordneten Hyperlinks zu einer Liste der angesehenen Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. Lese-/Schreibzugriff Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Stellt den spielenden Ton des Hyperlinks dar. Lese-/Schreibzugriff [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestimmt, ob der Ton beim Klicken auf den Hyperlink gestoppt werden soll. Lese-/Schreibzugriff Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Gibt das Rahmen innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, wenn eines vorhanden ist. Lese-/Schreibzugriff String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Gibt die Folie zurück, wenn der Hyperlink auf eine bestimmte Folie abzielt. Nur lesbarer [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Gibt den String zurück, der in einer Benutzeroberfläche als mit dem übergeordneten Hyperlink verbunden dargestellt werden kann. Lese-/Schreibzugriff String. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als Hashfunktion für einen bestimmten Typ und ist geeignet für die Verwendung in Hashing-Algorithmen und Datenstrukturen wie einer Hashtabelle. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testet zwei Hyperlinks auf Gleichheit. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testet zwei Hyperlinks auf Ungleichheit. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IHyperlink](../ihyperlink)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../) 

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->