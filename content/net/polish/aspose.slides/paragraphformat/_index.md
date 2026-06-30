---
title: ParagraphFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Ta klasa zawiera właściwości formatowania akapitu. W odróżnieniu od IParagraphFormatEffectiveData./iparagraphformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 9290
url: /pl/aspose.slides/paragraphformat/
---
## Klasa ParagraphFormat

Ta klasa zawiera własności formatowania akapitu. W przeciwieństwie do [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), wszystkie własności tej klasy są zapisywalne.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicjalizuje nową instancję klasy [`ParagraphFormat`](../paragraphformat). |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Określa, czy w akapicie używana jest odstająca interpunkcja. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Zwraca lub ustawia wcięcie pierwszej linii/odstające wcięcie akapitu bez dziedziczenia. Odstające wcięcie może być określone wartościami ujemnymi. Odczyt/zapis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Określa, czy w akapicie używany jest podział linii łacińskiej. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki ma zajmować biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Nie stosuje się dziedziczenia. Odczyt/zapis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Zwraca tabulacje akapitu. Nie stosuje się dziedziczenia. Tylko do odczytu [`ITabCollection`](../itabcollection). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Uwagi

Ta klasa służy do zwracania i manipulacji własnościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym dziedziczone, musisz użyć metody [`GetEffective`](./geteffective), która zwraca instancję [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfejs [IParagraphFormat](../iparagraphformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->