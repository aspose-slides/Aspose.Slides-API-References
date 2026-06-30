---
title: Presentation
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Reprezentuje prezentację Microsoft PowerPoint.
type: docs
weight: 9570
url: /pl/aspose.slides/presentation/
---
## Klasa Presentation

Reprezentuje prezentację Microsoft PowerPoint.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktory

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | Ten konstruktor tworzy nową prezentację od podstaw. Utworzona prezentacja ma jeden pusty slajd. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Ten konstruktor tworzy nową prezentację od podstaw. Utworzona prezentacja ma jeden pusty slajd. |
| [Presentation](presentation#constructor_2)(Stream) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [Presentation](presentation#constructor_4)(string) | Ten konstruktor pobiera ścieżkę do pliku źródłowego, z którego odczytywana jest zawartość prezentacji. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Ten konstruktor pobiera ścieżkę do pliku źródłowego, z którego odczytywana jest zawartość prezentacji. |

## Właściwości

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Zwraca wszystkie części danych niestandardowych w prezentacji. Tylko do odczytu [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji. Tylko do odczytu [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Zwraca kolekcję autorów komentarzy. Tylko do odczytu [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól daty i czasu. Domyślnie jest to czas utworzenia tego obiektu Presentation. Odczyt/zapis DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Zwraca niestandardowe dane prezentacji. Tylko do odczytu [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Zwraca domyślny styl tekstu dla kształtów. Tylko do odczytu [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Zwraca kolekcję podpisów użytych do podpisania prezentacji. Tylko do odczytu [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu. Tylko do odczytu [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Reprezentuje numer pierwszego slajdu w prezentacji |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Zwraca menedżer czcionek. Tylko do odczytu [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Zwraca aktualny menedżer nagłówka i stopki. Tylko do odczytu [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Umożliwia łatwy dostęp do wszystkich hiperlinków zawartych w slajdach prezentacji (z wyłączeniem slajdów master, układów, notatek). Tylko do odczytu [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Zwraca kolekcję wszystkich obrazów w prezentacji. Tylko do odczytu [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji. Tylko do odczytu [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Zwraca menedżer mastera wersji papierowej. Tylko do odczytu [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Zwraca menedżer mastera notatek. Tylko do odczytu [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Zwraca listę wszystkich slajdów master zdefiniowanych w prezentacji. Tylko do odczytu [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Zwraca motyw master. Tylko do odczytu [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Zwraca obiekt rozmiaru slajdu notatek. Tylko do odczytu [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Zwraca menedżer uprawnień dla tej prezentacji. Tylko do odczytu [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji. Tylko do odczytu [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji. Tylko do odczytu [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji. Tylko do odczytu [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Zwraca ustawienia pokazu slajdów dla prezentacji. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Zwraca obiekt rozmiaru slajdu. Tylko do odczytu [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Zwraca informację o formacie, z którego została wczytana prezentacja. Tylko do odczytu [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Zwraca lub ustawia projekt VBA z makrami prezentacji. Odczyt/zapis [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji. Tylko do odczytu [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Zwraca właściwości widoku obejmującego całą prezentację. Tylko do odczytu [`IViewProperties`](../iviewproperties). |

## Metody

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Zwalnia wszystkie zasoby używane przez ten obiekt Presentation. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Zwraca obiekty Image dla wszystkich slajdów prezentacji. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji o określonym rozmiarze. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z niestandardowym skalowaniem. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji o określonym rozmiarze. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji z niestandardowym skalowaniem. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Zwraca obiekt Slide, MasterSlide lub LayoutSlide na podstawie Id. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Wyróżnia wszystkie dopasowania wyrażenia regularnego podanym kolorem. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Wyróżnia wszystkie dopasowania przykładowego tekstu podanym kolorem. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Łączy segmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach na wszystkich slajdach. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Zastępuje wszystkie dopasowania wyrażenia regularnego podanym ciągiem. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Zapisuje wszystkie slajdy prezentacji do zestawu plików reprezentujących znacznik XAML. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |

### Przykłady

Poniższy przykład pokazuje, jak utworzyć prezentację PowerPoint.

```csharp
[C#]
// Utwórz obiekt Presentation, który reprezentuje plik prezentacji
using (Presentation presentation = new Presentation())
{
    // Pobierz pierwszy slajd
    ISlide slide = presentation.Slides[0];
    // Dodaj automatyczny kształt typu linia
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Zapisz plik prezentacji.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Poniższy przykład pokazuje, jak otworzyć i zapisać prezentację.

```csharp
[C#]
// Wczytaj dowolny obsługiwany plik w Presentation, np. ppt, pptx, odp itp.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Zapisz plik prezentacji.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IPresentation](../ipresentation)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->