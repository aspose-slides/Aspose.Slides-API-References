---
title: Presentation class
second_title: Aspose.Slides pro Python - reference .NET API
description: 
type: docs
url: /cs/aspose.slides/presentation/
---
## Presentation třída

Reprezentuje prezentaci Microsoft PowerPoint.

Typ Presentation exponuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#) | Tento konstruktor vytvoří novou prezentaci od nuly.<br/>            Vytvořená prezentace má jeden prázdný snímek. |
| [`__init__(self, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#loadoptions) | Tento konstruktor vytvoří novou prezentaci od nuly.<br/>            Vytvořená prezentace má jeden prázdný snímek. |
| [`__init__(self, stream)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#iorawiobase) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace Presentation. |
| [`__init__(self, file)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#str) | Tento konstruktor získá cestu k zdrojovému souboru, ze které<br/>             jsou načteny obsahy prezentace Presentation. |
| [`__init__(self, file, load_options)`](/slides/python-net/cs/aspose.slides/presentation/__init__/#str-loadoptions) | Tento konstruktor získá cestu k zdrojovému souboru, ze které<br/>            jsou načteny obsahy prezentace Presentation. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`current_date_time`](/slides/python-net/cs/aspose.slides/presentation/current_date_time/) | Vrátí nebo nastaví datum a čas, které nahradí obsah polí datetime.<br/>            Čas vytvoření tohoto objektu Presentation ve výchozím nastavení.<br/>            Čtení/zápis **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/presentation/header_footer_manager/) | Vrátí aktuální správce HeaderFooter.<br/>            Pouze pro čtení [`IPresentationHeaderFooterManager`](/slides/python-net/cs/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/cs/aspose.slides/presentation/protection_manager/) | Získá správce oprávnění pro tuto prezentaci.<br/>            Pouze pro čtení [`IProtectionManager`](/slides/python-net/cs/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/cs/aspose.slides/presentation/slides/) | Vrátí seznam všech snímků definovaných v prezentaci.<br/cs/>            Pouze pro čtení [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/cs/aspose.slides/presentation/sections/) | Vrátí seznam všech sekcí snímků definovaných v prezentaci.<br/>            Pouze pro čtení [`ISectionCollection`](/slides/python-net/cs/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/cs/aspose.slides/presentation/slide_size/) | Vrátí objekt velikosti snímku.<br/>            Pouze pro čtení [`ISlideSize`](/slides/python-net/cs/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/cs/aspose.slides/presentation/notes_size/) | Vrátí objekt velikosti snímku poznámek.<br/>            Pouze pro čtení [`INotesSize`](/slides/python-net/cs/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/cs/aspose.slides/presentation/layout_slides/) | Vrátí seznam všech snímků rozložení definovaných v prezentaci.<br/>            Pouze pro čtení [`IGlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/cs/aspose.slides/presentation/masters/) | Vrátí seznam všech hlavních snímků definovaných v prezentaci.<br/>            Pouze pro čtení [`IMasterSlideCollection`](/slides/python-net/cs/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/cs/aspose.slides/presentation/master_notes_slide_manager/) | Vrátí správce hlavních poznámek.<br/>            Pouze pro čtení [`IMasterNotesSlideManager`](/slides/python-net/cs/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/cs/aspose.slides/presentation/master_handout_slide_manager/) | Vrátí správce hlavních výstřižků.<br/>            Pouze pro čtení [`IMasterHandoutSlideManager`](/slides/python-net/cs/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/cs/aspose.slides/presentation/fonts_manager/) | Vrátí správce fontů.<br/>            Pouze pro čtení [`IFontsManager`](/slides/python-net/cs/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/cs/aspose.slides/presentation/default_text_style/) | Vrátí výchozí styl textu pro tvary.<br/>            Pouze pro čtení [`ITextStyle`](/slides/python-net/cs/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/cs/aspose.slides/presentation/comment_authors/) | Vrátí kolekci autorů komentářů.<br/>            Pouze pro čtení [`ICommentAuthorCollection`](/slides/python-net/cs/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/cs/aspose.slides/presentation/document_properties/) | Vrátí objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu.<br/>            Pouze pro čtení [`IDocumentProperties`](/slides/python-net/cs/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/cs/aspose.slides/presentation/images/) | Vrátí kolekci všech obrázků v prezentaci.<br/>            Pouze pro čtení [`IImageCollection`](/slides/python-net/cs/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/cs/aspose.slides/presentation/audios/) | Vrátí kolekci všech vložených audio souborů v prezentaci.<br/>            Pouze pro čtení [`IAudioCollection`](/slides/python-net/cs/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/cs/aspose.slides/presentation/videos/) | Vrátí kolekci všech vložených video souborů v prezentaci.<br/>            Pouze pro čtení [`IVideoCollection`](/slides/python-net/cs/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/cs/aspose.slides/presentation/slide_show_settings/) | Vrátí nastavení prezentace pro promítání. |
| [`digital_signatures`](/slides/python-net/cs/aspose.slides/presentation/digital_signatures/) | Vrátí kolekci podpisů použité k podepsání prezentace.<br/>            Pouze pro čtení [`IDigitalSignatureCollection`](/slides/python-net/cs/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/presentation/custom_data/) | Vrátí vlastní data prezentace.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/cs/aspose.slides/presentation/all_custom_xml_parts/) | Vrátí všechny části vlastních dat v prezentaci.<br/>            Pouze pro čtení [`ICustomXmlPart`](/slides/python-net/cs/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/cs/aspose.slides/presentation/vba_project/) | Získá nebo nastaví projekt VBA s makry prezentace.<br/>            Čtení/zápis [`IVbaProject`](/slides/python-net/cs/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/presentation/hyperlink_queries/) | Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení, poznámkových snímcích).<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/cs/aspose.slides/presentation/view_properties/) | Získá vlastnosti zobrazení na úrovni celé prezentace.<br/>            Pouze pro čtení [`IViewProperties`](/slides/python-net/cs/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/cs/aspose.slides/presentation/first_slide_number/) | Reprezentuje číslo prvního snímku v prezentaci |
| [`sensitivity_labels`](/slides/python-net/cs/aspose.slides/presentation/sensitivity_labels/) | Vrátí kolekci štítků citlivosti aplikovaných na dokument prezentace.<br/>            Pouze pro čtení [`ISensitivityLabelCollection`](/slides/python-net/cs/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/cs/aspose.slides/presentation/source_format/) | Vrátí informace o tom, z jakého formátu byla prezentace načtena.<br/>            Pouze pro čtení [`SourceFormat`](/slides/python-net/cs/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/cs/aspose.slides/presentation/master_theme/) | Vrátí hlavní téma.<br/>            Pouze pro čtení [`IMasterTheme`](/slides/python-net/cs/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/cs/aspose.slides/presentation/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do souboru ve specifikovaném formátu. |
| [`save(self, stream, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu. |
| [`save(self, fname, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dodatečnými možnostmi. |
| [`save(self, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Uloží všechny snímky prezentace do sady souborů představujících XAML značkování. |
| [`save(self, fname, slides, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Uloží určené snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží určené snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek. |
| [`save(self, stream, slides, format)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/cs/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží určené snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [`get_images(self, options)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Vrátí objekty Image pro všechny snímky prezentace. |
| [`get_images(self, options, slides)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Vrátí objekty Thumbnail Image pro určené snímky prezentace. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Vrátí objekty Thumbnail Image pro všechny snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Vrátí objekty Thumbnail Image pro určené snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, image_size)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Vrátí objekty Thumbnail Image pro všechny snímky prezentace se specifikovanou velikostí. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/cs/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Vrátí objekty Thumbnail Image pro určené snímky prezentace se specifikovanou velikostí. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/cs/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Zvýrazní všechny shody ukázkového textu zvolenou barvou. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/cs/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Zvýrazní všechny shody ukázkového textu zvolenou barvou. |
| [`get_slide_by_id(self, id)`](/slides/python-net/cs/aspose.slides/presentation/get_slide_by_id/#int) | Vrátí Slide, MasterSlide nebo LayoutSlide podle Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/presentation/join_portions_with_same_formatting/#) | Spojí běhy s identickým formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/cs/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Zvýrazní všechny shody regulárního výrazu zvolenou barvou. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/cs/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/cs/aspose.slides/presentation/replace_regex/#str-str) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)