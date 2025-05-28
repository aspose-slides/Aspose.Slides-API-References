---
title: Hyperlink
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt einen Hyperlink dar.
type: docs
weight: 4670
url: /de/aspose.slides/hyperlink/
---
## Hyperlink class

Stellt einen Hyperlink dar.

```csharp
public class Hyperlink : PVIObject, IHyperlink
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Erstellt eine Instanz eines Hyperlinks, der auf eine bestimmte Folie verweist. Hinweis: Der erstellte Hyperlink sollte einem Objekt aus derselben Präsentation zugewiesen werden, andernfalls wird der Link als NoAction gespeichert. |
| [Hyperlink](hyperlink#constructor_2)(string) | Erstellt eine Instanz eines Hyperlinks. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Erstellt eine Instanz eines Hyperlinks unter Verwendung eines anderen Hyperlinks als Quelle und überschreibt sekundäre Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Gibt einen Hyperlink zurück, der die Show beendet. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Gibt einen Hyperlink zur ersten Folie der Präsentation zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Gibt einen Hyperlink zur letzten Folie der Präsentation zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Gibt einen Hyperlink zur zuletzt angezeigten Folie zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Gibt einen speziellen "Mediendatei abspielen"-Hyperlink zurück. Wird in AudioFrame und VideoFrame verwendet. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Gibt einen Hyperlink zur nächsten Folie zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Gibt einen speziellen "Nichts tun"-Hyperlink zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Gibt einen Hyperlink zur vorherigen Folie zurück. Schreibgeschützt[`Hyperlink`](../hyperlink) . |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Gibt den Aktionstyp des Hyperlinks zurück. Schreibgeschützt[`HyperlinkActionType`](../hyperlinkactiontype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../ipresentationcomponent) . |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Stellt die Quelle der Hyperlink-Farbe dar – entweder Stile oder Teilformat. Lesen/Schreiben[`HyperlinkColorSource`](../hyperlinkcolorsource) . |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Gibt die externe URL an. SchreibgeschütztString . |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Legt fest, ob der Hyperlink beim Klicken hervorgehoben werden soll. Lesen/SchreibenBoolean . |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Legt fest, ob das Ziel des übergeordneten Hyperlinks beim Aufrufen zu einer Liste der angezeigten Hyperlinks hinzugefügt werden soll. Lesen/SchreibenBoolean . |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Legt fest, ob der Ton beim Klicken auf einen Hyperlink gestoppt werden soll. Lesen/SchreibenBoolean . |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Gibt den Frame innerhalb des übergeordneten HTML-Framesets für das Ziel des übergeordneten Hyperlinks zurück, sofern vorhanden. Lesen/SchreibenString . |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Wenn der Hyperlink auf eine bestimmte Folie abzielt, wird diese Folie zurückgegeben. Schreibgeschützt[`ISlide`](../islide) . |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Gibt die Zeichenfolge zurück, die in einer Benutzerschnittstelle angezeigt werden kann, die mit dem übergeordneten Hyperlink verknüpft ist. Lesen/SchreibenString . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Bestimmt, ob die beiden Hyperlink-Instanzen gleich sind. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Dient als Hash-Funktion für einen bestimmten Typ, geeignet für die Verwendung in Hash-Algorithmen und Datenstrukturen wie einer Hash-Tabelle. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testet zwei Hyperlinks auf Gleichheit. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testet zwei Hyperlinks auf Ungleichheit. |

### Siehe auch

* class [PVIObject](../pviobject)
* interface [IHyperlink](../ihyperlink)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
