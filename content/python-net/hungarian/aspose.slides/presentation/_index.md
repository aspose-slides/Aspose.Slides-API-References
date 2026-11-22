---
title: Presentation class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/presentation/
---
## Presentation osztály

Egy Microsoft PowerPoint prezentációt reprezentál.

A Presentation típus a következő tagokat teszi elérhetővé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#) | Ez a konstruktor új prezentációt hoz létre az elejétől.<br/>            A létrehozott prezentációnak egy üres diája van. |
| [`__init__(self, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#loadoptions) | Ez a konstruktor új prezentációt hoz létre az elejétől.<br/>            A létrehozott prezentációnak egy üres diája van. |
| [`__init__(self, stream)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#iorawiobase) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasására. |
| [`__init__(self, stream, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasására. |
| [`__init__(self, file)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#str) | Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből<br/>             a Presentation tartalma beolvasásra kerül. |
| [`__init__(self, file, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#str-loadoptions) | Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből<br/>            a Presentation tartalma beolvasásra kerül. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`current_date_time`](/slides/python-net/hu/aspose.slides/presentation/current_date_time/) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát.<br/>            Alapértelmezés szerint a Presentation objektum létrehozásának időpontja.<br/>            Olvasás/írás **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/presentation/header_footer_manager/) | Visszaadja a tényleges HeaderFooter kezelőt.<br/>            Csak olvasható [`IPresentationHeaderFooterManager`](/slides/python-net/hu/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hu/aspose.slides/presentation/protection_manager/) | Lekéri ennek a prezentációnak a jogosultságkezelőt.<br/>            Csak olvasható [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hu/aspose.slides/presentation/slides/) | Visszaad egy listát az összes diáról, amely a prezentációban definiálva van.<br/hu/>            Csak olvasható [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hu/aspose.slides/presentation/sections/) | Visszaad egy listát az összes diaszakaszról, amely a prezentációban definiálva van.<br/>            Csak olvasható [`ISectionCollection`](/slides/python-net/hu/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hu/aspose.slides/presentation/slide_size/) | Visszaadja a diaméret objektumot.<br/>            Csak olvasható [`ISlideSize`](/slides/python-net/hu/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hu/aspose.slides/presentation/notes_size/) | Visszaadja a jegyzetdia méret objektumot.<br/>            Csak olvasható [`INotesSize`](/slides/python-net/hu/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/presentation/layout_slides/) | Visszaad egy listát az összes elrendezési diáról, amely a prezentációban definiálva van.<br/>            Csak olvasható [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hu/aspose.slides/presentation/masters/) | Visszaad egy listát az összes fő diáról, amely a prezentációban definiálva van.<br/>            Csak olvasható [`IMasterSlideCollection`](/slides/python-net/hu/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hu/aspose.slides/presentation/master_notes_slide_manager/) | Visszaadja a jegyzet fő kezelőt.<br/>            Csak olvasható [`IMasterNotesSlideManager`](/slides/python-net/hu/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hu/aspose.slides/presentation/master_handout_slide_manager/) | Visszaadja a szórólap fő kezelőt.<br/>            Csak olvasható [`IMasterHandoutSlideManager`](/slides/python-net/hu/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hu/aspose.slides/presentation/fonts_manager/) | Visszaadja a betűtípus-kezelőt.<br/>            Csak olvasható [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hu/aspose.slides/presentation/default_text_style/) | Visszaadja az alapértelmezett szövegstílust az alakzatokhoz.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hu/aspose.slides/presentation/comment_authors/) | Visszaadja a megjegyzések szerzőinek gyűjteményét.<br/>            Csak olvasható [`ICommentAuthorCollection`](/slides/python-net/hu/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hu/aspose.slides/presentation/document_properties/) | Visszaadja a DocumentProperties objektumot, amely szabványos és egyedi dokumentumtulajdonságokat tartalmaz.<br/>            Csak olvasható [`IDocumentProperties`](/slides/python-net/hu/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hu/aspose.slides/presentation/images/) | Visszaadja az összes képet a prezentációban.<br/>            Csak olvasható [`IImageCollection`](/slides/python-net/hu/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hu/aspose.slides/presentation/audios/) | Visszaadja a prezentációba beágyazott összes audiofájl gyűjteményét.<br/>            Csak olvasható [`IAudioCollection`](/slides/python-net/hu/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hu/aspose.slides/presentation/videos/) | Visszaadja a prezentációba beágyazott összes videofájl gyűjteményét.<br/>            Csak olvasható [`IVideoCollection`](/slides/python-net/hu/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/hu/aspose.slides/presentation/slide_show_settings/) | Visszaadja a diavetítés beállításait a prezentációhoz. |
| [`digital_signatures`](/slides/python-net/hu/aspose.slides/presentation/digital_signatures/) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét.<br/>            Csak olvasható [`IDigitalSignatureCollection`](/slides/python-net/hu/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/presentation/custom_data/) | Visszaadja a prezentáció egyedi adatait.<br/>            Csak olvasható [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/hu/aspose.slides/presentation/all_custom_xml_parts/) | Visszaadja a prezentáció összes egyedi adat részét.<br/>            Csak olvasható [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/hu/aspose.slides/presentation/vba_project/) | Lekéri vagy beállítja a VBA projektet a prezentáció makrókkal.<br/>            Olvasás/írás [`IVbaProject`](/slides/python-net/hu/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/presentation/hyperlink_queries/) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián található (nem a fő, elrendezési, jegyzet diákon).<br/>            Csak olvasható [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hu/aspose.slides/presentation/view_properties/) | Lekéri a prezentáció általános nézet tulajdonságait.<br/>            Csak olvasható [`IViewProperties`](/slides/python-net/hu/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hu/aspose.slides/presentation/first_slide_number/) | A prezentáció első diájának számát jelöli |
| [`sensitivity_labels`](/slides/python-net/hu/aspose.slides/presentation/sensitivity_labels/) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét.<br/>            Csak olvasható [`ISensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/hu/aspose.slides/presentation/source_format/) | Visszaadja az információt arról, mely formátumból lett betöltve a prezentáció.<br/>            Csak olvasható [`SourceFormat`](/slides/python-net/hu/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/hu/aspose.slides/presentation/master_theme/) | Visszaadja a fő témát.<br/>            Csak olvasható [`IMasterTheme`](/slides/python-net/hu/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/hu/aspose.slides/presentation/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Elmenti a prezentáció összes diáját egy megadott formátumú fájlba. |
| [`save(self, stream, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátumban. |
| [`save(self, fname, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátumban és további beállításokkal. |
| [`save(self, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Elmenti a prezentáció összes diáját egy XAML jelölőnyelvet reprezentáló fájlhalmazba. |
| [`save(self, fname, slides, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot. |
| [`save(self, stream, slides, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátumban, megőrizve az oldalszámot. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátumban, megőrizve az oldalszámot. |
| [`get_images(self, options)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Visszaad egy Image objektumot a prezentáció összes diájához. |
| [`get_images(self, options, slides)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Visszaad egy Thumbnail Image objektumot a prezentáció megadott diáihoz. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához egyedi méretezéssel. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Visszaad egy Thumbnail Image objektumot a prezentáció megadott diáihoz egyedi méretezéssel. |
| [`get_images(self, options, image_size)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Visszaad egy Thumbnail Image objektumot a prezentáció összes diájához a megadott mérettel. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Visszaad egy Thumbnail Image objektumot a prezentáció megadott diáihoz a megadott mérettel. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`get_slide_by_id(self, id)`](/slides/python-net/hu/aspose.slides/presentation/get_slide_by_id/#int) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/presentation/join_portions_with_same_formatting/#) | Egyesíti a ugyanazzal a formázással rendelkező futamokat az összes bekezdésben az összes elfogadható alakzatban az összes dián. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/presentation/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/hu/aspose.slides/presentation/refresh_charts_data/#bool) | Újratölti az adatokat a prezentáció összes diagramjához a forrás munkafüzetekből. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)