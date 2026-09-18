---
title: Presentation class
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/presentation/
---
## Presentation osztály

Microsoft PowerPoint prezentációt képviseli.

A Presentation típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#) | Ez a konstruktor új prezentációt hoz létre a semmiből.<br/>            A létrehozott prezentáció egy üres diát tartalmaz. |
| [`__init__(self, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#loadoptions) | Ez a konstruktor új prezentációt hoz létre a semmiből.<br/>            A létrehozott prezentáció egy üres diát tartalmaz. |
| [`__init__(self, stream)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#iorawiobase) | Ez a konstruktor a meglévő Presentation beolvasásának elsődleges mechanizmusa. |
| [`__init__(self, stream, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Ez a konstruktor a meglévő Presentation beolvasásának elsődleges mechanizmusa. |
| [`__init__(self, file)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#str) | Ez a konstruktor egy forrásfájl útvonalát kapja, ahonnan<br/>             a Presentation tartalma beolvasásra kerül. |
| [`__init__(self, file, load_options)`](/slides/python-net/hu/aspose.slides/presentation/__init__/#str-loadoptions) | Ez a konstruktor egy forrásfájl útvonalát kapja, ahonnan<br/>            a Presentation tartalma beolvasásra kerül. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`current_date_time`](/slides/python-net/hu/aspose.slides/presentation/current_date_time/) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát.<br/>            Alapértelmezés szerint a Presentation objektum létrehozásának időpontja.<br/>            Olvasás/írás **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/hu/aspose.slides/presentation/header_footer_manager/) | Visszaadja a tényleges HeaderFooter kezelőt.<br/>            Csak olvasás [`IPresentationHeaderFooterManager`](/slides/python-net/hu/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/hu/aspose.slides/presentation/protection_manager/) | Megkapja a jelen prezentáció engedélykezelőjét.<br/>            Csak olvasás [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/hu/aspose.slides/presentation/slides/) | Visszaad egy listát az összes diákról, amely a prezentációban definiálva van.<br/hu/>            Csak olvasás [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/hu/aspose.slides/presentation/sections/) | Visszaad egy listát az összes diarészről, amely a prezentációban definiálva van.<br/>            Csak olvasás [`ISectionCollection`](/slides/python-net/hu/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/hu/aspose.slides/presentation/slide_size/) | Visszaad egy dia méret objektumot.<br/>            Csak olvasás [`ISlideSize`](/slides/python-net/hu/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/hu/aspose.slides/presentation/notes_size/) | Visszaad egy jegyzetdia méret objektumot.<br/>            Csak olvasás [`INotesSize`](/slides/python-net/hu/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/hu/aspose.slides/presentation/layout_slides/) | Visszaad egy listát az összes elrendezési diáról, amely a prezentációban definiálva van.<br/>            Csak olvasás [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/hu/aspose.slides/presentation/masters/) | Visszaad egy listát az összes mester diákról, amely a prezentációban definiálva van.<br/>            Csak olvasás [`IMasterSlideCollection`](/slides/python-net/hu/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/hu/aspose.slides/presentation/master_notes_slide_manager/) | Visszaadja a jegyzet mester kezelőt.<br/>            Csak olvasás [`IMasterNotesSlideManager`](/slides/python-net/hu/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/hu/aspose.slides/presentation/master_handout_slide_manager/) | Visszaadja a kézbesítő mester kezelőt.<br/>            Csak olvasás [`IMasterHandoutSlideManager`](/slides/python-net/hu/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/hu/aspose.slides/presentation/fonts_manager/) | Visszaadja a betűtípusok kezelőjét.<br/>            Csak olvasás [`IFontsManager`](/slides/python-net/hu/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/hu/aspose.slides/presentation/default_text_style/) | Visszaadja az alakzatok alapértelmezett szövegstílusát.<br/>            Csak olvasás [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/hu/aspose.slides/presentation/comment_authors/) | Visszaadja a megjegyzések szerzőinek gyűjteményét.<br/>            Csak olvasás [`ICommentAuthorCollection`](/slides/python-net/hu/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/hu/aspose.slides/presentation/document_properties/) | Visszaad egy DocumentProperties objektumot, amely szabványos és egyéni dokumentumtulajdonságokat tartalmaz.<br/>            Csak olvasás [`IDocumentProperties`](/slides/python-net/hu/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/hu/aspose.slides/presentation/images/) | Visszaadja az összes képet a prezentációban.<br/>            Csak olvasás [`IImageCollection`](/slides/python-net/hu/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/hu/aspose.slides/presentation/audios/) | Visszaadja a prezentációba beágyazott összes audiofájl gyűjteményét.<br/>            Csak olvasás [`IAudioCollection`](/slides/python-net/hu/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/hu/aspose.slides/presentation/videos/) | Visszaadja a prezentációba beágyazott összes videófájl gyűjteményét.<br/>            Csak olvasás [`IVideoCollection`](/slides/python-net/hu/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/hu/aspose.slides/presentation/slide_show_settings/) | Visszaadja a prezentáció diavetítés beállításait. |
| [`digital_signatures`](/slides/python-net/hu/aspose.slides/presentation/digital_signatures/) | Visszaadja a prezentáció aláírására használt aláírások gyűjteményét.<br/>            Csak olvasás [`IDigitalSignatureCollection`](/slides/python-net/hu/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/hu/aspose.slides/presentation/custom_data/) | Visszaadja a prezentáció egyéni adatait.<br/>            Csak olvasás [`ICustomData`](/slides/python-net/hu/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/hu/aspose.slides/presentation/all_custom_xml_parts/) | Visszaadja a prezentáció összes egyéni adat részét.<br/>            Csak olvasás [`ICustomXmlPart`](/slides/python-net/hu/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/hu/aspose.slides/presentation/vba_project/) | Megkapja vagy beállítja a VBA projektet a prezentáció makróival.<br/>            Olvasás/írás [`IVbaProject`](/slides/python-net/hu/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/hu/aspose.slides/presentation/hyperlink_queries/) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely a prezentáció diáiban szerepel (nem a mester, elrendezés, jegyzet diákban).<br/>            Csak olvasás [`IHyperlinkQueries`](/slides/python-net/hu/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/hu/aspose.slides/presentation/view_properties/) | Megkapja a prezentációra kiterjedő nézeti tulajdonságokat.<br/>            Csak olvasás [`IViewProperties`](/slides/python-net/hu/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/hu/aspose.slides/presentation/first_slide_number/) | A prezentáció első diaszámát jelöli |
| [`sensitivity_labels`](/slides/python-net/hu/aspose.slides/presentation/sensitivity_labels/) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét.<br/>            Csak olvasás [`ISensitivityLabelCollection`](/slides/python-net/hu/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/hu/aspose.slides/presentation/source_format/) | Visszaadja a prezentáció betöltésének formátumáról szóló információt.<br/>            Csak olvasás [`SourceFormat`](/slides/python-net/hu/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/hu/aspose.slides/presentation/master_theme/) | Visszaadja a mester témát.<br/>            Csak olvasás [`IMasterTheme`](/slides/python-net/hu/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/hu/aspose.slides/presentation/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Elmenti a prezentáció minden diáját egy fájlba a megadott formátummal. |
| [`save(self, stream, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Elmenti a prezentáció minden diáját egy adatfolyamba a megadott formátummal. |
| [`save(self, fname, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a prezentáció minden diáját egy adatfolyamba a megadott formátummal és további beállításokkal. |
| [`save(self, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Elmenti a prezentáció minden diáját egy fájlsorozatba, amely XAML jelölést képvisel. |
| [`save(self, fname, slides, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Elmenti a megadott diákot a prezentációból egy fájlba a megadott formátummal, megőrizve az oldalszámot. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a megadott diákot a prezentációból egy fájlba a megadott formátummal, megőrizve az oldalszámot. |
| [`save(self, stream, slides, format)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Elmenti a megadott diákot a prezentációból egy adatfolyamba a megadott formátummal, megőrizve az oldalszámot. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/hu/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Elmenti a megadott diákot a prezentációból egy adatfolyamba a megadott formátummal, megőrizve az oldalszámot. |
| [`get_images(self, options)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Visszaad Image objektumokat a prezentáció minden diájához. |
| [`get_images(self, options, slides)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Visszaad Thumbnail Image objektumokat a megadott diákhoz a prezentációból. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Visszaad Thumbnail Image objektumokat a prezentáció minden diájához egyéni méretezéssel. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Visszaad Thumbnail Image objektumokat a megadott diákhoz a prezentációból egyéni méretezéssel. |
| [`get_images(self, options, image_size)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Visszaad Thumbnail Image objektumokat a prezentáció minden diájához megadott mérettel. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/hu/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Visszaad Thumbnail Image objektumokat a megadott diákhoz a prezentációból megadott mérettel. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/hu/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/hu/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [`get_slide_by_id(self, id)`](/slides/python-net/hu/aspose.slides/presentation/get_slide_by_id/#int) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az Id alapján. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/hu/aspose.slides/presentation/join_portions_with_same_formatting/#) | Összevonja a ugyanolyan formázású futamokat az összes bekezdésben minden elfogadható alakzatban minden dián. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/hu/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/hu/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/hu/aspose.slides/presentation/replace_regex/#str-str) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)