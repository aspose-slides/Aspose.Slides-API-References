---
title: IDocumentProperties
second_title: Aspose.Sildes dla .NET – referencja API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 5690
url: /pl/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfejs

Reprezentuje właściwości prezentacji.

```csharp
public interface IDocumentProperties
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Zwraca lub ustawia szablon aplikacji. odczyt/zapis String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Zwraca wersję aplikacji. tylko odczyt String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Zwraca lub ustawia autora prezentacji. odczyt/zapis String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Zwraca lub ustawia kategorię prezentacji. odczyt/zapis String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Zwraca lub ustawia komentarze prezentacji. odczyt/zapis String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Zwraca lub ustawia właściwość firmy. odczyt/zapis String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Zwraca lub ustawia status treści prezentacji. odczyt/zapis String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Zwraca lub ustawia typ treści prezentacji. odczyt/zapis String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Zwraca liczbę niestandardowych właściwości rzeczywiście zawartych w kolekcji. tylko odczyt Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Zwraca datę utworzenia prezentacji. Wartości są w UTC. odczyt/zapis DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie. tylko odczyt IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Określa liczbę ukrytych slajdów w dokumencie prezentacji. tylko odczyt Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Zwraca lub ustawia właściwość dokumentu HyperlinkBase. odczyt/zapis String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Określa, że jeden lub więcej hiperłączy w tej części zostało zaktualizowanych wyłącznie w tej części przez producenta. Następny producent otwierający ten dokument powinien zaktualizować relacje hiperłączy za pomocą nowych hiperłącz określonych w tej części. odczyt/zapis Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Zwraca lub ustawia niestandardową właściwość powiązaną z określoną nazwą. odczyt/zapis Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Zwraca słowa kluczowe prezentacji. odczyt/zapis String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Zwraca datę ostatniego drukowania prezentacji. odczyt/zapis DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Zwraca nazwę ostatniej osoby, która zmodyfikowała prezentację. odczyt/zapis String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Zwraca datę ostatniej modyfikacji prezentacji. Wartości są w UTC. Tylko odczyt w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisywania obiektu IPresentation). Może być zmienione poprzez instancję DocumentProperties zwracaną przez metodę [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zobacz przykład w podsumowaniu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Wskazuje, czy hiperłącza w dokumentie są aktualne. Ustaw ten element na **true**, aby wskazać, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby wskazać, że hiperłącza są nieaktualne. odczyt/zapis Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Zwraca lub ustawia właściwość menedżera. odczyt/zapis String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Określa łączną liczbę klipów dźwiękowych lub wideo obecnych w dokumencie. tylko odczyt Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Zwraca lub ustawia nazwę aplikacji. odczyt/zapis String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Określa liczbę slajdów w prezentacji zawierających notatki. tylko odczyt Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Określa łączną liczbę akapitów znalezionych w dokumencie, jeśli ma zastosowanie. tylko odczyt Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Zwraca lub ustawia zamierzony format prezentacji. odczyt/zapis String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Zwraca lub ustawia numer wersji prezentacji. odczyt/zapis Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby pokazać tylko sekcje pasujące do wyświetlacza. odczyt/zapis Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Określa, czy prezentacja jest współdzielona między wieloma osobami. odczyt/zapis Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Określa całkowitą liczbę slajdów w dokumencie prezentacji. tylko odczyt Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Zwraca lub ustawia temat prezentacji. odczyt/zapis String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Zwraca lub ustawia tytuł prezentacji. odczyt/zapis String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Zwraca tytuł każdej części dokumentu. Te części nie są częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. tylko odczyt string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Całkowity czas edycji prezentacji. odczyt/zapis TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Określa łączną liczbę słów zawartych w dokumencie. tylko odczyt Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Czyści i ustawia domyślne wartości dla wszystkich wbudowanych właściwości. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Usuwa wszystkie niestandardowe właściwości. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Sprawdza obecność niestandardowej właściwości o określonej nazwie. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Zwraca nazwę niestandardowej właściwości pod wskazanym indeksem. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Pobiera nazwany wartość typu Boolean z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Pobiera nazwany wartość typu DateTime z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Pobiera nazwany wartość typu double z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Pobiera nazwany wartość typu float z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Pobiera nazwany wartość całkowitą z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Pobiera nazwany wartość typu string z niestandardowych właściwości. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Pobiera tablicę etykiet wrażliwości z niestandardowych właściwości dokumentu (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Usuwa niestandardową właściwość powiązaną z określoną nazwą. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ustawia nazwany niestandardowy Boolean. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ustawia nazwany niestandardowy DateTime. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ustawia nazwany niestandardowy double. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ustawia nazwany niestandardowy float. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ustawia nazwany niestandardowy integer. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ustawia nazwany niestandardowy string. |

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->