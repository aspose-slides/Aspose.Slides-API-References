---
title: DocumentProperties
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje właściwości prezentacji.
type: docs
weight: 2790
url: /pl/aspose.slides/documentproperties/
---
## DocumentProperties klasa

Reprezentuje właściwości prezentacji.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktory

| Nazwa | Opis |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inicjalizuje nową instancję klasy [`DocumentProperties`](../documentproperties). |

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Zwraca lub ustawia szablon aplikacji. Odczyt/zapis String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Zwraca wersję aplikacji. Tylko odczyt String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Zwraca lub ustawia autora prezentacji. Odczyt/zapis String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Zwraca lub ustawia kategorię prezentacji. Odczyt/zapis String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Zwraca lub ustawia komentarze prezentacji. Odczyt/zapis String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Zwraca lub ustawia właściwość firmy. Odczyt/zapis String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Zwraca lub ustawia status zawartości prezentacji. Odczyt/zapis String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Zwraca lub ustawia typ zawartości prezentacji. Odczyt/zapis String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Zwraca liczbę niestandardowych właściwości faktycznie zawartych w kolekcji. Tylko odczyt Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Zwraca datę utworzenia prezentacji. Wartości są w UTC. Odczyt/zapis DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Wskazuje grupowanie części dokumentu i liczbę części w każdej grupie. Tylko odczyt IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Zwraca liczbę ukrytych slajdów w dokumencie prezentacji. Tylko odczyt Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Zwraca lub ustawia właściwość dokumentu HyperlinkBase. Odczyt/zapis String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Określa, że jeden lub więcej odnośników w tej części zostały zaktualizowane wyłącznie w tej części przez producenta. Następny producent otwierający ten dokument zaktualizuje relacje odnośników nowymi odnośnikami określonymi w tej części. Odczyt/zapis Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Zwraca lub ustawia niestandardową właściwość powiązaną z określoną nazwą. Odczyt/zapis Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Zwraca lub ustawia słowa kluczowe prezentacji. Odczyt/zapis String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Zwraca datę ostatniego drukowania prezentacji. Odczyt/zapis DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Zwraca lub ustawia nazwę ostatniej osoby, która modyfikowała prezentację. Odczyt/zapis String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Zwraca datę ostatniej modyfikacji prezentacji. Wartości są w UTC. Tylko odczyt w przypadku Presentation.DocumentProperties (ponieważ będzie aktualizowane wewnętrznie podczas procesu zapisywania obiektu IPresentation). Można zmienić za pomocą instancji DocumentProperties zwracanej przez metodę [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zobacz przykład w podsumowaniu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Wskazuje, czy odnośniki w dokumencie są aktualne. Ustaw ten element na **true**, aby zaznaczyć, że odnośniki są zaktualizowane. Ustaw na **false**, aby zaznaczyć, że odnośniki są nieaktualne. Odczyt/zapis Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Zwraca lub ustawia właściwość menedżera. Odczyt/zapis String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Zwraca łączną liczbę klipów dźwiękowych lub wideo znajdujących się w dokumencie. Tylko odczyt Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Zwraca lub ustawia nazwę aplikacji. Odczyt/zapis String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Zwraca liczbę slajdów w prezentacji zawierających notatki. Tylko odczyt Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Zwraca łączną liczbę akapitów w dokumencie, jeśli dotyczy. Tylko odczyt Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Zwraca lub ustawia zamierzony format prezentacji. Odczyt/zapis String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Zwraca lub ustawia numer rewizji prezentacji. Odczyt/zapis Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Określa tryb wyświetlania miniatury dokumentu. Ustaw ten element na **true**, aby włączyć skalowanie miniatury dokumentu do wyświetlacza. Ustaw na **false**, aby włączyć przycinanie miniatury dokumentu tak, aby wyświetlała tylko sekcje pasujące do wyświetlacza. Odczyt/zapis Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Określa, czy prezentacja jest udostępniana wielu osobom. Odczyt/zapis Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Zwraca łączną liczbę slajdów w dokumencie prezentacji. Tylko odczyt Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Zwraca lub ustawia temat prezentacji. Odczyt/zapis String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Zwraca lub ustawia tytuł prezentacji. Odczyt/zapis String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Określa tytuł każdej części dokumentu. Te części nie są rzeczywistymi częściami dokumentu, lecz konceptualnymi reprezentacjami sekcji dokumentu. Tylko odczyt string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Łączny czas edycji prezentacji. Odczyt/zapis TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Zwraca łączną liczbę słów zawartych w dokumencie. Tylko odczyt Int32. |

## Metody

| Nazwa | Opis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Czyści i ustawia domyślne wartości dla wszystkich wbudowanych właściwości. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Usuwa wszystkie niestandardowe właściwości. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klonuje bieżący obiekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klonuje bieżący obiekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Sprawdza obecność niestandardowej właściwości o określonej nazwie. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Zwraca nazwę niestandardowej właściwości pod podanym indeksem. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Pobiera nazwany wartość bool z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Pobiera nazwany wartość DateTime z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Pobiera nazwany wartość double z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Pobiera nazwany wartość float z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Pobiera nazwany wartość integer z niestandardowych właściwości. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Pobiera nazwany wartość string z niestandardowych właściwości. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Pobiera tablicę etykiet wrażliwości z niestandardowych właściwości dokumentu (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Usuwa niestandardową właściwość powiązaną z określoną nazwą. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ustawia nazwany boolean jako niestandardową właściwość. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ustawia nazwany DateTime jako niestandardową właściwość. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ustawia nazwany double jako niestandardową właściwość. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ustawia nazwany float jako niestandardową właściwość. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ustawia nazwany integer jako niestandardową właściwość. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ustawia nazwany string jako niestandardową właściwość. |

### Przykłady

Poniższy przykład pokazuje, jak uzyskać dostęp do wbudowanych właściwości prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation reprezentującej prezentację
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Utwórz referencję do obiektu IDocumentProperties powiązanego z prezentacją
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Wyświetl wbudowane właściwości
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Poniższy przykład pokazuje, jak zmodyfikować wbudowane właściwości prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation reprezentującej prezentację
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Utwórz referencję do obiektu IDocumentProperties powiązanego z prezentacją
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Ustaw wbudowane właściwości
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Zapisz prezentację do pliku
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IDocumentProperties](../idocumentproperties)
* interfejs [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->