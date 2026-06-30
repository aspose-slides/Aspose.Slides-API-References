---
title: TextFrameFormat
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Zawiera właściwości formatTextFrameFormatting obiektu TextFrames.
type: docs
weight: 10940
url: /pl/aspose.slides/textframeformat/
---
## TextFrameFormat klasa

Zawiera właściwości formatTextFrameFormatting obiektu TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktorzy

| Nazwa | Opis |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inicjalizuje nową instancję klasy [`TextFrameFormat`](../textframeformat). |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Zwraca lub ustawia pionowy punkt kotwiczenia tekstu w ramce TextFrame. Odczyt/zapis [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko odczyt [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Zwraca lub ustawia tryb automatycznego dopasowywania tekstu. Odczyt/zapis [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce poziomo. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Odczyt/zapis Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze (w punktach). Powinno mieć zastosowanie tylko gdy istnieje więcej niż 1 kolumna. Wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Odczyt/zapis Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Pobiera lub ustawia zachowanie tekstu płaskiego nawet po zastosowaniu efektu 3-D Rotation. Odczyt/zapis Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Zwraca lub ustawia dolny margines (w punktach) w ramce TextFrame. Odczyt/zapis Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Zwraca lub ustawia lewy margines (w punktach) w ramce TextFrame. Odczyt/zapis Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Zwraca lub ustawia prawy margines (w punktach) w ramce TextFrame. Odczyt/zapis Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Zwraca lub ustawia górny margines (w punktach) w ramce TextFrame. Odczyt/zapis Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki. Jeśli nie jest podany, używany jest obrót powiązanej figury. Jeśli jest podany, jest stosowany niezależnie od figury. Oznacza to, że figura może mieć obrót, a tekst może mieć dodatkowy własny obrót. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Zwraca obiekt ThreeDFormat reprezentujący właściwości efektu 3D dla tekstu. Tylko odczyt [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Pobiera lub ustawia kształt zawijania tekstu. Odczyt/zapis [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** jeśli tekst jest zawijany przy marginesach TextFrame. Odczyt/zapis [`NullableBool`](../nullablebool). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Pobiera efektywne dane formatowania ramki tekstowej z uwzględnieniem dziedziczenia. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfejs [ITextFrameFormat](../itextframeformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->