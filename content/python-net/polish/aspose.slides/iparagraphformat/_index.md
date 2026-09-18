---
title: IParagraphFormat class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/iparagraphformat/
---
## IParagraphFormat klasa

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

Typ IParagraphFormat udostępnia następujące elementy:

## Properties

| Właściwość | Opis |
| :- | :- |
| [`bullet`](/slides/python-net/pl/aspose.slides/iparagraphformat/bullet/) | Zwraca format wypunktowania akapitu.<br/>            Tylko do odczytu [`IBulletFormat`](/slides/python-net/pl/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/pl/aspose.slides/iparagraphformat/depth/) | Zwraca lub ustawia głębokość akapitu.<br/>            Wartość 0 oznacza nieokreśloną wartość.<br/>            Odczyt/zapis **int**. |
| [`alignment`](/slides/python-net/pl/aspose.slides/iparagraphformat/alignment/) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia.<br/>            Odczyt/zapis [`TextAlignment`](/slides/python-net/pl/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/pl/aspose.slides/iparagraphformat/space_within/) | Zwraca lub ustawia ilość odstępu między liniami bazowymi w akapicie. Dodatnia wartość oznacza procent, ujemna – rozmiar w punktach. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis **float**. |
| [`space_before`](/slides/python-net/pl/aspose.slides/iparagraphformat/space_before/) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia.<br/>            Dodatnia wartość określa procent rozmiaru czcionki, jaki ma stanowić biały odstęp.<br/>            Ujemna wartość określa rozmiar białego odstępu w punktach.<br/>            Odczyt/zapis **float**. |
| [`space_after`](/slides/python-net/pl/aspose.slides/iparagraphformat/space_after/) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia.<br/>            Dodatnia wartość określa procent rozmiaru czcionki, jaki ma stanowić biały odstęp.<br/>            Ujemna wartość określa rozmiar białego odstępu w punktach.<br/>            Odczyt/zapis **float**. |
| [`east_asian_line_break`](/slides/python-net/pl/aspose.slides/iparagraphformat/east_asian_line_break/) | Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/pl/aspose.slides/iparagraphformat/right_to_left/) | Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/pl/aspose.slides/iparagraphformat/latin_line_break/) | Określa, czy w akapicie używany jest podział linii łaciński. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/pl/aspose.slides/iparagraphformat/hanging_punctuation/) | Określa, czy w akapicie używana jest zwieszona interpunkcja. Nie zastosowano dziedziczenia.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/pl/aspose.slides/iparagraphformat/margin_left/) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia.<br/>            Odczyt/zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/iparagraphformat/margin_right/) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia.<br/>            Odczyt/zapis **float**. |
| [`indent`](/slides/python-net/pl/aspose.slides/iparagraphformat/indent/) | Zwraca lub ustawia wcięcie pierwszej linii/wiązane wcięcie akapitu bez dziedziczenia. Wiązane wcięcie może być definiowane ujemnymi wartościami.<br/>            Odczyt/zapis **float**. |
| [`default_tab_size`](/slides/python-net/pl/aspose.slides/iparagraphformat/default_tab_size/) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia.<br/>            Odczyt/zapis **float**. |
| [`tabs`](/slides/python-net/pl/aspose.slides/iparagraphformat/tabs/) | Zwraca tabulacje akapitu. Nie zastosowano dziedziczenia.<br/>            Tylko do odczytu [`ITabCollection`](/slides/python-net/pl/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/pl/aspose.slides/iparagraphformat/font_alignment/) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia.<br/>            Odczyt/zapis [`FontAlignment`](/slides/python-net/pl/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/pl/aspose.slides/iparagraphformat/default_portion_format/) | Zwraca domyślny format fragmentu akapitu. Nie zastosowano dziedziczenia.<br/>            Tylko do odczytu [`IPortionFormat`](/slides/python-net/pl/aspose.slides/iportionformat). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/iparagraphformat/get_effective/#) | Pobiera efektywne dane formatowania akapitu z zastosowanym dziedziczeniem. |

### Uwagi

Ta klasa służy do zwracania i manipulowania właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że
            nie stosuje się dziedziczenia przy pobieraniu wartości, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać efektywne wartości parametrów formatowania, w tym dziedziczone, musisz użyć metody [`IParagraphFormat.get_effective`](/slides/python-net/pl/aspose.slides/iparagraphformat/get_effective),
            która zwraca instancję [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata).

### Zobacz także
* klasa [`IParagraphFormatEffectiveData`](/slides/python-net/pl/aspose.slides/iparagraphformateffectivedata)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)