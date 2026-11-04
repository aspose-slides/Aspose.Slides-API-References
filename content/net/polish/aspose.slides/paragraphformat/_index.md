---
title: ParagraphFormat
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do IParagraphFormatEffectiveData./iparagraphformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 9330
url: /pl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasa

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktory

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicjalizuje nową instancję klasy [`ParagraphFormat`](../paragraphformat). |

## Właściwości

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Określa, czy w akapicie używana jest wisząca interpunkcja. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Zwraca lub ustawia wcięcie pierwszej linii/wiszące wcięcie akapitu bez dziedziczenia. Wiszące wcięcie może być określone wartościami ujemnymi. Odczyt/zapis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Określa, czy w akapicie używany jest podział linii łaciński. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie stosuje się dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki powinien mieć biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaki powinien mieć biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Zwraca lub ustawia ilość odstępu pomiędzy liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Nie stosuje się dziedziczenia. Odczyt/zapis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Zwraca tabulacje akapitu. Nie stosuje się dziedziczenia. Tylko do odczytu [`ITabCollection`](../itabcollection). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z podanym obiektem. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod skrótu. |

### Uwagi

Ta klasa służy do zwracania i manipulowania właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym dziedziczone, należy użyć metody [`GetEffective`](./geteffective), która zwraca instancję [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Zobacz również

* klasa [PVIObject](../pviobject)
* interfejs [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfejs [IParagraphFormat](../iparagraphformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->