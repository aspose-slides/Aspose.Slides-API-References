---
title: IPresentation class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ipresentation/
---
## třída IPresentation

Dokument prezentace

Typ IPresentation poskytuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/cs/aspose.slides/ipresentation/current_date_time/) | Vrací nebo nastavuje datum a čas, které nahradí obsah polí typu datetime.<br/>            Výchozí čas vytvoření tohoto objektu Presentation.<br/>            Čtení/zápis **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/ipresentation/header_footer_manager/) | Vrací správce HeaderFooter prezentace.<br/>            Pouze pro čtení [`IPresentationHeaderFooterManager`](/slides/python-net/cs/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/cs/aspose.slides/ipresentation/protection_manager/) | Získá správce oprávnění pro tuto prezentaci. <br/>            Pouze pro čtení [`IProtectionManager`](/slides/python-net/cs/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/cs/aspose.slides/ipresentation/slides/) | Vrací seznam všech snímků definovaných v prezentaci.<br/cs/>            Pouze pro čtení [`ISlideCollection`](/slides/python-net/cs/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/cs/aspose.slides/ipresentation/sections/) | Vrací seznam všech sekcí snímků definovaných v prezentaci.<br/>            Pouze pro čtení [`ISectionCollection`](/slides/python-net/cs/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/cs/aspose.slides/ipresentation/slide_size/) | Vrací objekt velikosti snímku.<br/>            Pouze pro čtení [`ISlideSize`](/slides/python-net/cs/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/cs/aspose.slides/ipresentation/notes_size/) | Vrací objekt velikosti snímku poznámek.<br/>            Pouze pro čtení [`INotesSize`](/slides/python-net/cs/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/cs/aspose.slides/ipresentation/layout_slides/) | Vrací seznam všech snímků rozvržení definovaných v prezentaci.<br/>            Pouze pro čtení [`IGlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/cs/aspose.slides/ipresentation/masters/) | Vrací seznam všech hlavních (master) snímků definovaných v prezentaci.<br/>            Pouze pro čtení [`IMasterSlideCollection`](/slides/python-net/cs/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/cs/aspose.slides/ipresentation/master_notes_slide_manager/) | Vrací správce hlavních poznámek.<br/>            Pouze pro čtení [`IMasterNotesSlideManager`](/slides/python-net/cs/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/cs/aspose.slides/ipresentation/master_handout_slide_manager/) | Vrací správce hlavních výstřižků.<br/>            Pouze pro čtení [`IMasterHandoutSlideManager`](/slides/python-net/cs/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/cs/aspose.slides/ipresentation/fonts_manager/) | Vrací správce písem.<br/>            Pouze pro čtení [`IFontsManager`](/slides/python-net/cs/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/cs/aspose.slides/ipresentation/default_text_style/) | Vrací výchozí styl textu pro tvary.<br/>            Pouze pro čtení [`ITextStyle`](/slides/python-net/cs/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/cs/aspose.slides/ipresentation/comment_authors/) | Vrací kolekci autorů komentářů.<br/>            Pouze pro čtení [`ICommentAuthorCollection`](/slides/python-net/cs/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/cs/aspose.slides/ipresentation/document_properties/) | Vrací objekt DocumentProperties, který obsahuje standardní a uživatelské vlastnosti dokumentu.<br/>            Pouze pro čtení [`IDocumentProperties`](/slides/python-net/cs/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/cs/aspose.slides/ipresentation/images/) | Vrací kolekci všech obrázků v prezentaci.<br/>            Pouze pro čtení [`IImageCollection`](/slides/python-net/cs/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/cs/aspose.slides/ipresentation/audios/) | Vrací kolekci všech vložených zvukových souborů v prezentaci.<br/>            Pouze pro čtení [`IAudioCollection`](/slides/python-net/cs/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/cs/aspose.slides/ipresentation/videos/) | Vrací kolekci všech vložených video souborů v prezentaci.<br/>            Pouze pro čtení [`IVideoCollection`](/slides/python-net/cs/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/cs/aspose.slides/ipresentation/custom_data/) | Vrací vlastní data prezentace.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/cs/aspose.slides/ipresentation/vba_project/) | Získá projekt VBA s makry prezentace.<br/>            Čtení/zápis [`IVbaProject`](/slides/python-net/cs/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/cs/aspose.slides/ipresentation/source_format/) | Vrací informaci o formátu, ze kterého byla prezentace načtena.<br/>            Pouze pro čtení [`IPresentation.source_format`](/slides/python-net/cs/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/cs/aspose.slides/ipresentation/master_theme/) | Vrací hlavní téma prezentace.<br/>            Pouze pro čtení [`IMasterTheme`](/slides/python-net/cs/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/ipresentation/hyperlink_queries/) | Poskytuje snadný přístup ke všem hyperodkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozvržení ani poznámkách).<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/cs/aspose.slides/ipresentation/view_properties/) | Získá vlastnosti zobrazení platné pro celou prezentaci.<br/>            Pouze pro čtení [`IViewProperties`](/slides/python-net/cs/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/cs/aspose.slides/ipresentation/first_slide_number/) | Reprezentuje číslo prvního snímku v prezentaci.<br/>            Čtení/zápis **int**. |
| [`all_custom_xml_parts`](/slides/python-net/cs/aspose.slides/ipresentation/all_custom_xml_parts/) | Vrací všechny vlastní datové části v prezentaci.<br/>            Pouze pro čtení [`ICustomXmlPart`](/slides/python-net/cs/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/cs/aspose.slides/ipresentation/digital_signatures/) | Vrací kolekci podpisů použitých k podepsání prezentace.<br/>            Pouze pro čtení [`IDigitalSignatureCollection`](/slides/python-net/cs/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/cs/aspose.slides/ipresentation/sensitivity_labels/) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace.<br/>            Pouze pro čtení [`ISensitivityLabelCollection`](/slides/python-net/cs/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/cs/aspose.slides/ipresentation/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu. |
| [`save(self, stream, format)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu. |
| [`save(self, fname, format, options)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu a s dalšími možnostmi. |
| [`save(self, stream, format, options)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu a s dalšími možnostmi. |
| [`save(self, fname, slides, format)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Uloží vybrané snímky prezentace do souboru ve zvoleném formátu. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží vybrané snímky prezentace do souboru ve zvoleném formátu. |
| [`save(self, stream, slides, format)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Uloží vybrané snímky prezentace do proudu ve zvoleném formátu. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Uloží vybrané snímky prezentace do proudu ve zvoleném formátu. |
| [`save(self, options)`](/slides/python-net/cs/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Uloží všechny snímky prezentace do sady souborů představujících značkování XAML. |
| [`get_images(self, options)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Vrací objekt náhledu (Thumbnail Image) pro všechny snímky prezentace. |
| [`get_images(self, options, slides)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Vrací objekt náhledu (Thumbnail Bitmap) pro vybrané snímky prezentace. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Vrací objekt náhledu (Thumbnail Image) pro všechny snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Vrací objekt náhledu (Thumbnail Image) pro vybrané snímky prezentace s vlastním měřítkem. |
| [`get_images(self, options, image_size)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Vrací objekt náhledu (Thumbnail Image) pro všechny snímky prezentace se zadanou velikostí. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/cs/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Vrací objekt náhledu (Thumbnail Image) pro vybrané snímky prezentace se zadanou velikostí. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/cs/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Zvýrazní všechny výskyty ukázkového textu zadanou barvou. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/cs/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Zvýrazní všechny výskyty ukázkového textu zadanou barvou. |
| [`get_slide_by_id(self, id)`](/slides/python-net/cs/aspose.slides/ipresentation/get_slide_by_id/#int) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Spojí úseky se stejným formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/cs/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Zvýrazní všechny výskyty regulárního výrazu zadanou barvou. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/cs/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/cs/aspose.slides/ipresentation/replace_regex/#str-str) | Nahradí všechny výskyty regulárního výrazu zadaným řetězcem. |

### Viz také
* module [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)