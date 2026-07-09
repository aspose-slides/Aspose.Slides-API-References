---
title: IPresentation
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Dokument prezentacji
type: docs
weight: 6750
url: /pl/aspose.slides/ipresentation/
---
## IPresentation interfejs

Dokument prezentacji

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Zwraca wszystkie niestandardowe części danych w prezentacji. Tylko do odczytu [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Zwraca interfejs IDisposable. Tylko do odczytu IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Umożliwia uzyskanie bazowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Zwraca kolekcję autorów komentarzy. Tylko do odczytu [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Zwraca lub ustawia datę i godzinę, która zastąpi treść pól datetime. Domyślnie czas utworzenia tego obiektu Presentation. Do odczytu i zapisu DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Zwraca niestandardowe dane prezentacji. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Zwraca domyślny styl tekstu dla kształtów. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Zwraca kolekcję podpisów używanych do podpisywania prezentacji. Tylko do odczytu [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. Tylko do odczytu [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Reprezentuje numer pierwszego slajdu w prezentacji. Do odczytu i zapisu Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Zwraca menedżera czcionek. Tylko do odczytu [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Zwraca menedżera nagłówka i stopki prezentacji. Tylko do odczytu [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Zapewnia łatwy dostęp do wszystkich hiperłączy znajdujących się we wszystkich slajdach prezentacji (z wyłączeniem slajdów master, układu, notatek). Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji. Tylko do odczytu [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Zwraca menedżera mastera materiałów rozdawniczych. Tylko do odczytu [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Zwraca menedżera mastera notatek. Tylko do odczytu [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Zwraca listę wszystkich slajdów master zdefiniowanych w prezentacji. Tylko do odczytu [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Zwraca motyw mastera prezentacji. Tylko do odczytu [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Zwraca obiekt rozmiaru slajdu notatek. Tylko do odczytu [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Zwraca menedżera uprawnień dla tej prezentacji. Tylko do odczytu [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji. Tylko do odczytu [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. Tylko do odczytu [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji. Tylko do odczytu [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Zwraca obiekt rozmiaru slajdu. Tylko do odczytu [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Zwraca informacje o formacie, z którego została wczytana prezentacja. Tylko do odczytu [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Zwraca projekt VBA z makrami prezentacji. Do odczytu i zapisu [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Zwraca właściwości widoku prezentacji. Tylko do odczytu [`IViewProperties`](../iviewproperties). |

## Metody

| Nazwa | Opis |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Zwraca obiekty miniatury obrazu dla wszystkich slajdów prezentacji. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Zwraca obiekty miniatury bitmapy dla określonych slajdów prezentacji. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Zwraca obiekty miniatury obrazu dla wszystkich slajdów prezentacji o określonym rozmiarze. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Zwraca obiekty miniatury obrazu dla wszystkich slajdów prezentacji z niestandardowym skalowaniem. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Zwraca obiekty miniatury obrazu dla określonych slajdów prezentacji o określonym rozmiarze. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Zwraca obiekty miniatury obrazu dla określonych slajdów prezentacji z niestandardowym skalowaniem. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Zwraca obiekt Slide, MasterSlide lub LayoutSlide na podstawie Id. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Podświetla wszystkie dopasowania wyrażenia regularnego podanym kolorem. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Podświetla wszystkie dopasowania tekstu przykładowego podanym kolorem. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Podświetla wszystkie dopasowania tekstu przykładowego podanym kolorem. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Łączy fragmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach we wszystkich slajdach. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Zastępuje wszystkie dopasowania wyrażenia regularnego podanym łańcuchem znaków. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Zastępuje wszystkie wystąpienia podanego tekstu innym podanym tekstem. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie oraz z dodatkowymi opcjami. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie. |

### Zobacz także

* interfejs [IPresentationComponent](../ipresentationcomponent)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* biblioteka [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->