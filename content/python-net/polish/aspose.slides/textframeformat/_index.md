---
title: TextFrameFormat class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/textframeformat/
---
## TextFrameFormat klasa

Zawiera właściwości formatTextFrameFormatting TextFrame.

**Dziedziczenie:**[`TextFrameFormat`](/slides/python-net/pl/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)

Typ TextFrameFormat udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/textframeformat/__init__/#) | Inicjalizuje nową instancję klasy [`TextFrameFormat`](/slides/python-net/pl/aspose.slides/textframeformat). |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/textframeformat/three_d_format/) | Zwraca obiekt ThreeDFormat, który reprezentuje właściwości efektu 3d dla tekstu.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/pl/aspose.slides/textframeformat/margin_left/) | Zwraca lub ustawia lewy margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/textframeformat/margin_right/) | Zwraca lub ustawia prawy margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_top`](/slides/python-net/pl/aspose.slides/textframeformat/margin_top/) | Zwraca lub ustawia górny margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_bottom`](/slides/python-net/pl/aspose.slides/textframeformat/margin_bottom/) | Zwraca lub ustawia dolny margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`wrap_text`](/slides/python-net/pl/aspose.slides/textframeformat/wrap_text/) | **True** jeśli tekst jest zawijany przy marginesach TextFrame.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/pl/aspose.slides/textframeformat/anchoring_type/) | Zwraca lub ustawia pionowy punkt zaczepienia tekstu w TextFrame.<br/>            Odczyt/zapis [`TextAnchorType`](/slides/python-net/pl/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/pl/aspose.slides/textframeformat/center_text/) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/pl/aspose.slides/textframeformat/text_vertical_type/) | Określa orientację tekstu.<br/>            Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta<br/>            w właściwości RotationAngle.<br/>            Odczyt/zapis [`TextVerticalType`](/slides/python-net/pl/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/pl/aspose.slides/textframeformat/autofit_type/) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu.<br/>            Odczyt/zapis [`TextAutofitType`](/slides/python-net/pl/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/pl/aspose.slides/textframeformat/column_count/) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu.<br/>            Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero.<br/>            Wartość 0 oznacza nieokreśloną wartość.<br/>            Odczyt/zapis **int**. |
| [`column_spacing`](/slides/python-net/pl/aspose.slides/textframeformat/column_spacing/) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze (w punktach). To powinno mieć zastosowanie <br/>            tylko gdy jest więcej niż 1 kolumna.<br/>            Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero.<br/>            Odczyt/zapis **float**. |
| [`rotation_angle`](/slides/python-net/pl/aspose.slides/textframeformat/rotation_angle/) | Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki. Jeśli nie<br/>            zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, jest on<br/>            stosowany niezależnie od figury. To znaczy, że figura może mieć zastosowany obrót<br/>            oprócz tego, że sam tekst ma zastosowany obrót.<br/>            Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego<br/>            typu pionowego w właściwości TextVerticalType.<br/>            Odczyt/zapis **float**. |
| [`transform`](/slides/python-net/pl/aspose.slides/textframeformat/transform/) | Zwraca lub ustawia kształt owijania tekstu.<br/>            Odczyt/zapis [`TextShapeType`](/slides/python-net/pl/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/pl/aspose.slides/textframeformat/keep_text_flat/) | Zwraca lub ustawia zachowanie płaskości tekstu mimo zastosowania efektu obrotu 3-D.<br/>            Odczyt/zapis **bool**. |
| [`slide`](/slides/python-net/pl/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/pl/aspose.slides/textframeformat/text_style/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/textframeformat/get_effective/#) | Zwraca efektywne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem. |


### Zobacz także
* klasa [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)
* klasa [`TextFrameFormat`](/slides/python-net/pl/aspose.slides/textframeformat)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)