---
title: IHyperlink class
second_title: Aspose.Slides dla Pythona przez .NET - referencja API
description: 
type: docs
url: /pl/aspose.slides/ihyperlink/
---
## IHyperlink klasa

Reprezentuje hiperłącze.

Typ IHyperlink udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`action_type`](/slides/python-net/pl/aspose.slides/ihyperlink/action_type/) | Zwraca typ akcji HyperLinkEx.<br/>            Tylko do odczytu [`HyperlinkActionType`](/slides/python-net/pl/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/pl/aspose.slides/ihyperlink/external_url/) | Określa zewnętrzny URL<br/>            Jeśli ta właściwość nie będzie równa None, to właściwość TargetSlide będzie równa None.<br/>            Tylko do odczytu **str**. |
| [`external_url_original`](/slides/python-net/pl/aspose.slides/ihyperlink/external_url_original/) | Reprezentuje hiperłącze ustawione dla tego fragmentu bez względu na rzeczywistą zawartość fragmentu.<br/>            <br/>            PowerPoint zachowuje się specyficznie względem linków i ich odpowiadającego tekstu w fragmencie. Umożliwia tworzenie tekstu hiperłącza w<br/>            formie prawidłowego URL, różnego od rzeczywistego adresu linku. W takim przypadku, gdy przeglądasz link w oknie edycji, zostanie on<br/>            zmieniony, aby pasował do fragmentu tekstu. Ta właściwość reprezentuje pierwotną wartość hiperłącza. |
| [`target_slide`](/slides/python-net/pl/aspose.slides/ihyperlink/target_slide/) | Jeśli HyperlinkEx wskazuje konkretny slajd, zwraca ten slajd.<br/>            Jeśli właściwość nie będzie równa None, to właściwość ExternalUrl będzie równa None.<br/>            Tylko do odczytu [`ISlide`](/slides/python-net/pl/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/pl/aspose.slides/ihyperlink/target_frame/) | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla docelowego<br/>            hiperłącza nadrzędnego, gdy istnieje.<br/>            Odczyt/zapis **str**. |
| [`tooltip`](/slides/python-net/pl/aspose.slides/ihyperlink/tooltip/) | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika<br/>            jako powiązany z nadrzędnym hiperłączem.<br/>            Odczyt/zapis **str**. |
| [`history`](/slides/python-net/pl/aspose.slides/ihyperlink/history/) | Określa, czy docelowy hiperlink nadrzędny ma zostać dodany<br/>            do listy przeglądanych hiperłączy po wywołaniu.<br/>            Odczyt/zapis **bool**. |
| [`highlight_click`](/slides/python-net/pl/aspose.slides/ihyperlink/highlight_click/) | Określa, czy hiperłącze ma być podświetlane po kliknięciu.<br/>            Odczyt/zapis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/pl/aspose.slides/ihyperlink/stop_sound_on_click/) | Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza.<br/>            Odczyt/zapis **bool**. |
| [`sound`](/slides/python-net/pl/aspose.slides/ihyperlink/sound/) | Reprezentuje odtwarzany dźwięk hiperłącza.<br/>            Odczyt/zapis [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/pl/aspose.slides/ihyperlink/color_source/) | Reprezentuje źródło koloru hiperłącza – style lub format fragmentu.<br/>            Odczyt/zapis [`HyperlinkColorSource`](/slides/python-net/pl/aspose.slides/hyperlinkcolorsource). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/pl/aspose.slides/ihyperlink/equals/#ihyperlink) | Określa, czy dwa wystąpienia Hyperlink są równe. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)