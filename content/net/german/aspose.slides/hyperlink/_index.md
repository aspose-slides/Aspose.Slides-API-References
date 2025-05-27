---
title: Hyperlink
second_title: Aspose.Slides für .NET API-Referenz
description: Repräsentiert einen Hyperlink.
type: docs
weight: 4920
url: /de/aspose.slides/hyperlink/
---

## Hyperlink-Klasse

Repräsentiert einen Hyperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt aus derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert. |
| [Hyperlink](hyperlink#constructor_2)(string) | Erstellt eine Instanz eines Hyperlinks. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Erstellt eine Instanz eines Hyperlinks, indem ein anderer Hyperlink als Quelle verwendet wird, wobei sekundäre Eigenschaften überschrieben werden. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gibt einen Hyperlink zurück, der die Präsentation beendet. Nur lesend [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Gibt einen Hyperlink zur zuletzt angesehenen Folie zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Gibt einen speziellen Hyperlink "Medienfile abspielen" zurück. Wird in AudioFrame und VideoFrame verwendet. Nur lesend [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Gibt einen Hyperlink zur nächsten Folie zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Gibt einen speziellen Hyperlink "nichts tun" zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Gibt einen Hyperlink zur vorherigen Folie zurück. Nur lesend [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Gibt den Typ der Aktion des Hyperlinks zurück. Nur lesend [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur lesend [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Repräsentiert die Quelle der Hyperlink-Farbe - entweder Stile oder Abschnittsformat. Schreib-/lesbar [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Gibt die externe URL an. Nur lesend String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Repräsentiert einen Hyperlink, der für diesen Abschnitt festgelegt wurde, ohne Berücksichtigung des tatsächlichen Inhalts des Abschnitts. PowerPoint verhält sich speziell für Links und deren entsprechenden Text in einem Abschnitt. Es ermöglicht, Text für den Hyperlink in Form einer gültigen URL zu erstellen, die sich von der tatsächlichen Adresse des Links unterscheidet. In diesem Fall wird der Link im Bearbeitungsfenster geändert, um dem Textabschnitt zu entsprechen. Diese Eigenschaft repräsentiert den ursprünglichen Wert des Hyperlinks. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Bestimmt, ob der Hyperlink bei einem Klick hervorgehoben werden soll. Schreib-/lesbar Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Bestimmt, ob das Ziel des übergeordneten Hyperlinks zu einer Liste angezeigter Hyperlinks hinzugefügt werden soll, wenn es aufgerufen wird. Schreib-/lesbar Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Repräsentiert den abspielenden Sound des Hyperlinks. Schreib-/lesbar [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Bestimmt, ob der Sound beim Klicken auf den Hyperlink gestoppt werden soll. Schreib-/lesbar Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Gibt das Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, wenn eines existiert. Schreib-/lesbar String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Gibt, wenn der Hyperlink auf eine bestimmte Folie abzielt, diese Folie zurück. Nur lesend [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Gibt den String zurück, der in einer Benutzeroberfläche als mit dem übergeordneten Hyperlink verbunden angezeigt werden kann. Schreib-/lesbar String. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als Hashfunktion für einen bestimmten Typ, geeignet für die Verwendung in Hash-Algorithmen und Datenstrukturen wie einer Hash-Tabelle. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Überprüft zwei Hyperlinks auf Gleichheit. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Überprüft zwei Hyperlinks auf Ungleichheit. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IHyperlink](../ihyperlink)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->