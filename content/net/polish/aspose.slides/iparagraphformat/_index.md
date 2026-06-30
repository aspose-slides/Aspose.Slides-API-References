---
title: IParagraphFormat
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do IParagraphFormatEffectiveData./iparagraphformateffectivedata wszystkie właściwości tej klasy są zapisywalne.
type: docs
weight: 6570
url: /pl/aspose.slides/iparagraphformat/
---
## IParagraphFormat interfejs

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

```csharp
public interface IParagraphFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Zwraca format wypunktowania akapitu. Tylko odczyt [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Zwraca domyślny format części akapitu. Nie zastosowano dziedziczenia. Tylko odczyt [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Zwraca lub ustawia głębokość akapitu. Wartość 0 oznacza niezdefiniowaną wartość. Odczyt/zapis Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Określa, czy w akapicie używane jest łamanie linii w stylu wschodnioazjatyckim. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Określa, czy w akapicie używana jest interpunkcja zwisająca. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Zwraca lub ustawia wcięcie pierwszej linii/ wcięcie zwisające akapitu bez dziedziczenia. Wcięcie zwisające może być określone wartościami ujemnymi. Odczyt/zapis Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Określa, czy w akapicie używane jest łamanie linii łacińskie. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia. Odczyt/zapis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma mieć biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Wartość dodatnia określa procent rozmiaru czcionki, jaką ma mieć biały odstęp. Wartość ujemna określa rozmiar białego odstępu w punktach. Odczyt/zapis Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. Wartość dodatnia oznacza procent, ujemna – rozmiar w punktach. Nie zastosowano dziedziczenia. Odczyt/zapis Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Zwraca tabulacje akapitu. Nie zastosowano dziedziczenia. Tylko odczyt [`ITabCollection`](../itabcollection). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem. |

### Uwagi

Ta klasa służy do zwracania i manipulacji właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające "undefined".

Aby uzyskać efektywne wartości parametrów formatowania, w tym dziedziczone, musisz użyć metody [`GetEffective`](./geteffective), która zwraca instancję [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->