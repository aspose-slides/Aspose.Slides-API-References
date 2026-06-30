---
title: Hyperlink
second_title: Aspose.Sildes dla .NET - dokumentacja API
description: Reprezentuje hiperlink.
type: docs
weight: 5100
url: /pl/aspose.slides/hyperlink/
---
## Hyperlink klasa

Reprezentuje hiperlink.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Tworzy przykład hiperlinku, który wskazuje na konkretny slajd. Uwaga: utworzony hiperlink powinien być przypisany do jakiegoś obiektu z tej samej prezentacji, w przeciwnym razie odnośnik zostanie zapisany jako NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Tworzy przykład hiperlinku. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Tworzy przykład hiperlinku przy użyciu innego hiperlinku jako źródła, nadpisując właściwości wtórne. |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Zwraca hiperlink, który kończy prezentację. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Zwraca hiperlink do pierwszego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Zwraca hiperlink do ostatniego slajdu prezentacji. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Zwraca hiperlink do ostatnio wyświetlanego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Zwraca specjalny hiperlink „odtwórz plik multimedialny”. Używany w AudioFrame i VideoFrame. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Zwraca hiperlink do następnego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Zwraca specjalny hiperlink „nic nie rób”. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Zwraca hiperlink do poprzedniego slajdu. Tylko do odczytu [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Zwraca typ akcji hiperlinku. Tylko do odczytu [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie bazowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Reprezentuje źródło koloru hiperlinku – style lub format części. Odczyt/zapis [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Określa zewnętrzny URL. Tylko do odczytu String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Reprezentuje hiperlink ustawiony dla tej części bez uwzględniania rzeczywistej treści części. PowerPoint zachowuje się w szczególny sposób względem odnośników i ich odpowiadającego tekstu w części. Umożliwia tworzenie tekstu hiperlinku w postaci prawidłowego URL, różnego od rzeczywistego adresu odnośnika. W takim przypadku, gdy przeglądasz odnośnik w oknie edycji, zostanie on zmieniony, aby pasował do tekstu części. To właściwość reprezentuje pierwotną wartość hiperlinku. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Określa, czy hiperlink ma być podświetlany po kliknięciu. Odczyt/zapis Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Określa, czy cel nadrzędnego hiperlinku ma być dodany do listy oglądanych hiperlinków po jego wywołaniu. Odczyt/zapis Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Reprezentuje dźwięk odtwarzany przez hiperlink. Odczyt/zapis [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Określa, czy dźwięk ma zostać zatrzymany po kliknięciu hiperlinku. Odczyt/zapis Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Zwraca ramkę wewnątrz nadrzędnego zestawu ramek HTML dla celu nadrzędnego hiperlinku, jeśli istnieje. Odczyt/zapis String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Jeśli hiperlink odnosi się do konkretnego slajdu, zwraca ten slajd. Tylko do odczytu [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Zwraca ciąg znaków, który może być wyświetlany w interfejsie użytkownika jako powiązany z nadrzędnym hiperlinkiem. Odczyt/zapis String. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Określa, czy dwie instancje Hyperlink są równe. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Określa, czy dwie instancje Hyperlink są równe. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Służy jako funkcja skrótu dla określonego typu, odpowiednia do użycia w algorytmach haszujących i strukturach danych, takich jak tablica mieszająca. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testuje dwa hiperlinki pod kątem równości. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testuje dwa hiperlinki pod kątem nierówności. |

### Zobacz też

* klasa [PVIObject](../pviobject)
* interfejs [IHyperlink](../ihyperlink)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->