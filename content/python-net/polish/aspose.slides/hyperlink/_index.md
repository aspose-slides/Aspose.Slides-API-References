---
title: Hyperlink class
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/hyperlink/
---
## Klasa Hyperlink

Reprezentuje hiperłącze.

**Dziedziczenie:**[`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)

Typ Hyperlink udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/pl/aspose.slides/hyperlink/__init__/#str) | Tworzy instancję hiperłącza. |
| [`__init__(self, slide)`](/slides/python-net/pl/aspose.slides/hyperlink/__init__/#islide) | Tworzy instancję hiperłącza, które wskazuje konkretny slajd.<br/>            Uwaga: utworzone hiperłącze powinno być przypisane do jakiegoś obiektu z tej samej prezentacji, w przeciwnym razie link zostanie zapisany jako NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/pl/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Tworzy instancję hiperłącza przy użyciu innego hiperłącza jako źródła, nadpisując właściwości pomocnicze. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`no_action`](/slides/python-net/pl/aspose.slides/hyperlink/no_action/) | Zwraca specjalne hiperłącze „nic nie rób”.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/pl/aspose.slides/hyperlink/media/) | Zwraca specjalne hiperłącze „odtwarzaj plik multimedialny”. Używane w AudioFrame i VideoFrame.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/pl/aspose.slides/hyperlink/next_slide/) | Zwraca hiperłącze do następnego slajdu.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/pl/aspose.slides/hyperlink/previous_slide/) | Zwraca hiperłącze do poprzedniego slajdu.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/pl/aspose.slides/hyperlink/first_slide/) | Zwraca hiperłącze do pierwszego slajdu prezentacji.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/pl/aspose.slides/hyperlink/last_slide/) | Zwraca hiperłącze do ostatniego slajdu prezentacji.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/pl/aspose.slides/hyperlink/last_vieved_slide/) | Zwraca hiperłącze do ostatniego oglądanego slajdu.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/pl/aspose.slides/hyperlink/end_show/) | Zwraca hiperłącze, które kończy pokaz.<br/>            Tylko do odczytu [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/pl/aspose.slides/hyperlink/action_type/) | Zwraca typ akcji Hyperlink.<br/>            Tylko do odczytu [`HyperlinkActionType`](/slides/python-net/pl/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/pl/aspose.slides/hyperlink/external_url/) | Określa zewnętrzny URL.<br/>            Tylko do odczytu **str**. |
| [`target_slide`](/slides/python-net/pl/aspose.slides/hyperlink/target_slide/) | Jeśli Hyperlink wskazuje konkretny slajd, zwraca ten slajd.<br/>            Tylko do odczytu [`ISlide`](/slides/python-net/pl/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/pl/aspose.slides/hyperlink/external_url_original/) | Reprezentuje hiperłącze ustawione dla tej części bez względu na rzeczywistą zawartość części.<br/>            <br/>            PowerPoint zachowuje się szczególnie dla linków i ich odpowiadającego tekstu w części. Umożliwia tworzenie tekstu dla hiperłącza w formie prawidłowego URL, różnego od rzeczywistego adresu linku. W takim przypadku, gdy przeglądasz link w oknie edycji, zostanie on zmieniony, aby pasował do tekstu części. Ta właściwość reprezentuje pierwotną wartość hiperłącza. |
| [`target_frame`](/slides/python-net/pl/aspose.slides/hyperlink/target_frame/) | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla docelowego elementu nadrzędnego hiperłącza, jeśli istnieje.<br/>            Odczyt/zapis **str**. |
| [`tooltip`](/slides/python-net/pl/aspose.slides/hyperlink/tooltip/) | Zwraca ciąg znaków, który może być wyświetlony w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem.<br/>            Odczyt/zapis **str**. |
| [`history`](/slides/python-net/pl/aspose.slides/hyperlink/history/) | Określa, czy docelowy element nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po jego wywołaniu.<br/>            Odczyt/zapis **bool**. |
| [`highlight_click`](/slides/python-net/pl/aspose.slides/hyperlink/highlight_click/) | Określa, czy hiperłącze ma być podświetlane po kliknięciu.<br/>            Odczyt/zapis **bool**. |
| [`stop_sound_on_click`](/slides/python-net/pl/aspose.slides/hyperlink/stop_sound_on_click/) | Określa, czy dźwięk ma być zatrzymany po kliknięciu hiperłącza.<br/>            Odczyt/zapis **bool**. |
| [`sound`](/slides/python-net/pl/aspose.slides/hyperlink/sound/) | Reprezentuje odtwarzany dźwięk hiperłącza.<br/>            Odczyt/zapis [`IAudio`](/slides/python-net/pl/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/pl/aspose.slides/hyperlink/color_source/) | Reprezentuje źródło koloru hiperłącza – style lub format części.<br/>            Odczyt/zapis [`HyperlinkColorSource`](/slides/python-net/pl/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/pl/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/hyperlink/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/pl/aspose.slides/hyperlink/equals/#ihyperlink) | Określa, czy dwie instancje Hyperlink są równe. |


### Zobacz także
* klasa [`Hyperlink`](/slides/python-net/pl/aspose.slides/hyperlink)
* klasa [`PVIObject`](/slides/python-net/pl/aspose.slides/pviobject)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)