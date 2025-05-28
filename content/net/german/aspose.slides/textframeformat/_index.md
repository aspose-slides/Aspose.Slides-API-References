---
title: TextFrameFormat
second_title: Aspose.Slides für .NET API Referenz
description: Enthält die formatTextFrameFormatting Eigenschaften von TextFrames.
type: docs
weight: 10650
url: /de/aspose.slides/textframeformat/
---

## TextFrameFormat-Klasse

Enthält die formatTextFrameFormatting Eigenschaften des TextFrame.

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
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Gibt den vertikalen Ankertext in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle IPresentationComponent. Nur lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Gibt den Autofit-Modus des Textes zurück oder setzt ihn. Lesen/Schreiben [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Wenn NullableBool.True, sollte der Text horizontal im Feld zentriert sein. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Gibt die Anzahl der Spalten im Textbereich zurück oder setzt sie. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf null gesetzt. Ein Wert von 0 bedeutet, dass der Wert undefiniert ist. Lesen/Schreiben Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Gibt den Abstand zwischen den Textspalten im Textbereich (in Punkten) zurück oder setzt ihn. Dies sollte nur gelten, wenn mehr als 1 Spalte vorhanden ist. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf null gesetzt. Lesen/Schreiben Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Gibt an, ob der Text flach gehalten wird, auch wenn ein 3-D Rotations-Effekt angewendet wurde. Lesen/Schreiben Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lesen/Schreiben Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Gibt die benutzerdefinierte Drehung an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn nicht angegeben, wird die Drehung der begleitenden Form verwendet. Wenn angegeben, wird sie unabhängig von der Form angewendet. Das bedeutet, dass die Form zusätzlich zur Textdrehung eine Drehung erhalten kann. Der sich daraus ergebende Wert der visuellen Textdrehung fasst diesen Wert sowie den vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammen. Lesen/Schreiben Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Bestimmt die Textausrichtung. Der sich daraus ergebende Wert der visuellen Textdrehung fasst diesen Wert sowie den benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammen. Lesen/Schreiben [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekt-Eigenschaften für einen Text repräsentiert. Nur lesen [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Gibt die Textumbruchform zurück oder setzt sie. Lesen/Schreiben [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, wenn der Text an den Rändern des TextFrames umbrochen wird. Lesen/Schreiben [`NullableBool`](../nullablebool). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Gibt die effektiven Daten zur Textrahmenformatierung mit der angewandten Vererbung zurück. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* Schnittstelle [ITextFrameFormat](../itextframeformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->