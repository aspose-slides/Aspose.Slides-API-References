---
title: IDocumentProperties class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/idocumentproperties/
---
## IDocumentProperties classe

Représente les propriétés d'une présentation.

Le type IDocumentProperties expose les membres suivants :

## Propriété

| Propriété | Description |
| :- | :- |
| [`app_version`](/slides/python-net/fr/aspose.slides/idocumentproperties/app_version/) | Returns the app version.<br/>            Read-only **str**. |
| [`name_of_application`](/slides/python-net/fr/aspose.slides/idocumentproperties/name_of_application/) | Renvoie ou définit le nom de l'application.<br/>            Lecture/écriture **str**. |
| [`company`](/slides/python-net/fr/aspose.slides/idocumentproperties/company/) | Renvoie ou définit la propriété de l'entreprise.<br/>            Lecture/écriture **str**. |
| [`manager`](/slides/python-net/fr/aspose.slides/idocumentproperties/manager/) | Renvoie ou définit la propriété du gestionnaire.<br/>            Lecture/écriture **str**. |
| [`presentation_format`](/slides/python-net/fr/aspose.slides/idocumentproperties/presentation_format/) | Renvoie ou définit le format prévu d'une présentation.<br/>            Lecture/écriture **str**. |
| [`shared_doc`](/slides/python-net/fr/aspose.slides/idocumentproperties/shared_doc/) | Détermine si la présentation est partagée entre plusieurs personnes.<br/>            Lecture/écriture **bool**. |
| [`application_template`](/slides/python-net/fr/aspose.slides/idocumentproperties/application_template/) | Renvoie ou définit le modèle d'une application.<br/>            Lecture/écriture **str**. |
| [`total_editing_time`](/slides/python-net/fr/aspose.slides/idocumentproperties/total_editing_time/) | Temps total d'édition d'une présentation.<br/>            Lecture/écriture **System.TimeSpan**. |
| [`title`](/slides/python-net/fr/aspose.slides/idocumentproperties/title/) | Renvoie ou définit le titre d'une présentation.<br/>            Lecture/écriture **str**. |
| [`subject`](/slides/python-net/fr/aspose.slides/idocumentproperties/subject/) | Renvoie ou définit le sujet d'une présentation.<br/>            Lecture/écriture **str**. |
| [`author`](/slides/python-net/fr/aspose.slides/idocumentproperties/author/) | Renvoie ou définit l'auteur d'une présentation.<br/>            Lecture/écriture **str**. |
| [`keywords`](/slides/python-net/fr/aspose.slides/idocumentproperties/keywords/) | Renvoie ou définit les mots-clés d'une présentation.<br/>            Lecture/écriture **str**. |
| [`comments`](/slides/python-net/fr/aspose.slides/idocumentproperties/comments/) | Renvoie ou définit les commentaires d'une présentation.<br/>            Lecture/écriture **str**. |
| [`category`](/slides/python-net/fr/aspose.slides/idocumentproperties/category/) | Renvoie ou définit la catégorie d'une présentation.<br/>            Lecture/écriture **str**. |
| [`created_time`](/slides/python-net/fr/aspose.slides/idocumentproperties/created_time/) | Renvoie la date à laquelle une présentation a été créée.<br/>            Les valeurs sont en UTC.<br/>            Lecture/écriture **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/fr/aspose.slides/idocumentproperties/last_saved_time/) | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois.<br/>            Les valeurs sont en UTC.<br/>            Lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). <br/>            Peut être modifié via l'instance DocumentProperties renvoyée par la méthode [`IPresentationInfo.read_document_properties`](/slides/python-net/fr/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Veuillez consulter l'exemple dans le résumé de la méthode **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/fr/aspose.slides/idocumentproperties/last_printed/) | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois.<br/>            Lecture/écriture **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/fr/aspose.slides/idocumentproperties/last_saved_by/) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation.<br/>            Lecture/écriture **str**. |
| [`revision_number`](/slides/python-net/fr/aspose.slides/idocumentproperties/revision_number/) | Renvoie ou définit le numéro de révision de la présentation.<br/>            Lecture/écriture **int**. |
| [`content_status`](/slides/python-net/fr/aspose.slides/idocumentproperties/content_status/) | Renvoie ou définit le statut du contenu d'une présentation.<br/>            Lecture/écriture **str**. |
| [`content_type`](/slides/python-net/fr/aspose.slides/idocumentproperties/content_type/) | Renvoie ou définit le type de contenu d'une présentation.<br/>            Lecture/écriture **str**. |
| [`hyperlink_base`](/slides/python-net/fr/aspose.slides/idocumentproperties/hyperlink_base/) | Renvoie ou définit la propriété de document HyperlinkBase.<br/>            Lecture/écriture **str**. |
| [`scale_crop`](/slides/python-net/fr/aspose.slides/idocumentproperties/scale_crop/) | Indique le mode d'affichage de la miniature du document.<br/>            Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage.<br/>            Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin d'afficher uniquement les sections qui s'adaptent à l'affichage.<br/>            Lecture/écriture **bool**. |
| [`links_up_to_date`](/slides/python-net/fr/aspose.slides/idocumentproperties/links_up_to_date/) | Indique si les hyperliens dans un document sont à jour.<br/>            Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour.<br/>            Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes.<br/>            Lecture/écriture **bool**. |
| [`hyperlinks_changed`](/slides/python-net/fr/aspose.slides/idocumentproperties/hyperlinks_changed/) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur.<br/>            Le prochain producteur ouvrant ce document doit mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie.<br/>            Lecture/écriture **bool**. |
| [`slides`](/slides/python-net/fr/aspose.slides/idocumentproperties/slides/) | Spécifie le nombre total de diapositives dans un document de présentation.<br/fr/>            Lecture seule **int**. |
| [`hidden_slides`](/slides/python-net/fr/aspose.slides/idocumentproperties/hidden_slides/) | Spécifie le nombre de diapositives cachées dans un document de présentation.<br/>            Lecture seule **int**. |
| [`notes`](/slides/python-net/fr/aspose.slides/idocumentproperties/notes/) | Spécifie le nombre de diapositives d'une présentation contenant des notes.<br/>            Lecture seule **int**. |
| [`paragraphs`](/slides/python-net/fr/aspose.slides/idocumentproperties/paragraphs/) | Spécifie le nombre total de paragraphes présents dans un document le cas échéant.<br/>            Lecture seule **int**. |
| [`words`](/slides/python-net/fr/aspose.slides/idocumentproperties/words/) | Spécifie le nombre total de mots contenus dans un document.<br/>            Lecture seule **int**. |
| [`multimedia_clips`](/slides/python-net/fr/aspose.slides/idocumentproperties/multimedia_clips/) | Spécifie le nombre total de fichiers sonores ou vidéo présents dans le document.<br/>            Lecture seule **int**. |
| [`titles_of_parts`](/slides/python-net/fr/aspose.slides/idocumentproperties/titles_of_parts/) | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties du document mais des représentations conceptuelles des sections du document.<br/>            Lecture seule **List[str]**. |
| [`heading_pairs`](/slides/python-net/fr/aspose.slides/idocumentproperties/heading_pairs/) | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe.<br/>            Lecture seule **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/fr/aspose.slides/idocumentproperties/count_of_custom_properties/) | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection.<br/>            Lecture seule **int**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Définit une propriété personnalisée booléenne nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Définit une propriété personnalisée entière nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Définit une propriété personnalisée DateTime nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Définit une propriété personnalisée chaîne nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Définit une propriété personnalisée flottante nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Définit une propriété personnalisée double nommée. |
| [`get_custom_property_name(self, index)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| [`remove_custom_property(self, name)`](/slides/python-net/fr/aspose.slides/idocumentproperties/remove_custom_property/#str) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [`contains_custom_property(self, name)`](/slides/python-net/fr/aspose.slides/idocumentproperties/contains_custom_property/#str) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [`clear_custom_properties(self)`](/slides/python-net/fr/aspose.slides/idocumentproperties/clear_custom_properties/#) | Supprime toutes les propriétés personnalisées. |
| [`clear_built_in_properties(self)`](/slides/python-net/fr/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [`get_sensitivity_labels(self)`](/slides/python-net/fr/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection). |

### Voir également
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)