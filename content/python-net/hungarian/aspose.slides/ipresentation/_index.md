---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ipresentation/
---
## IPresentation osztály

Prezentációs dokumentum

Az IPresentation típus a következő tagokat jeleníti meg:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`current_date_time`](/slides/python-net/hu/aspose.slides/ipresentation/current_date_time/) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát.<br/>Alapértelmezés szerint ennek a Presentation objektumnak a létrehozási ideje.<br/>Olvasás/írás **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/ipresentation/header_footer_manager/) | Visszaadja a prezentáció HeaderFooter kezelőjét.<br/>Csak olvasás [`IPresentationHeaderFooterManager`](/slides/python-net/hu/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hu/aspose.slides/ipresentation/protection_manager/) | Megkapja a jogosultságok kezelőjét ehhez a prezentációhoz.<br/>Csak olvasás [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hu/aspose.slides/ipresentation/slides/) | Visszaad egy listát az összes diáról, ami a prezentációban definiált.<br/hu/>Csak olvasás [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hu/aspose.slides/ipresentation/sections/) | Visszaad egy listát az összes diarészről, ami a prezentációban definiált.<br/>Csak olvasás [`ISectionCollection`](/slides/python-net/hu/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hu/aspose.slides/ipresentation/slide_size/) | Visszaadja a dia méret objektumát.<br/>Csak olvasás [`ISlideSize`](/slides/python-net/hu/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hu/aspose.slides/ipresentation/notes_size/) | Visszaadja a jegyzet dia méret objektumát.<br/>Csak olvasás [`INotesSize`](/slides/python-net/hu/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/ipresentation/layout_slides/) | Visszaad egy listát az összes elrendezés diáról, ami a prezentációban definiált.<br/>Csak olvasás [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hu/aspose.slides/ipresentation/masters/) | Visszaad egy listát az összes mester diáról, ami a prezentációban definiált.<br/>Csak olvasás [`IMasterSlideCollection`](/slides/python-net/hu/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hu/aspose.slides/ipresentation/master_notes_slide_manager/) | Visszaadja a jegyzet mester kezelőjét.<br/>Csak olvasás [`IMasterNotesSlideManager`](/slides/python-net/hu/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hu/aspose.slides/ipresentation/master_handout_slide_manager/) | Visszaadja a szórólap mester kezelőjét.<br/>Csak olvasás [`IMasterHandoutSlideManager`](/slides/python-net/hu/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hu/aspose.slides/ipresentation/fonts_manager/) | Visszaadja a betűkészletek kezelőjét.<br/>Csak olvasás [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hu/aspose.slides/ipresentation/default_text_style/) | Visszaadja az alakzatok alapértelmezett szövegstílusát.<br/>Csak olvasás [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hu/aspose.slides/ipresentation/comment_authors/) | Visszaadja a komment szerzők gyűjteményét.<br/>Csak olvasás [`ICommentAuthorCollection`](/slides/python-net/hu/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hu/aspose.slides/ipresentation/document_properties/) | Visszaadja a DocumentProperties objektumot, amely szabványos és egyéni dokumentumtulajdonságokat tartalmaz.<br/>Csak olvasás [`IDocumentProperties`](/slides/python-net/hu/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hu/aspose.slides/ipresentation/images/) | Visszaadja az összes képet a prezentációban.<br/>Csak olvasás [`IImageCollection`](/slides/python-net/hu/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hu/aspose.slides/ipresentation/audios/) | Visszaadja az összes beágyazott hangfájlt a prezentációban.<br/>Csak olvasás [`IAudioCollection`](/slides/python-net/hu/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hu/aspose.slides/ipresentation/videos/) | Visszaadja az összes beágyazott videofájlt a prezentációban.<br/>Csak olvasás [`IVideoCollection`](/slides/python-net/hu/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/ipresentation/custom_data/) | Visszaadja a prezentáció egyéni adatait.<br/>Csak olvasás [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/hu/aspose.slides/ipresentation/vba_project/) | Megkapja a VBA projektet a prezentáció makróival.<br/>Olvasás/írás [`IVbaProject`](/slides/python-net/hu/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/hu/aspose.slides/ipresentation/source_format/) | Visszaadja, hogy melyik formátumból lett betöltve a prezentáció.<br/>Csak olvasás [`IPresentation.source_format`](/slides/python-net/hu/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/hu/aspose.slides/ipresentation/master_theme/) | Visszaadja a prezentáció mester témáját.<br/>Csak olvasás [`IMasterTheme`](/slides/python-net/hu/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/ipresentation/hyperlink_queries/) | Egyszerű hozzáférést biztosít az összes hiperhivatkozáshoz, ami a prezentáció diáin (nem a mester, elrendezés, jegyzet diákon) található.<br/>Csak olvasás [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hu/aspose.slides/ipresentation/view_properties/) | Megkapja a prezentációra vonatkozó nézet tulajdonságait.<br/>Csak olvasás [`IViewProperties`](/slides/python-net/hu/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hu/aspose.slides/ipresentation/first_slide_number/) | A prezentáció első dia számát képviseli.<br/>Olvasás/írás **int**. |
| [`all_custom_xml_parts`](/slides/python-net/hu/aspose.slides/ipresentation/all_custom_xml_parts/) | Visszaadja a prezentációban található összes egyéni adat részt.<br/>Csak olvasás [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/hu/aspose.slides/ipresentation/digital_signatures/) | Visszaadja az aláírások gyűjteményét, amelyekkel a prezentáció alá van írva.<br/>Csak olvasás [`IDigitalSignatureCollection`](/slides/python-net/hu/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/hu/aspose.slides/ipresentation/sensitivity_labels/) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét.<br/>Csak olvasás [`ISensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/hu/aspose.slides/ipresentation/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [`save(self, stream, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal. |
| [`save(self, fname, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal és további beállításokkal. |
| [`save(self, stream, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal és további beállításokkal. |
| [`save(self, fname, slides, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Elmenti a megadott diákat egy fájlba a megadott formátummal. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a megadott diákat egy fájlba a megadott formátummal. |
| [`save(self, stream, slides, format)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Elmenti a megadott diákat egy adatfolyamra a megadott formátummal. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a megadott diákat egy adatfolyamra a megadott formátummal. |
| [`save(self, options)`](/slides/python-net/hu/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Elmenti a prezentáció összes diáját egy XAML jelölést reprezentáló fájlkészletbe. |
| [`get_images(self, options)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Visszaad egy Thumbnail Image objektumot az összes diára a prezentációban. |
| [`get_images(self, options, slides)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Visszaad egy Thumbnail Bitmap objektumot a megadott diákra a prezentációban. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Visszaad egy Thumbnail Image objektumot az összes diára a prezentációban egyedi méretezéssel. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Visszaad egy Thumbnail Image objektumot a megadott diákra a prezentációban egyedi méretezéssel. |
| [`get_images(self, options, image_size)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Visszaad egy Thumbnail Image objektumot az összes diára a prezentációban a megadott mérettel. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hu/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Visszaad egy Thumbnail Image objektumot a megadott diákra a prezentációban a megadott mérettel. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Kiemeli a mintaszöveg összes előfordulását a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Kiemeli a mintaszöveg összes előfordulását a megadott színnel. |
| [`get_slide_by_id(self, id)`](/slides/python-net/hu/aspose.slides/ipresentation/get_slide_by_id/#int) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az Id alapján. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Összevonja a hasonló formázású futamokat minden bekezdésben minden elfogadható alakzatban minden dián. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/ipresentation/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/hu/aspose.slides/ipresentation/refresh_charts_data/#bool) | Újratölti az összes diagram adatait a prezentációban a forrás munkafüzetekből. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)