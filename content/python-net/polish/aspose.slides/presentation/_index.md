---
title: Presentation class
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/presentation/
---
## Presentation klasa

Reprezentuje prezentację Microsoft PowerPoint.

Typ Presentation udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#) | Ten konstruktor tworzy nową prezentację od podstaw.<br/>            Utworzona prezentacja ma jeden pusty slajd. |
| [`__init__(self, load_options)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#loadoptions) | Ten konstruktor tworzy nową prezentację od podstaw.<br/>            Utworzona prezentacja ma jeden pusty slajd. |
| [`__init__(self, stream)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#iorawiobase) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [`__init__(self, stream, load_options)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Ten konstruktor jest podstawowym mechanizmem odczytu istniejącej prezentacji. |
| [`__init__(self, file)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#str) | Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego<br/>             zawartość prezentacji jest odczytywana. |
| [`__init__(self, file, load_options)`](/slides/python-net/pl/aspose.slides/presentation/__init__/#str-loadoptions) | Ten konstruktor pobiera ścieżkę pliku źródłowego, z którego<br/>            zawartość prezentacji jest odczytywana. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`current_date_time`](/slides/python-net/pl/aspose.slides/presentation/current_date_time/) | Zwraca lub ustawia datę i godzinę, które zastąpią zawartość pól datetime.<br/>            Domyślnie czas utworzenia tego obiektu Presentation.<br/>            Odczyt/zapis **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/presentation/header_footer_manager/) | Zwraca aktualny menedżer HeaderFooter.<br/>            Tylko do odczytu [`IPresentationHeaderFooterManager`](/slides/python-net/pl/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/pl/aspose.slides/presentation/protection_manager/) | Pobiera menedżera uprawnień dla tej prezentacji.<br/>            Tylko do odczytu [`IProtectionManager`](/slides/python-net/pl/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/pl/aspose.slides/presentation/slides/) | Zwraca listę wszystkich slajdów zdefiniowanych w prezentacji.<br/pl/>            Tylko do odczytu [`ISlideCollection`](/slides/python-net/pl/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/pl/aspose.slides/presentation/sections/) | Zwraca listę wszystkich sekcji slajdów zdefiniowanych w prezentacji.<br/>            Tylko do odczytu [`ISectionCollection`](/slides/python-net/pl/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/pl/aspose.slides/presentation/slide_size/) | Zwraca obiekt rozmiaru slajdu.<br/>            Tylko do odczytu [`ISlideSize`](/slides/python-net/pl/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/pl/aspose.slides/presentation/notes_size/) | Zwraca obiekt rozmiaru slajdu notatek.<br/>            Tylko do odczytu [`INotesSize`](/slides/python-net/pl/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/pl/aspose.slides/presentation/layout_slides/) | Zwraca listę wszystkich slajdów układu zdefiniowanych w prezentacji.<br/>            Tylko do odczytu [`IGlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/pl/aspose.slides/presentation/masters/) | Zwraca listę wszystkich slajdów master zdefiniowanych w prezentacji.<br/>            Tylko do odczytu [`IMasterSlideCollection`](/slides/python-net/pl/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/pl/aspose.slides/presentation/master_notes_slide_manager/) | Zwraca menedżera notatek master.<br/>            Tylko do odczytu [`IMasterNotesSlideManager`](/slides/python-net/pl/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/pl/aspose.slides/presentation/master_handout_slide_manager/) | Zwraca menedżera handout master.<br/>            Tylko do odczytu [`IMasterHandoutSlideManager`](/slides/python-net/pl/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/pl/aspose.slides/presentation/fonts_manager/) | Zwraca menedżera czcionek.<br/>            Tylko do odczytu [`IFontsManager`](/slides/python-net/pl/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/pl/aspose.slides/presentation/default_text_style/) | Zwraca domyślny styl tekstu dla kształtów.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/pl/aspose.slides/presentation/comment_authors/) | Zwraca kolekcję autorów komentarzy.<br/>            Tylko do odczytu [`ICommentAuthorCollection`](/slides/python-net/pl/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/pl/aspose.slides/presentation/document_properties/) | Zwraca obiekt DocumentProperties, który zawiera standardowe i niestandardowe właściwości dokumentu.<br/>            Tylko do odczytu [`IDocumentProperties`](/slides/python-net/pl/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/pl/aspose.slides/presentation/images/) | Zwraca kolekcję wszystkich obrazów w prezentacji.<br/>            Tylko do odczytu [`IImageCollection`](/slides/python-net/pl/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/pl/aspose.slides/presentation/audios/) | Zwraca kolekcję wszystkich osadzonych plików audio w prezentacji.<br/>            Tylko do odczytu [`IAudioCollection`](/slides/python-net/pl/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/pl/aspose.slides/presentation/videos/) | Zwraca kolekcję wszystkich osadzonych plików wideo w prezentacji.<br/>            Tylko do odczytu [`IVideoCollection`](/slides/python-net/pl/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/pl/aspose.slides/presentation/slide_show_settings/) | Zwraca ustawienia pokazu slajdów dla prezentacji. |
| [`digital_signatures`](/slides/python-net/pl/aspose.slides/presentation/digital_signatures/) | Zwraca kolekcję podpisów używanych do podpisania prezentacji.<br/>            Tylko do odczytu [`IDigitalSignatureCollection`](/slides/python-net/pl/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/pl/aspose.slides/presentation/custom_data/) | Zwraca niestandardowe dane prezentacji.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/pl/aspose.slides/presentation/all_custom_xml_parts/) | Zwraca wszystkie części niestandardowych danych w prezentacji.<br/>            Tylko do odczytu [`ICustomXmlPart`](/slides/python-net/pl/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/pl/aspose.slides/presentation/vba_project/) | Pobiera lub ustawia projekt VBA z makrami prezentacji.<br/>            Odczyt/zapis [`IVbaProject`](/slides/python-net/pl/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/presentation/hyperlink_queries/) | Zapewnia łatwy dostęp do wszystkich hiperłączy zawartych we wszystkich slajdach prezentacji (z wyłączeniem slajdów master, layout, notes).<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/pl/aspose.slides/presentation/view_properties/) | Pobiera właściwości widoku obejmujące całą prezentację.<br/>            Tylko do odczytu [`IViewProperties`](/slides/python-net/pl/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/pl/aspose.slides/presentation/first_slide_number/) | Reprezentuje numer pierwszego slajdu w prezentacji |
| [`sensitivity_labels`](/slides/python-net/pl/aspose.slides/presentation/sensitivity_labels/) | Zwraca kolekcję etykiet wrażliwości zastosowanych do dokumentu prezentacji.<br/>            Tylko do odczytu [`ISensitivityLabelCollection`](/slides/python-net/pl/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/pl/aspose.slides/presentation/source_format/) | Zwraca informacje o formacie, z którego załadowano prezentację.<br/>            Tylko do odczytu [`SourceFormat`](/slides/python-net/pl/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/pl/aspose.slides/presentation/master_theme/) | Zwraca motyw master.<br/>            Tylko do odczytu [`IMasterTheme`](/slides/python-net/pl/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/pl/aspose.slides/presentation/presentation/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/pl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Zapisuje wszystkie slajdy prezentacji do pliku w określonym formacie. |
| [`save(self, stream, format)`](/slides/python-net/pl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie. |
| [`save(self, fname, format, options)`](/slides/python-net/pl/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/pl/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Zapisuje wszystkie slajdy prezentacji do strumienia w określonym formacie oraz z dodatkowymi opcjami. |
| [`save(self, options)`](/slides/python-net/pl/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Zapisuje wszystkie slajdy prezentacji jako zestaw plików reprezentujących znacznik XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/pl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/pl/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Zapisuje określone slajdy prezentacji do pliku w określonym formacie, zachowując numery stron. |
| [`save(self, stream, slides, format)`](/slides/python-net/pl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/pl/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Zapisuje określone slajdy prezentacji do strumienia w określonym formacie, zachowując numery stron. |
| [`get_images(self, options)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Zwraca obiekty Image dla wszystkich slajdów prezentacji. |
| [`get_images(self, options, slides)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji z własną skalą. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji z własną skalą. |
| [`get_images(self, options, image_size)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Zwraca obiekty Thumbnail Image dla wszystkich slajdów prezentacji o określonym rozmiarze. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/pl/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Zwraca obiekty Thumbnail Image dla określonych slajdów prezentacji o określonym rozmiarze. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pl/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Wyróżnia wszystkie dopasowania przykładowego tekstu określonym kolorem. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pl/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Wyróżnia wszystkie dopasowania przykładowego tekstu określonym kolorem. |
| [`get_slide_by_id(self, id)`](/slides/python-net/pl/aspose.slides/presentation/get_slide_by_id/#int) | Zwraca obiekt Slide, MasterSlide lub LayoutSlide według Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/presentation/join_portions_with_same_formatting/#) | Łączy fragmenty z takim samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach na wszystkich slajdach. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pl/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Wyróżnia wszystkie dopasowania wyrażenia regularnego określonym kolorem. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pl/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Zastępuje wszystkie wystąpienia określonego tekstu innym określonym tekstem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pl/aspose.slides/presentation/replace_regex/#str-str) | Zastępuje wszystkie dopasowania wyrażenia regularnego określonym ciągiem. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)