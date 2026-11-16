---
title: IDocumentProperties
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 5730
url: /pl/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfejs

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Zwraca wersję aplikacji. Tylko do odczytu String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Zwraca lub ustawia autora prezentacji. Odczyt/zapis String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Zwraca lub ustawia właściwość firmy. Odczyt/zapis String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Zwraca liczbę własnych właściwości faktycznie zawartych w kolekcji. Tylko do odczytu Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Zwraca datę utworzenia prezentacji. Wartości w UTC. Odczyt/zapis DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Wskazuje grupowanie części dokumentu oraz liczbę części w każdej grupie. Tylko do odczytu IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Określa liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Zwraca lub ustawia właściwość dokumentu HyperlinkBase. Odczyt/zapis String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Określa, że jeden lub więcej odnośników w tej części zostały zaktualizowane wyłącznie w tej części przez producenta. Następny producent otwierający ten dokument powinien zaktualizować relacje odnośników nowymi odnośnikami określonymi w tej części. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Zwraca lub ustawia własną właściwość powiązaną z określoną nazwą. Odczyt/zapis Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Zwraca datę ostatniego wydruku prezentacji. Odczyt/zapis DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Zwraca lub ustawia imię i nazwisko ostatniej osoby, która zmodyfikowała prezentację. Odczyt/zapis String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Zwraca datę ostatniej modyfikacji prezentacji. Wartości w UTC.P. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisywania obiektu IPresentation). Może być zmieniona za pośrednictwem instancji DocumentProperties zwracanej przez metodę [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Proszę zobaczyć przykład w podsumowaniu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Wskazuje, czy odnośniki w dokumencie są aktualne. Ustaw ten element na **true**, aby wskazać, że odnośniki są zaktualizowane. Ustaw ten element na **false**, aby wskazać, że odnośniki są nieaktualne. Odczyt/zapis Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Zwraca lub ustawia właściwość manager. Odczyt/zapis String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Określa łączną liczbę klipów dźwiękowych lub wideo znajdujących się w dokumencie. Tylko do odczytu Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Określa liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Określa łączną liczbę akapitów znalezionych w dokumencie, jeśli ma to zastosowanie. Tylko do odczytu Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Zwraca lub ustawia zamierzony format prezentacji. Odczyt/zapis String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Zwraca lub ustawia numer wersji prezentacji. Odczyt/zapis Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Wskazuje tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniatury dokumentu, aby pokazać tylko sekcje pasujące do wyświetlacza. Odczyt/zapis Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Określa, czy prezentacja jest współdzielona między wieloma osobami. Odczyt/zapis Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Określa łączną liczbę slajdów w dokumencie prezentacji. Tylko do odczytu Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Zwraca lub ustawia temat prezentacji. Odczyt/zapis String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Określa tytuł każdej części dokumentu. Części te nie są rzeczywistymi częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. Tylko do odczytu string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Łączny czas edycji prezentacji. Odczyt/zapis TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Określa łączną liczbę słów zawartych w dokumencie. Tylko do odczytu Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Czyści i ustawia wartości domyślne dla wszystkich wbudowanych właściwości. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Usuwa wszystkie własne właściwości. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Sprawdza obecność własnej właściwości o określonej nazwie. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Zwraca nazwę własnej właściwości pod określonym indeksem. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Pobiera nazwany wartość boolowską z własnych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Pobiera nazwany wartość DateTime z własnych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Pobiera nazwany wartość double z własnych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Pobiera nazwany wartość float z własnych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Pobiera nazwany wartość całkowitą z własnych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Pobiera nazwany wartość string z własnych właściwości. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Pobiera tablicę etykiet wrażliwości z własnych właściwości dokumentu (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Usuwa własną właściwość powiązaną z określoną nazwą. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ustawia własną właściwość boolowską o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ustawia własną właściwość DateTime o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ustawia własną właściwość double o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ustawia własną właściwość float o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ustawia własną właściwość całkowitą o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ustawia własną właściwość string o podanej nazwie. |

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->