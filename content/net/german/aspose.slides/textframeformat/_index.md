---
title: TextFrameFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Enthält die formatTextFrameFormatting Eigenschaften der TextFrames.
type: docs
weight: 10960
url: /de/aspose.slides/textframeformat/
---
## TextFrameFormat Klasse

Enthält die formatTextFrameFormatting Eigenschaften des TextFrames.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialisiert eine neue Instanz der [`TextFrameFormat`](../textframeformat) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Liefert oder legt den vertikalen Ankertext in einem TextFrame fest. Lesen/Schreiben [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Gibt den Autofit-Modus des Textes zurück oder setzt ihn. Lesen/Schreiben [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Wenn NullableBool.True, dann sollte der Text horizontal im Feld zentriert werden. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Gibt die Anzahl der Spalten im Textbereich zurück oder setzt sie. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Der Wert 0 bedeutet einen undefinierten Wert. Lesen/Schreiben Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Gibt den Abstand zwischen Textspalten im Textbereich zurück oder setzt ihn (in Punkten). Dies sollte nur gelten, wenn mehr als eine Spalte vorhanden ist. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Lesen/Schreiben Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Legt fest, ob der Text flach bleibt, selbst wenn ein 3-D-Rotations-Effekt angewendet wurde. Lesen/Schreiben Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Gibt die benutzerdefinierte Drehung an, die auf den Text im Begrenzungsrahmen angewendet wird. Wenn nicht angegeben, wird die Drehung der zugehörigen Form verwendet. Ist sie angegeben, wird sie unabhängig von der Form angewendet. Das heißt, die Form kann eine Drehung haben, zusätzlich zur Drehung des Textes selbst. Der resultierende Wert der visuellen Textdrehung ergibt sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType. Lesen/Schreiben Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textdrehung ergibt sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle. Lesen/Schreiben [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3-D-Effekteigenschaften für einen Text darstellt. Nur-Lesen [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Legt die Textumbruchform fest oder gibt sie zurück. Lesen/Schreiben [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, wenn der Text an den Rändern des TextFrames umbrochen wird. Lesen/Schreiben [`NullableBool`](../nullablebool). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Ruft die effektiven TextFrame-Formatierungsdaten mit angewandter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* Schnittstelle [ITextFrameFormat](../itextframeformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->