---
title: Hyperlink
second_title: Aspose.Sildes dla .NET – referencja API
description: Reprezentuje hiperłącze.
type: docs
weight: 5120
url: /pl/aspose.slides/hyperlink/
---
## Hyperlink klasa

Reprezentuje hiperłącze.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Tworzy instancję hiperłącza, które wskazuje na określony slajd. Uwaga: utworzone hiperłącze powinno być przypisane do jakiegoś obiektu z tej samej prezentacji, w przeciwnym razie link zostanie zapisany jako NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Tworzy instancję hiperłącza. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Tworzy instancję hiperłącza przy użyciu innego hiperłącza jako źródła, nadpisując właściwości dodatkowe. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Zwraca hiperłącze, które kończy pokaz. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Zwraca hiperłącze do pierwszego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Zwraca hiperłącze do ostatniego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Zwraca hiperłącze do ostatnio oglądanego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Zwraca specjalne hiperłącze "play mediafile". Używane w AudioFrame i VideoFrame. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Zwraca hiperłącze do następnego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Zwraca specjalne hiperłącze "do nothing". Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Zwraca hiperłącze do poprzedniego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Zwraca typ akcji hiperłącza. Tylko do odczytu [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie bazowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Reprezentuje źródło koloru hiperłącza – style lub format części. Odczyt/zapis [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Określa zewnętrzny URL. Tylko do odczytu String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Reprezentuje hiperłącze ustawione dla tej części bez względu na rzeczywistą treść części. PowerPoint zachowuje się specyficznie dla linków i ich odpowiadającego tekstu w części. Umożliwia tworzenie tekstu dla hiperłącza w formie prawidłowego URL, różnego od rzeczywistego adresu linku. W takim przypadku, gdy wyświetlasz link w oknie edycji, zostanie on zmieniony, aby pasował do tekstu części. Ta właściwość reprezentuje pierwotną wartość hiperłącza. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Określa, czy hiperłącze powinno być podświetlane po kliknięciu. Odczyt/zapis Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Określa, czy cel nadrzędnego hiperłącza ma być dodany do listy oglądanych hiperłączy po wywołaniu. Odczyt/zapis Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Reprezentuje odtwarzany dźwięk hiperłącza. Odczyt/zapis [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Określa, czy dźwięk powinien być zatrzymany po kliknięciu hiperłącza. Odczyt/zapis Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Zwraca ramkę w ramach nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperłącza, jeśli istnieje. Odczyt/zapis String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Jeśli Hyperlink wskazuje konkretny slajd, zwraca ten slajd. Tylko do odczytu [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperłączem. Odczyt/zapis String. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Określa, czy dwie instancje Hyperlink są równe. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Określa, czy dwie instancje Hyperlink są równe. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych, takich jak tablica hash. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testuje dwa hiperłącza pod kątem równości. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testuje dwa hiperłącza pod kątem nierówności. |

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IHyperlink](../ihyperlink)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->