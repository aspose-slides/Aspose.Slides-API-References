---
title: TextFrameFormat
second_title: Aspose.Slides für .NET API Referenz
description: Enthält die Eigenschaften des TextFrames formatTextFrameFormatting.
type: docs
weight: 10650
url: /de/aspose.slides/textframeformat/
---

## TextFrameFormat-Klasse

Enthält die Eigenschaften des TextFrame-Formats formatTextFrameFormatting.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Initialisiert eine neue Instanz der Klasse [`TextFrameFormat`](../textframeformat). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Gibt den vertikalen Ankertext in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff auf [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-Interface IPresentationComponent. Nur Lesezugriff auf [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Gibt den Autofit-Modus des Textes zurück oder setzt ihn. Lese-/Schreibzugriff auf [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Wenn NullableBool.True, sollte der Text horizontal im Feld zentriert werden. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Gibt die Anzahl der Spalten im Textbereich zurück oder setzt sie. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Wert 0 bedeutet undefinierter Wert. Lese-/Schreibzugriff auf Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Gibt den Abstand zwischen den Textspalten im Textbereich (in Punkten) zurück oder setzt ihn. Dies sollte nur gelten, wenn mehr als 1 Spalte vorhanden ist. Dieser Wert muss eine positive Zahl sein. Andernfalls wird der Wert auf Null gesetzt. Lese-/Schreibzugriff auf Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Holt oder setzt, dass der Text flach bleibt, auch wenn ein 3-D-Rotationseffekt angewendet wurde. Lese-/Schreibzugriff auf Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Gibt den unteren Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff auf Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Gibt den linken Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff auf Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Gibt den rechten Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff auf Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Gibt den oberen Rand (Punkte) in einem TextFrame zurück oder setzt ihn. Lese-/Schreibzugriff auf Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Gibt die benutzerdefinierte Rotation an, die auf den Text innerhalb des Begrenzungsrahmens angewendet wird. Wenn nicht angegeben, wird die Rotation der begleitenden Form verwendet. Wenn sie angegeben wird, wird diese unabhängig von der Form angewendet. Das heißt, die Form kann zusätzlich zur Rotation des Textes selbst eine Rotation haben. Der resultierende Wert der visuellen Textrotation fasst sich aus dieser Eigenschaft und dem vordefinierten vertikalen Typ in der Eigenschaft TextVerticalType zusammen. Lese-/Schreibzugriff auf Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Bestimmt die Textausrichtung. Der resultierende Wert der visuellen Textrotation fasst sich aus dieser Eigenschaft und dem benutzerdefinierten Winkel in der Eigenschaft RotationAngle zusammen. Lese-/Schreibzugriff auf [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Gibt das ThreeDFormat-Objekt zurück, das die 3D-Effekteigenschaften für einen Text repräsentiert. Nur Lesezugriff auf [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Holt oder setzt die Form des Textumbruchs. Lese-/Schreibzugriff auf [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, wenn der Text an den Rändern des TextFrames umbrochen wird. Lese-/Schreibzugriff auf [`NullableBool`](../nullablebool). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Holt die wirksamen Textframe-Formatierungsdaten mit angewandter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe Auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* Schnittstelle [ITextFrameFormat](../itextframeformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->