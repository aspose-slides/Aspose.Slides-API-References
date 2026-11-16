---
title: TextFrameFormat
second_title: Aspose.Sildes dla .NET Referencja API
description: Zawiera właściwości formatTextFrameFormatting obiektów TextFrames.
type: docs
weight: 10980
url: /pl/aspose.slides/textframeformat/
---
## TextFrameFormat klasa

Zawiera właściwości formatTextFrameFormatting obiektu TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inicjalizuje nową instancję klasy [`TextFrameFormat`](../textframeformat). |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Zwraca lub ustawia pionowy punkt zaczepienia tekstu w obiekcie TextFrame. Odczyt/zapis [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Zwraca lub ustawia tryb autofit tekstu. Odczyt/zapis [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Jeśli NullableBool.True, tekst powinien być wyśrodkowany poziomo w ramce. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze (w punktach). Powinno obowiązywać tylko gdy istnieje więcej niż 1 kolumna. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Odczyt/zapis Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Zwraca lub ustawia zachowanie płaskiego tekstu, nawet po zastosowaniu efektu obrotu 3D. Odczyt/zapis Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Zwraca lub ustawia dolny margines (w punktach) w obiekcie TextFrame. Odczyt/zapis Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Zwraca lub ustawia lewy margines (w punktach) w obiekcie TextFrame. Odczyt/zapis Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Zwraca lub ustawia prawy margines (w punktach) w obiekcie TextFrame. Odczyt/zapis Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Zwraca lub ustawia górny margines (w punktach) w obiekcie TextFrame. Odczyt/zapis Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki. Jeśli nie zostanie podany, używany jest obrót powiązanej figury. Jeśli zostanie podany, jest stosowany niezależnie od figury. To znaczy, że figura może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3D dla tekstu. Tylko do odczytu [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Zwraca lub ustawia kształt zawijania tekstu. Odczyt/zapis [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [`NullableBool`](../nullablebool). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Zwraca skuteczne dane formatowania ramki tekstowej z uwzględnionym dziedziczeniem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfejs [ITextFrameFormat](../itextframeformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zbiór [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->