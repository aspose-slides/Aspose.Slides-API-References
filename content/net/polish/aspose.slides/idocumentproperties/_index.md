---
title: IDocumentProperties
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 5710
url: /pl/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfejs

Reprezentuje właściwości prezentacji.

```csharp
public interface IDocumentProperties
```

## Właściwości

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Zwraca wersję aplikacji. Tylko do odczytu String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Zwraca lub ustawia autora prezentacji. Odczyt/zapis String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Zwraca lub ustawia własność company. Odczyt/zapis String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Zwraca lub ustawia status treści prezentacji. Odczyt/zapis String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Zwraca lub ustawia typ treści prezentacji. Odczyt/zapis String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Zwraca liczbę własności niestandardowych rzeczywiście zawartych w kolekcji. Tylko do odczytu Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Zwraca datę utworzenia prezentacji. Wartości są w UTC. Odczyt/zapis DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Wskazuje grupowanie części dokumentu oraz liczbę części w każdej grupie. Tylko do odczytu IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Określa liczbę ukrytych slajdów w dokumencie prezentacji. Tylko do odczytu Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Zwraca lub ustawia własność HyperlinkBase dokumentu. Odczyt/zapis String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Określa, że jeden lub więcej hiperłączy w tej części zostały zaktualizowane wyłącznie w tej części przez producenta. Następny producent otwierający ten dokument powinien zaktualizować relacje hiperłączy przy użyciu nowych hiperłączy określonych w tej części. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Zwraca lub ustawia własność niestandardową powiązaną z określoną nazwą. Odczyt/zapis Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Zwraca datę ostatniego wydruku prezentacji. Odczyt/zapis DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Zwraca lub ustawia nazwę ostatniej osoby, która zmodyfikowała prezentację. Odczyt/zapis String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Zwraca datę ostatniej modyfikacji prezentacji. Wartości są w UTC. Tylko do odczytu w przypadku Presentation.DocumentProperties (ponieważ jest aktualizowane wewnętrznie podczas procesu zapisywania obiektu IPresentation). Może być zmienione poprzez instancję DocumentProperties zwróconą metodą [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Proszę zobaczyć przykład w podsumowaniu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Wskazuje, czy hiperłącza w dokumencie są aktualne. Ustaw ten element na **true**, aby wskazać, że hiperłącza są zaktualizowane. Ustaw ten element na **false**, aby wskazać, że hiperłącza są nieaktualne. Odczyt/zapis Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Zwraca lub ustawia własność manager. Odczyt/zapis String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Określa łączną liczbę klipów dźwiękowych lub wideo znajdujących się w dokumencie. Tylko do odczytu Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Określa liczbę slajdów w prezentacji zawierających notatki. Tylko do odczytu Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Określa łączną liczbę paragrafów znalezionych w dokumencie, jeśli dotyczy. Tylko do odczytu Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Zwraca lub ustawia zamierzony format prezentacji. Odczyt/zapis String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Zwraca lub ustawia numer rewizji prezentacji. Odczyt/zapis Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Wskazuje tryb wyświetlania miniaturki dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniaturki dokumentu do wyświetlacza. Ustaw ten element na **false**, aby włączyć przycinanie miniaturki dokumentu, aby wyświetlała tylko sekcje pasujące do wyświetlacza. Odczyt/zapis Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Określa, czy prezentacja jest współdzielona między wieloma osobami. Odczyt/zapis Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Określa łączną liczbę slajdów w dokumencie prezentacji. Tylko do odczytu Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Zwraca lub ustawia temat prezentacji. Odczyt/zapis String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Określa tytuł każdej części dokumentu. Te części nie są rzeczywistymi częściami dokumentu, lecz koncepcyjnymi reprezentacjami sekcji dokumentu. Tylko do odczytu string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Łączny czas edycji prezentacji. Odczyt/zapis TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Określa łączną liczbę słów zawartych w dokumencie. Tylko do odczytu Int32. |

## Metody

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Usuwa i ustawia wartości domyślne dla wszystkich wbudowanych właściwości. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Usuwa wszystkie własności niestandardowe. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Sprawdza obecność własności niestandardowej o określonej nazwie. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Zwraca nazwę własności niestandardowej pod wskazanym indeksem. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Pobiera nazwany boolowski wartość z własności niestandardowych. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Pobiera nazwany DateTime z własności niestandardowych. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Pobiera nazwany double z własności niestandardowych. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Pobiera nazwany float z własności niestandardowych. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Pobiera nazwany integer z własności niestandardowych. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Pobiera nazwany string z własności niestandardowych. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Pobiera tablicę etykiet wrażliwości z własności niestandardowych dokumentu (Metadane Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Usuwa własność niestandardową powiązaną z określoną nazwą. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ustawia niestandardową własność boolowską o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ustawia niestandardową własność DateTime o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ustawia niestandardową własność double o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ustawia niestandardową własność float o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ustawia niestandardową własność integer o podanej nazwie. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ustawia niestandardową własność string o podanej nazwie. |

### Zobacz także

* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->