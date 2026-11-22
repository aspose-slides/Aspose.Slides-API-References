---
title: Presentation class
second_title: Aspose.Slides pro Python pomocí .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/presentation/
---
## Presentation třída

Představuje prezentaci Microsoft PowerPoint.

Typ Presentation vystavuje následující členy:

## Konstruktory

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#) | Tento konstruktér vytvoří novou prezentaci od nuly.<br/>            Vytvořená prezentace má jeden prázdný snímek. |
| [`__init__(self, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#loadoptions) | Tento konstruktér vytvoří novou prezentaci od nuly.<br/>            Vytvořená prezentace má jeden prázdný snímek. |
| [`__init__(self, stream)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#iorawiobase) | Tento konstruktér je primárním mechanismem pro čtení existující prezentace. |
| [`__init__(self, stream, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Tento konstruktér je primárním mechanismem pro čtení existující prezentace. |
| [`__init__(self, file)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#str) | Tento konstruktér získá cestu k souboru zdroje, ze které<br/>             jsou načteny obsah prezentace. |
| [`__init__(self, file, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#str-loadoptions) | Tento konstruktér získá cestu k souboru zdroje, ze které<br/>            jsou načteny obsah prezentace. |

## Vlastnosti

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/cs/aspose.slides/presentation/current_date_time/) | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datetime.<br/>            Čas vytvoření tohoto objektu Presentation jako výchozí.<br/>            Číst/Zapisovat **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/presentation/header_footer_manager/) | Vrací aktuální správce HeaderFooter.<br/>            Pouze pro čtení [`IPresentationHeaderFooterManager`](/slides/python-net/cs/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/cs/aspose.slides/presentation/protection_manager/) | Získá správce oprávnění pro tuto prezentaci.<br/>            Pouze pro čtení [`IProtectionManager`](/slides/python-net/cs/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/cs/aspose.slides/presentation/slides/) | Vrací seznam všech snímků, které jsou definovány v prezentaci.<br/cs/>            Pouze pro čtení [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/cs/aspose.slides/presentation/sections/) | Vrací seznam všech sekcí snímků, které jsou definovány v prezentaci.<br/>            Pouze pro čtení [`ISectionCollection`](/slides/python-net/cs/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/cs/aspose.slides/presentation/slide_size/) | Vrací objekt velikosti snímku.<br/>            Pouze pro čtení [`ISlideSize`](/slides/python-net/cs/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/cs/aspose.slides/presentation/notes_size/) | Vrací objekt velikosti snímků poznámek.<br/>            Pouze pro čtení [`INotesSize`](/slides/python-net/cs/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/cs/aspose.slides/presentation/layout_slides/) | Vrací seznam všech snímků rozvržení, které jsou definovány v prezentaci.<br/>            Pouze pro čtení [`IGlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/cs/aspose.slides/presentation/masters/) | Vrací seznam všech hlavních snímků, které jsou definovány v prezentaci.<br/>            Pouze pro čtení [`IMasterSlideCollection`](/slides/python-net/cs/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/cs/aspose.slides/presentation/master_notes_slide_manager/) | Vrací správce hlavních poznámek.<br/>            Pouze pro čtení [`IMasterNotesSlideManager`](/slides/python-net/cs/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/cs/aspose.slides/presentation/master_handout_slide_manager/) | Vrací správce hlavních přehledů.<br/>            Pouze pro čtení [`IMasterHandoutSlideManager`](/slides/python-net/cs/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/cs/aspose.slides/presentation/fonts_manager/) | Vrací správce fontů.<br/>            Pouze pro čtení [`IFontsManager`](/slides/python-net/cs/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/cs/aspose.slides/presentation/default_text_style/) | Vrací výchozí styl textu pro tvary.<br/>            Pouze pro čtení [`ITextStyle`](/slides/python-net/cs/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/cs/aspose.slides/presentation/comment_authors/) | Vrací kolekci autorů komentářů.<br/>            Pouze pro čtení [`ICommentAuthorCollection`](/slides/python-net/cs/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/cs/aspose.slides/presentation/document_properties/) | Vrací objekt DocumentProperties, který obsahuje standardní a uživatelské vlastnosti dokumentu.<br/>            Pouze pro čtení [`IDocumentProperties`](/slides/python-net/cs/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/cs/aspose.slides/presentation/images/) | Vrací kolekci všech obrázků v prezentaci.<br/>            Pouze pro čtení [`IImageCollection`](/slides/python-net/cs/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/cs/aspose.slides/presentation/audios/) | Vrací kolekci všech vložených audio souborů v prezentaci.<br/>            Pouze pro čtení [`IAudioCollection`](/slides/python-net/cs/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/cs/aspose.slides/presentation/videos/) | Vrací kolekci všech vložených video souborů v prezentaci.<br/>            Pouze pro čtení [`IVideoCollection`](/slides/python-net/cs/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/cs/aspose.slides/presentation/slide_show_settings/) | Vrací nastavení prezentace pro slideshow. |
| [`digital_signatures`](/slides/python-net/cs/aspose.slides/presentation/digital_signatures/) | Vrací kolekci podpisů použitých k podepsání prezentace.<br/>            Pouze pro čtení [`IDigitalSignatureCollection`](/slides/python-net/cs/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/presentation/custom_data/) | Vrací uživatelská data prezentace.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/cs/aspose.slides/presentation/all_custom_xml_parts/) | Vrací všechny uživatelské datové části v prezentaci.<br/>            Pouze pro čtení [`ICustomXmlPart`](/slides/python-net/cs/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/cs/aspose.slides/presentation/vba_project/) | Získá nebo nastaví projekt VBA s makry prezentace.<br/>            Číst/Zapisovat [`IVbaProject`](/slides/python-net/cs/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/presentation/hyperlink_queries/) | Poskytuje snadný přístup ke všem hyperodkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozvržení a poznámkových snímcích).<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/cs/aspose.slides/presentation/view_properties/) | Získá celoprezentační vlastnosti zobrazení.<br/>            Pouze pro čtení [`IViewProperties`](/slides/python-net/cs/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/cs/aspose.slides/presentation/first_slide_number/) | Zastupuje číslo prvního snímku v prezentaci |
| [`sensitivity_labels`](/slides/python-net/cs/aspose.slides/presentation/sensitivity_labels/) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace.<br/>            Pouze pro čtení [`ISensitivityLabelCollection`](/slides/python-net/cs/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/cs/aspose.slides/presentation/source_format/) | Vrací informace o formátu, ze kterého byla prezentace načtena.<br/>            Pouze pro čtení [`SourceFormat`](/slides/python-net/cs/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/cs/aspose.slides/presentation/master_theme/) | Vrací hlavní motiv.<br/>            Pouze pro čtení [`IMasterTheme`](/slides/python-net/cs/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/cs/aspose.slides/presentation/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do souboru ve specifikovaném formátu. |
| [`save(self, stream, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu. |
| [`save(self, fname, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dalšími možnostmi. |
| [`save(self, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Uloží všechny snímky prezentace do sady souborů představujících XAML značkování. |
| [`save(self, fname, slides, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Uloží určené snímky prezentace do souboru ve specifikovaném formátu při zachování číslování stránek. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží určené snímky prezentace do souboru ve specifikovaném formátu při zachování číslování stránek. |
| [`save(self, stream, slides, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu při zachování číslování stránek. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu při zachování číslování stránek. |
| [`get_images(self, options)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Vrací objekty Image pro všechny snímky prezentace. |
| [`get_images(self, options, slides)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Vrací objekty Thumbnail Image pro určené snímky prezentace. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, image_size)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Vrací objekty Thumbnail Image pro všechny snímky prezentace se specifikovanou velikostí. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Vrací objekty Thumbnail Image pro určené snímky prezentace se specifikovanou velikostí. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/cs/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/cs/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [`get_slide_by_id(self, id)`](/slides/python-net/cs/aspose.slides/presentation/get_slide_by_id/#int) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/presentation/join_portions_with_same_formatting/#) | Spojí běhy s stejným formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/cs/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/cs/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/cs/aspose.slides/presentation/replace_regex/#str-str) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/cs/aspose.slides/presentation/refresh_charts_data/#bool) | Znovu načte data všech grafů v prezentaci z jejich zdrojových sešitů. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)