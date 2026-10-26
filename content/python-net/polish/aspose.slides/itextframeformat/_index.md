---
title: ITextFrameFormat class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/itextframeformat/
---
## ITextFrameFormat klasa

Zawiera właściwości formatowania TextFrame.

Typ ITextFrameFormat udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`text_style`](/slides/python-net/pl/aspose.slides/itextframeformat/text_style/) | Returns text's style.<br/>            Read-only [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/pl/aspose.slides/itextframeformat/margin_left/) | Zwraca lub ustawia lewy margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_right`](/slides/python-net/pl/aspose.slides/itextframeformat/margin_right/) | Zwraca lub ustawia prawy margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_top`](/slides/python-net/pl/aspose.slides/itextframeformat/margin_top/) | Zwraca lub ustawia górny margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`margin_bottom`](/slides/python-net/pl/aspose.slides/itextframeformat/margin_bottom/) | Zwraca lub ustawia dolny margines (punkty) w TextFrame.<br/>            Odczyt/zapis **float**. |
| [`wrap_text`](/slides/python-net/pl/aspose.slides/itextframeformat/wrap_text/) | **True**  jeśli tekst jest zawijany przy marginesach TextFrame.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/pl/aspose.slides/itextframeformat/anchoring_type/) | Zwraca lub ustawia pionowy kotwiczony tekst w TextFrame.<br/>            Odczyt/zapis [`TextAnchorType`](/slides/python-net/pl/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/pl/aspose.slides/itextframeformat/center_text/) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce poziomo.<br/>            Odczyt/zapis [`NullableBool`](/slides/python-net/pl/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/pl/aspose.slides/itextframeformat/text_vertical_type/) | Określa orientację tekstu.<br/>            Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i własnego kąta<br/>            w właściwości RotationAngle.<br/>            Odczyt/zapis [`TextVerticalType`](/slides/python-net/pl/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/pl/aspose.slides/itextframeformat/autofit_type/) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu.<br/>            Odczyt/zapis [`TextAutofitType`](/slides/python-net/pl/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/pl/aspose.slides/itextframeformat/column_count/) | Zwraca lub ustawia liczbę kolumn w obszarze tekstowym.<br/>            Ta wartość musi być liczbą dodatnią. W przeciwnym wypadku zostanie ustawiona na zero. <br/>            Wartość 0 oznacza niezdefiniowaną wartość.<br/>            Odczyt/zapis **int**. |
| [`column_spacing`](/slides/python-net/pl/aspose.slides/itextframeformat/column_spacing/) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstowym (w punktach). To powinno mieć zastosowanie <br/>            tylko gdy istnieje więcej niż 1 kolumna.<br/>            Ta wartość musi być liczbą dodatnią. W przeciwnym wypadku zostanie ustawiona na zero. <br/>            Odczyt/zapis **float**. |
| [`three_d_format`](/slides/python-net/pl/aspose.slides/itextframeformat/three_d_format/) | Zwraca obiekt ThreeDFormat reprezentujący właściwości efektu 3D dla tekstu.<br/>            Tylko do odczytu [`IThreeDFormat`](/slides/python-net/pl/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/pl/aspose.slides/itextframeformat/keep_text_flat/) | Zwraca lub ustawia całkowite wykluczenie tekstu ze sceny 3D.<br/>            Odczyt/zapis **bool**. |
| [`rotation_angle`](/slides/python-net/pl/aspose.slides/itextframeformat/rotation_angle/) | Określa własny obrót stosowany do tekstu w obrębie ramki. Jeśli nie<br/>            zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, jest on<br/>            stosowany niezależnie od figury. Oznacza to, że figura może mieć obrót, a jednocześnie tekst mieć własny obrót.<br/>            Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego<br/>            typu pionowego w właściwości TextVerticalType.<br/>            Odczyt/zapis **float**. |
| [`transform`](/slides/python-net/pl/aspose.slides/itextframeformat/transform/) | Zwraca lub ustawia kształt zawijania tekstu.<br/>            Odczyt/zapis [`TextShapeType`](/slides/python-net/pl/aspose.slides/textshapetype). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pl/aspose.slides/itextframeformat/get_effective/#) | Zwraca efektywne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)