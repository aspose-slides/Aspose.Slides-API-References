---
title: Presentation class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/presentation/
---
## classe Presentation

Représente une présentation Microsoft PowerPoint.

Le type Presentation expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#) | Ce constructeur crée une nouvelle présentation à partir de zéro.<br/>            La présentation créée possède une diapositive vide. |
| [`__init__(self, load_options)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#loadoptions) | Ce constructeur crée une nouvelle présentation à partir de zéro.<br/>            La présentation créée possède une diapositive vide. |
| [`__init__(self, stream)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#iorawiobase) | Ce constructeur est le mécanisme principal pour lire une Presentation existante. |
| [`__init__(self, stream, load_options)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Ce constructeur est le mécanisme principal pour lire une Presentation existante. |
| [`__init__(self, file)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#str) | Ce constructeur obtient le chemin du fichier source à partir duquel<br/>             le contenu de la Presentation est lu. |
| [`__init__(self, file, load_options)`](/slides/python-net/fr/aspose.slides/presentation/__init__/#str-loadoptions) | Ce constructeur obtient le chemin du fichier source à partir duquel<br/>            le contenu de la Presentation est lu. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/fr/aspose.slides/presentation/current_date_time/) | Renvoie ou définit la date et l’heure qui remplaceront le contenu des champs datetime.<br/>            Heure de création de cet objet Presentation par défaut.<br/>            Lecture/écriture **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/fr/aspose.slides/presentation/header_footer_manager/) | Renvoie le gestionnaire HeaderFooter actuel.<br/>            Lecture seule [`IPresentationHeaderFooterManager`](/slides/python-net/fr/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/fr/aspose.slides/presentation/protection_manager/) | Obtient le gestionnaire des autorisations pour cette présentation.<br/>            Lecture seule [`IProtectionManager`](/slides/python-net/fr/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/fr/aspose.slides/presentation/slides/) | Renvoie une liste de toutes les diapositives définies dans la présentation.<br/fr/>            Lecture seule [`ISlideCollection`](/slides/python-net/fr/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/fr/aspose.slides/presentation/sections/) | Renvoie une liste de toutes les sections de diapositives définies dans la présentation.<br/>            Lecture seule [`ISectionCollection`](/slides/python-net/fr/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/fr/aspose.slides/presentation/slide_size/) | Renvoie l’objet taille de diapositive.<br/>            Lecture seule [`ISlideSize`](/slides/python-net/fr/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/fr/aspose.slides/presentation/notes_size/) | Renvoie l’objet taille de diapositive de notes.<br/>            Lecture seule [`INotesSize`](/slides/python-net/fr/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/fr/aspose.slides/presentation/layout_slides/) | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation.<br/>            Lecture seule [`IGlobalLayoutSlideCollection`](/slides/python-net/fr/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/fr/aspose.slides/presentation/masters/) | Renvoie une liste de toutes les diapositives maîtres définies dans la présentation.<br/>            Lecture seule [`IMasterSlideCollection`](/slides/python-net/fr/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/fr/aspose.slides/presentation/master_notes_slide_manager/) | Renvoie le gestionnaire de notes maître.<br/>            Lecture seule [`IMasterNotesSlideManager`](/slides/python-net/fr/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/fr/aspose.slides/presentation/master_handout_slide_manager/) | Renvoie le gestionnaire de version imprimable maître.<br/>            Lecture seule [`IMasterHandoutSlideManager`](/slides/python-net/fr/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/fr/aspose.slides/presentation/fonts_manager/) | Renvoie le gestionnaire de polices.<br/>            Lecture seule [`IFontsManager`](/slides/python-net/fr/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/fr/aspose.slides/presentation/default_text_style/) | Renvoie le style de texte par défaut pour les formes.<br/>            Lecture seule [`ITextStyle`](/slides/python-net/fr/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/fr/aspose.slides/presentation/comment_authors/) | Renvoie la collection des auteurs de commentaires.<br/>            Lecture seule [`ICommentAuthorCollection`](/slides/python-net/fr/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/fr/aspose.slides/presentation/document_properties/) | Renvoie l’objet DocumentProperties qui contient les propriétés de document standard et personnalisées.<br/>            Lecture seule [`IDocumentProperties`](/slides/python-net/fr/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/fr/aspose.slides/presentation/images/) | Renvoie la collection de toutes les images de la présentation.<br/>            Lecture seule [`IImageCollection`](/slides/python-net/fr/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/fr/aspose.slides/presentation/audios/) | Renvoie la collection de tous les fichiers audio intégrés dans la présentation.<br/>            Lecture seule [`IAudioCollection`](/slides/python-net/fr/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/fr/aspose.slides/presentation/videos/) | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation.<br/>            Lecture seule [`IVideoCollection`](/slides/python-net/fr/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/fr/aspose.slides/presentation/slide_show_settings/) | Renvoie les paramètres du diaporama pour la présentation. |
| [`digital_signatures`](/slides/python-net/fr/aspose.slides/presentation/digital_signatures/) | Renvoie la collection des signatures utilisées pour signer la présentation.<br/>            Lecture seule [`IDigitalSignatureCollection`](/slides/python-net/fr/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/fr/aspose.slides/presentation/custom_data/) | Renvoie les données personnalisées de la présentation.<br/>            Lecture seule [`ICustomData`](/slides/python-net/fr/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/fr/aspose.slides/presentation/all_custom_xml_parts/) | Renvoie toutes les parties de données personnalisées dans la présentation.<br/>            Lecture seule [`ICustomXmlPart`](/slides/python-net/fr/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/fr/aspose.slides/presentation/vba_project/) | Obtient ou définit le projet VBA avec les macros de la présentation.<br/>            Lecture/écriture [`IVbaProject`](/slides/python-net/fr/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/fr/aspose.slides/presentation/hyperlink_queries/) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les diapositives maître, de mise en page ou de notes).<br/>            Lecture seule [`IHyperlinkQueries`](/slides/python-net/fr/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/fr/aspose.slides/presentation/view_properties/) | Obtient les propriétés de vue globales de la présentation.<br/>            Lecture seule [`IViewProperties`](/slides/python-net/fr/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/fr/aspose.slides/presentation/first_slide_number/) | Représente le numéro de la première diapositive dans la présentation |
| [`sensitivity_labels`](/slides/python-net/fr/aspose.slides/presentation/sensitivity_labels/) | Renvoie la collection des étiquettes de sensibilité appliquées au document de la présentation.<br/>            Lecture seule [`ISensitivityLabelCollection`](/slides/python-net/fr/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/fr/aspose.slides/presentation/source_format/) | Renvoie les informations sur le format à partir duquel la présentation a été chargée.<br/>            Lecture seule [`SourceFormat`](/slides/python-net/fr/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/fr/aspose.slides/presentation/master_theme/) | Renvoie le thème maître.<br/>            Lecture seule [`IMasterTheme`](/slides/python-net/fr/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/fr/aspose.slides/presentation/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/fr/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié. |
| [`save(self, stream, format)`](/slides/python-net/fr/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié. |
| [`save(self, fname, format, options)`](/slides/python-net/fr/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/fr/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
| [`save(self, options)`](/slides/python-net/fr/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [`save(self, fname, slides, format)`](/slides/python-net/fr/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié en conservant les numéros de page. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/fr/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié en conservant les numéros de page. |
| [`save(self, stream, slides, format)`](/slides/python-net/fr/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié en conservant les numéros de page. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/fr/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié en conservant les numéros de page. |
| [`get_images(self, options)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Renvoie des objets Image pour toutes les diapositives d’une présentation. |
| [`get_images(self, options, slides)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec mise à l’échelle personnalisée. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec mise à l’échelle personnalisée. |
| [`get_images(self, options, image_size)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec taille spécifiée. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/fr/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec taille spécifiée. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/fr/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Met en évidence toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/fr/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Met en évidence toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
| [`get_slide_by_id(self, id)`](/slides/python-net/fr/aspose.slides/presentation/get_slide_by_id/#int) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/fr/aspose.slides/presentation/join_portions_with_same_formatting/#) | Fusionne les segments avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/fr/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Met en évidence toutes les correspondances de l’expression régulière avec la couleur spécifiée. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/fr/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/fr/aspose.slides/presentation/replace_regex/#str-str) | Remplace toutes les correspondances de l’expression régulière par la chaîne spécifiée. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)