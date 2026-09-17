---
title: IPresentation class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ipresentation/
---
## IPresentation classe

Document de présentation

Le type IPresentation expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/fr/aspose.slides/ipresentation/current_date_time/) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime.<br/>            Heure de création de cet objet Presentation par défaut.<br/>            Lecture/écriture **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/ipresentation/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter de la présentation.<br/>            Lecture seule [`IPresentationHeaderFooterManager`](/slides/python-net/fr/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/fr/aspose.slides/ipresentation/protection_manager/) | Obtient le gestionnaire des autorisations pour cette présentation.<br/>            Lecture seule [`IProtectionManager`](/slides/python-net/fr/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/fr/aspose.slides/ipresentation/slides/) | Renvoie une liste de toutes les diapositives définies dans la présentation.<br/fr/>            Lecture seule [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/fr/aspose.slides/ipresentation/sections/) | Renvoie une liste de toutes les sections de diapositives définies dans la présentation.<br/>            Lecture seule [`ISectionCollection`](/slides/python-net/fr/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/fr/aspose.slides/ipresentation/slide_size/) | Renvoie l'objet de taille de diapositive.<br/>            Lecture seule [`ISlideSize`](/slides/python-net/fr/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/fr/aspose.slides/ipresentation/notes_size/) | Renvoie l'objet de taille des diapositives de notes.<br/>            Lecture seule [`INotesSize`](/slides/python-net/fr/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/fr/aspose.slides/ipresentation/layout_slides/) | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation.<br/>            Lecture seule [`IGlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/fr/aspose.slides/ipresentation/masters/) | Renvoie une liste de toutes les diapositives maîtres définies dans la présentation.<br/>            Lecture seule [`IMasterSlideCollection`](/slides/python-net/fr/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/fr/aspose.slides/ipresentation/master_notes_slide_manager/) | Renvoie le gestionnaire du maître de notes.<br/>            Lecture seule [`IMasterNotesSlideManager`](/slides/python-net/fr/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/fr/aspose.slides/ipresentation/master_handout_slide_manager/) | Renvoie le gestionnaire du maître de fascicule.<br/>            Lecture seule [`IMasterHandoutSlideManager`](/slides/python-net/fr/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/fr/aspose.slides/ipresentation/fonts_manager/) | Renvoie le gestionnaire des polices.<br/>            Lecture seule [`IFontsManager`](/slides/python-net/fr/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/fr/aspose.slides/ipresentation/default_text_style/) | Renvoie le style de texte par défaut pour les formes.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/fr/aspose.slides/ipresentation/comment_authors/) | Renvoie la collection d'auteurs de commentaires.<br/>            Lecture seule [`ICommentAuthorCollection`](/slides/python-net/fr/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/fr/aspose.slides/ipresentation/document_properties/) | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées.<br/>            Lecture seule [`IDocumentProperties`](/slides/python-net/fr/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/fr/aspose.slides/ipresentation/images/) | Renvoie la collection de toutes les images de la présentation.<br/>            Lecture seule [`IImageCollection`](/slides/python-net/fr/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/fr/aspose.slides/ipresentation/audios/) | Renvoie la collection de tous les fichiers audio embarqués dans la présentation.<br/>            Lecture seule [`IAudioCollection`](/slides/python-net/fr/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/fr/aspose.slides/ipresentation/videos/) | Renvoie la collection de tous les fichiers vidéo embarqués dans la présentation.<br/>            Lecture seule [`IVideoCollection`](/slides/python-net/fr/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/ipresentation/custom_data/) | Renvoie les données personnalisées de la présentation.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/fr/aspose.slides/ipresentation/vba_project/) | Obtient le projet VBA contenant les macros de la présentation.<br/>            Lecture/écriture [`IVbaProject`](/slides/python-net/fr/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/fr/aspose.slides/ipresentation/source_format/) | Renvoie des informations sur le format à partir duquel la présentation a été chargée.<br/>            Lecture seule [`IPresentation.source_format`](/slides/python-net/fr/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/fr/aspose.slides/ipresentation/master_theme/) | Renvoie le thème maître de la présentation.<br/>            Lecture seule [`IMasterTheme`](/slides/python-net/fr/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/ipresentation/hyperlink_queries/) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes).<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/fr/aspose.slides/ipresentation/view_properties/) | Obtient les propriétés de vue globale de la présentation.<br/>            Lecture seule [`IViewProperties`](/slides/python-net/fr/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/fr/aspose.slides/ipresentation/first_slide_number/) | Représente le numéro de la première diapositive dans la présentation.<br/>            Lecture/écriture **int**. |
| [`all_custom_xml_parts`](/slides/python-net/fr/aspose.slides/ipresentation/all_custom_xml_parts/) | Renvoie toutes les parties de données personnalisées dans la présentation.<br/>            Lecture seule [`ICustomXmlPart`](/slides/python-net/fr/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/fr/aspose.slides/ipresentation/digital_signatures/) | Renvoie la collection de signatures utilisées pour signer la présentation.<br/>            Lecture seule [`IDigitalSignatureCollection`](/slides/python-net/fr/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/fr/aspose.slides/ipresentation/sensitivity_labels/) | Renvoie la collection d'étiquettes de sensibilité appliquées au document de présentation.<br/>            Lecture seule [`ISensitivityLabelCollection`](/slides/python-net/fr/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/fr/aspose.slides/ipresentation/presentation/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié. |
| [`save(self, stream, format)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [`save(self, fname, format, options)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
| [`save(self, stream, format, options)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [`save(self, fname, slides, format)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |
| [`save(self, stream, slides, format)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [`save(self, options)`](/slides/python-net/fr/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [`get_images(self, options)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation. |
| [`get_images(self, options, slides)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Renvoie des objets Bitmap miniature pour les diapositives spécifiées d'une présentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [`get_images(self, options, image_size)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec la taille spécifiée. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/fr/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec la taille spécifiée. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fr/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fr/aspose.slides/ipresentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [`get_slide_by_id(self, id)`](/slides/python-net/fr/aspose.slides/ipresentation/get_slide_by_id/#int) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fr/aspose.slides/ipresentation/highlight_regex/#str-asposepydrawingcolor) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fr/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fr/aspose.slides/ipresentation/replace_regex/#str-str) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)