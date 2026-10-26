---
title: IPresentation class
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/ipresentation/
---
## IPresentation osztály

Prezentációs dokumentum

Az IPresentation típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`current_date_time`](/slides/python-net/hu/aspose.slides/ipresentation/current_date_time/) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát.<br/>            Alapértelmezés szerint ennek a Presentation objektumnak a létrehozási ideje.<br/>            Olvasás/írás **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/ipresentation/header_footer_manager/) | Visszaadja a prezentáció HeaderFooter kezelőjét.<br/>            Csak olvasható [`IPresentationHeaderFooterManager`](/slides/python-net/hu/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hu/aspose.slides/ipresentation/protection_manager/) | Lekéri a jogosultságok kezelőjét ehhez a prezentációhoz.<br/>            Csak olvasható [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hu/aspose.slides/ipresentation/slides/) | Visszaadja a prezentációban definiált összes dia listáját.<br/hu/>            Csak olvasható [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hu/aspose.slides/ipresentation/sections/) | Visszaadja a prezentációban definiált összes diarészlet listáját.<br/>            Csak olvasható [`ISectionCollection`](/slides/python-net/hu/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hu/aspose.slides/ipresentation/slide_size/) | Visszaadja a dia méret objektumot.<br/>            Csak olvasható [`ISlideSize`](/slides/python-net/hu/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hu/aspose.slides/ipresentation/notes_size/) | Visszaadja a jegyzetdia méret objektumot.<br/>            Csak olvasható [`INotesSize`](/slides/python-net/hu/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides/) | Visszaadja a prezentációban definiált összes elrendezésdia listáját.<br/>            Csak olvasható [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hu/aspose.slides/ipresentation/masters/) | Visszaadja a prezentációban definiált összes mesterdia listáját.<br/>            Csak olvasható [`IMasterSlideCollection`](/slides/python-net/hu/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hu/aspose.slides/ipresentation/master_notes_slide_manager/) | Visszaadja a jegyzet mester kezelőt.<br/>            Csak olvasható [`IMasterNotesSlideManager`](/slides/python-net/hu/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hu/aspose.slides/ipresentation/master_handout_slide_manager/) | Visszaadja a szórólap mester kezelőt.<br/>            Csak olvasható [`IMasterHandoutSlideManager`](/slides/python-net/hu/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hu/aspose.slides/ipresentation/fonts_manager/) | Visszaadja a betűtípusok kezelőjét.<br/>            Csak olvasható [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hu/aspose.slides/ipresentation/default_text_style/) | Visszaadja az alakzatok alapértelmezett szövegstílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hu/aspose.slides/ipresentation/comment_authors/) | Visszaadja a megjegyzések szerzőinek gyűjteményét.<br/>            Csak olvasható [`ICommentAuthorCollection`](/slides/python-net/hu/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hu/aspose.slides/ipresentation/document_properties/) | Visszaadja a DocumentProperties objektumot, amely a szabványos és egyéni dokumentumtulajdonságokat tartalmazza.<br/>            Csak olvasható [`IDocumentProperties`](/slides/python-net/hu/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hu/aspose.slides/ipresentation/images/) | Visszaadja a prezentációban lévő összes kép gyűjteményét.<br/>            Csak olvasható [`IImageCollection`](/slides/python-net/hu/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hu/aspose.slides/ipresentation/audios/) | Visszaadja a prezentációba beágyazott összes hangfájl gyűjteményét.<br/>            Csak olvasható [`IAudioCollection`](/slides/python-net/hu/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hu/aspose.slides/ipresentation/videos/) | Visszaadja a prezentációba beágyazott összes videófájl gyűjteményét.<br/>            Csak olvasható [`IVideoCollection`](/slides/python-net/hu/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/ipresentation/custom_data/) | Visszaadja a prezentáció egyéni adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/hu/aspose.slides/ipresentation/vba_project/) | Lekéri a VBA projektet a prezentáció makróival.<br/>            Olvasás/írás [`IVbaProject`](/slides/python-net/hu/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/hu/aspose.slides/ipresentation/source_format/) | Visszaadja azt az információt, hogy melyik formátumból lett betöltve a prezentáció.<br/>            Csak olvasható [`IPresentation.source_format`](/slides/python-net/hu/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/hu/aspose.slides/ipresentation/master_theme/) | Visszaadja a prezentáció mester témáját.<br/>            Csak olvasható [`IMasterTheme`](/slides/python-net/hu/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/ipresentation/hyperlink_queries/) | Könnyű hozzáférést biztosít a prezentáció összes diájában (nem a mester, elrendezés vagy jegyzet diákban) található hyperhivatkozáshoz.<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hu/aspose.slides/ipresentation/view_properties/) | Lekéri a prezentációra kiterjedő nézet tulajdonságait.<br/>            Csak olvasható [`IViewProperties`](/slides/python-net/hu/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hu/aspose.slides/ipresentation/first_slide_number/) | A prezentáció első dia számát képviseli.<br/>            Olvasás/írás **int**. |
| [`all_custom_xml_parts`](/slides/python-net/hu/aspose.slides/ipresentation/all_custom_xml_parts/) | Visszaadja a prezentáció összes egyéni adat részét.<br/>            Csak olvasható [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/hu/aspose.slides/ipresentation/digital_signatures/) | Visszaadja a prezentáció aláírására használt aláírások gyűjteményét.<br/>            Csak olvasható [`IDigitalSignatureCollection`](/slides/python-net/hu/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/hu/aspose.slides/ipresentation/sensitivity_labels/) | Visszaadja a prezentáció dokumentumára alkalmazott érzékenységi címkék gyűjteményét.<br/>            Csak olvasható [`ISensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/hu/aspose.slides/ipresentation/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Ment minden diát egy prezentációból egy fájlba a megadott formátummal. |
| [`save(self, stream, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Ment minden diát egy prezentációból egy adatfolyamra a megadott formátummal. |
| [`save(self, fname, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Ment minden diát egy prezentációból egy fájlba a megadott formátummal és további beállításokkal. |
| [`save(self, stream, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Ment minden diát egy prezentációból egy adatfolyamra a megadott formátummal és további beállításokkal. |
| [`save(self, fname, slides, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Ment a megadott diákat egy prezentációból egy fájlba a megadott formátummal. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Ment a megadott diákat egy prezentációból egy fájlba a megadott formátummal. |
| [`save(self, stream, slides, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Ment a megadott diákat egy prezentációból egy adatfolyamra a megadott formátummal. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Ment a megadott diákat egy prezentációból egy adatfolyamra a megadott formátummal. |
| [`save(self, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Ment minden diát egy prezentációból egy XAML jelölést ábrázoló fájlsorozatba. |
| [`get_images(self, options)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Visszaad Miniatűr Kép objektumokat az összes diához egy prezentációban. |
| [`get_images(self, options, slides)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Visszaad Miniatűr Bitmap objektumokat a megadott diákhoz egy prezentációban. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Visszaad Miniatűr Kép objektumokat az összes diához egy prezentációban egyéni skálázással. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Visszaad Miniatűr Kép objektumokat a megadott diákhoz egy prezentációban egyéni skálázással. |
| [`get_images(self, options, image_size)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Visszaad Miniatűr Kép objektumokat az összes diához egy prezentációban a megadott mérettel. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Visszaad Miniatűr Kép objektumokat a megadott diákhoz egy prezentációban a megadott mérettel. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [`get_slide_by_id(self, id)`](/slides/python-net/hu/aspose.slides/ipresentation/get_slide_by_id/#int) | Visszaad egy Slide, MasterSlide vagy LayoutSlide elemet az Id alapján. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Összefűzi a ugyanazt a formázást tartalmazó futamokat az összes bekezdésben az összes alkalmas alakzatban minden diában. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/ipresentation/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)