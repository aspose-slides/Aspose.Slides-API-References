---
title: Hyperlink
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje odnośnik.
type: docs
weight: 5140
url: /pl/aspose.slides/hyperlink/
---
## Klasa Hyperlink

Reprezentuje odnośnik.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktorzy

| Name | Description |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Tworzy instancję odnośnika, który wskazuje konkretny slajd. Uwaga: utworzony odnośnik powinien być przypisany do jakiegoś obiektu z tej samej prezentacji, w przeciwnym razie odnośnik zostanie zapisany jako NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Tworzy instancję odnośnika. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Tworzy instancję odnośnika przy użyciu innego odnośnika jako źródła, nadpisując właściwości dodatkowe. |

## Właściwości

| Name | Description |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Zwraca odnośnik, który kończy pokaz. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Zwraca odnośnik do pierwszego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Zwraca odnośnik do ostatniego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Zwraca odnośnik do ostatnio wyświetlanego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Zwraca specjalny odnośnik "play mediafile". Używany w AudioFrame i VideoFrame. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Zwraca odnośnik do następnego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Zwraca specjalny odnośnik "do nothing". Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Zwraca odnośnik do poprzedniego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Zwraca typ akcji odnośnika. Tylko do odczytu [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Reprezentuje źródło koloru odnośnika – style lub format części. Odczyt/zapis [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Określa zewnętrzny URL. Tylko do odczytu String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Reprezentuje odnośnik ustawiony dla tej części niezależnie od rzeczywistej zawartości części. PowerPoint zachowuje się specyficznie względem odnośników i odpowiadającego im tekstu w części. Umożliwia tworzenie tekstu odnośnika w formie prawidłowego URL, różnego od rzeczywistego adresu odnośnika. W takim przypadku, gdy przeglądasz odnośnik w oknie edycji, zostanie on zmieniony tak, aby pasował do tekstu części. To właściwość reprezentuje pierwotną wartość odnośnika. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Określa, czy odnośnik powinien być podświetlany po kliknięciu. Odczyt/zapis Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Określa, czy cel nadrzędnego odnośnika ma być dodany do listy przeglądanych odnośników po jego wywołaniu. Odczyt/zapis Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Reprezentuje odtwarzany dźwięk odnośnika. Odczyt/zapis [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Określa, czy dźwięk powinien być zatrzymany po kliknięciu odnośnika. Odczyt/zapis Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego odnośnika, jeśli istnieje. Odczyt/zapis String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Jeśli odnośnik wskazuje konkretny slajd, zwraca ten slajd. Tylko do odczytu [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym odnośnikiem. Odczyt/zapis String. |

## Metody

| Name | Description |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Określa, czy dwie instancje Hyperlink są równe. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Określa, czy dwie instancje Hyperlink są równe. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Służy jako funkcja mieszająca dla danego typu, odpowiednia do użycia w algorytmach mieszających i strukturach danych, takich jak tablica mieszająca. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testuje dwa odnośniki pod kątem równości. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testuje dwa odnośniki pod kątem nierówności. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IHyperlink](../ihyperlink)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->