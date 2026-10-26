---
title: ParagraphFormat class
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/paragraphformat/
---
## ParagraphFormat klasa

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

**Dziedziczenie:**[`ParagraphFormat`](/slides/python-net/pl/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)

Typ ParagraphFormat udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/paragraphformat/__init__/#) | Inicjalizuje nową instancję klasy [`ParagraphFormat`](/slides/python-net/pl/aspose.slides/paragraphformat). |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`alignment`](/slides/python-net/pl/aspose.slides/paragraphformat/alignment/) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia.<br/>            Odczyt/Zapis [`TextAlignment`](/slides/python-net/pl/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/pl/aspose.slides/paragraphformat/space_within/) | Zwraca lub ustawia ilość odstępu między podstawowymi liniami w akapicie. Dodatnia wartość oznacza procent, ujemna - rozmiar w punktach. Nie stosuje się dziedziczenia.<br/>            Odczyt/Zapis **float**. |
| [`space_before`](/slides/python-net/pl/aspose.slides/paragraphformat/space_before/) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia.<br/>            Dodatnia wartość określa procent rozmiaru czcionki, jaki ma mieć biały odstęp.<br/>            Ujemna wartość określa rozmiar białego odstępu w punktach.<br/>            Odczyt/Zapis **float**. |
| [`space_after`](/slides/python-net/pl/aspose.slides/paragraphformat/space_after/) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia.<br/>            Dodatnia wartość określa procent rozmiaru czcionki, jaki ma mieć biały odstęp.<br/>            Ujemna wartość określa rozmiar białego odstępu w punktach.<br/>            Odczyt/Zapis **float**. |
| [`east_asian_line_break`](/slides/python-net/pl/aspose.slides/paragraphformat/east_asian_line_break/) | Określa, czy w akapicie używany jest podział linii w stylu wschodnioazjatyckim. Nie stosuje się dziedziczenia.<br/>            Odczyt/Zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/pl/aspose.slides/paragraphformat/right_to_left/) | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie stosuje się dziedziczenia.<br/>            Odczyt/Zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/pl/aspose.slides/paragraphformat/latin_line_break/) | Określa, czy w akapicie używany jest podział linii łaciński. Nie stosuje się dziedziczenia.<br/>            Odczyt/Zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/pl/aspose.slides/paragraphformat/hanging_punctuation/) | Określa, czy w akapicie używana jest wieszająca interpunkcja. Nie stosuje się dziedziczenia.<br/>            Odczyt/Zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/pl/aspose.slides/paragraphformat/margin_left/) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia.<br/>            Odczyt/Zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/paragraphformat/margin_right/) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia.<br/>            Odczyt/Zapis **float**. |
| [`indent`](/slides/python-net/pl/aspose.slides/paragraphformat/indent/) | Zwraca lub ustawia wcięcie pierwszej linii/ wcięcie wiszące w akapicie bez dziedziczenia. Wcięcie wiszące może być określone wartościami ujemnymi.<br/>            Odczyt/Zapis **float**. |
| [`default_tab_size`](/slides/python-net/pl/aspose.slides/paragraphformat/default_tab_size/) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia.<br/>            Odczyt/Zapis **float**. |
| [`tabs`](/slides/python-net/pl/aspose.slides/paragraphformat/tabs/) | Zwraca tabulacje akapitu. Nie stosuje się dziedziczenia.<br/>            Tylko do odczytu [`ITabCollection`](/slides/python-net/pl/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/pl/aspose.slides/paragraphformat/font_alignment/) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia.<br/>            Odczyt/Zapis [`FontAlignment`](/slides/python-net/pl/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/pl/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/pl/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/pl/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/pl/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/paragraphformat/get_effective/#) | Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem. |

### Uwagi

Ta klasa służy do zwracania i modyfikowania właściwości formatowania akapitu zdefiniowanych dla konkretnego akapitu. Oznacza to, że
            nie stosuje się dziedziczenia przy pobieraniu wartości, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym odziedziczone, musisz użyć metody [`ParagraphFormat.get_effective`](/slides/python-net/pl/aspose.slides/paragraphformat/get_effective)
            która zwraca instancję [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata).

### Zobacz także
* klasa [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata)
* klasa [`ParagraphFormat`](/slides/python-net/pl/aspose.slides/paragraphformat)
* klasa [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)