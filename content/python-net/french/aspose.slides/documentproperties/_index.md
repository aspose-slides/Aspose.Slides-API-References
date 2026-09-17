---
title: DocumentProperties class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/documentproperties/
---
## DocumentProperties classe

Represents properties of a presentation.

The DocumentProperties type exposes the following members:

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/documentproperties/__init__/#) | Initializes new instance of class [`DocumentProperties`](/slides/python-net/fr/aspose.slides/documentproperties). |

## Propriétés

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/fr/aspose.slides/documentproperties/app_version/) | Renvoie la version de l'application.<br/>            Read-only **str**. |
| [`name_of_application`](/slides/python-net/fr/aspose.slides/documentproperties/name_of_application/) | Renvoie ou définit le nom de l'application.<br/>            Read/write **str**. |
| [`company`](/slides/python-net/fr/aspose.slides/documentproperties/company/) | Renvoie ou définit la propriété de l'entreprise.<br/>            Read/write **str**. |
| [`manager`](/slides/python-net/fr/aspose.slides/documentproperties/manager/) | Renvoie ou définit la propriété du responsable.<br/>            Read/write **str**. |
| [`presentation_format`](/slides/python-net/fr/aspose.slides/documentproperties/presentation_format/) | Renvoie ou définit le format prévu d'une présentation.<br/>            Read/write **str**. |
| [`shared_doc`](/slides/python-net/fr/aspose.slides/documentproperties/shared_doc/) | Détermine si la présentation est partagée entre plusieurs personnes.<br/>            Read/write **bool**. |
| [`application_template`](/slides/python-net/fr/aspose.slides/documentproperties/application_template/) | Renvoie ou définit le modèle d'une application.<br/>            Read/write **str**. |
| [`total_editing_time`](/slides/python-net/fr/aspose.slides/documentproperties/total_editing_time/) | Durée totale d'édition d'une présentation.<br/>            Read/write **System.TimeSpan**. |
| [`title`](/slides/python-net/fr/aspose.slides/documentproperties/title/) | Renvoie ou définit le titre d'une présentation.<br/>            Read/write **str**. |
| [`subject`](/slides/python-net/fr/aspose.slides/documentproperties/subject/) | Renvoie ou définit le sujet d'une présentation.<br/>            Read/write **str**. |
| [`author`](/slides/python-net/fr/aspose.slides/documentproperties/author/) | Renvoie ou définit l'auteur d'une présentation.<br/>            Read/write **str**. |
| [`keywords`](/slides/python-net/fr/aspose.slides/documentproperties/keywords/) | Renvoie ou définit les mots-clés d'une présentation.<br/>            Read/write **str**. |
| [`comments`](/slides/python-net/fr/aspose.slides/documentproperties/comments/) | Renvoie ou définit les commentaires d'une présentation.<br/>            Read/write **str**. |
| [`category`](/slides/python-net/fr/aspose.slides/documentproperties/category/) | Renvoie ou définit la catégorie d'une présentation.<br/>            Read/write **str**. |
| [`created_time`](/slides/python-net/fr/aspose.slides/documentproperties/created_time/) | Renvoie la date de création d'une présentation.<br/>            Les valeurs sont en UTC.<br/>            Read/write **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/fr/aspose.slides/documentproperties/last_saved_time/) | Renvoie la date de la dernière modification d'une présentation.<br/>            Les valeurs sont en UTC.<br/>            Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). <br/>            Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/fr/aspose.slides/ipresentationinfo/read_document_properties)<br/>            Please see the example in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary. |
| [`last_printed`](/slides/python-net/fr/aspose.slides/documentproperties/last_printed/) | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois.<br/>            Read/write **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/fr/aspose.slides/documentproperties/last_saved_by/) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation.<br/>            Read/write **str**. |
| [`revision_number`](/slides/python-net/fr/aspose.slides/documentproperties/revision_number/) | Renvoie ou définit le numéro de révision de la présentation.<br/>            Read/write **int**. |
| [`content_status`](/slides/python-net/fr/aspose.slides/documentproperties/content_status/) | Renvoie ou définit le statut du contenu d'une présentation.<br/>            Read/write **str**. |
| [`content_type`](/slides/python-net/fr/aspose.slides/documentproperties/content_type/) | Renvoie ou définit le type de contenu d'une présentation.<br/>            Read/write **str**. |
| [`hyperlink_base`](/slides/python-net/fr/aspose.slides/documentproperties/hyperlink_base/) | Renvoie ou définit la propriété de document HyperlinkBase.<br/>            Read/write **str**. |
| [`count_of_custom_properties`](/slides/python-net/fr/aspose.slides/documentproperties/count_of_custom_properties/) | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection.<br/>            Read-only **int**. |
| [`scale_crop`](/slides/python-net/fr/aspose.slides/documentproperties/scale_crop/) | Indique le mode d'affichage de la miniature du document.<br/>            Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage.<br/>            Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin d'afficher uniquement les sections qui s'adaptent à l'affichage.<br/>            Read/write **bool**. |
| [`links_up_to_date`](/slides/python-net/fr/aspose.slides/documentproperties/links_up_to_date/) | Indique si les hyperliens dans un document sont à jour.<br/>            Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour.<br/>            Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes.<br/>            Read/write **bool**. |
| [`hyperlinks_changed`](/slides/python-net/fr/aspose.slides/documentproperties/hyperlinks_changed/) | Spécifie que un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur.<br/>            Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie.<br/>            Read/write **bool**. |
| [`slides`](/slides/python-net/fr/aspose.slides/documentproperties/slides/) | Renvoie le nombre total de diapositives dans un document de présentation.<br/fr/>            Read-only **int**. |
| [`hidden_slides`](/slides/python-net/fr/aspose.slides/documentproperties/hidden_slides/) | Renvoie le nombre de diapositives masquées dans un document de présentation.<br/>            Read-only **int**. |
| [`notes`](/slides/python-net/fr/aspose.slides/documentproperties/notes/) | Renvoie le nombre de diapositives d'une présentation contenant des notes.<br/>            Read-only **int**. |
| [`paragraphs`](/slides/python-net/fr/aspose.slides/documentproperties/paragraphs/) | Renvoie le nombre total de paragraphes trouvés dans un document le cas échéant.<br/>            Read-only **int**. |
| [`words`](/slides/python-net/fr/aspose.slides/documentproperties/words/) | Renvoie le nombre total de mots contenus dans un document.<br/>            Read-only **int**. |
| [`multimedia_clips`](/slides/python-net/fr/aspose.slides/documentproperties/multimedia_clips/) | Renvoie le nombre total de clips audio ou vidéo présents dans le document.<br/>            Read-only **int**. |
| [`titles_of_parts`](/slides/python-net/fr/aspose.slides/documentproperties/titles_of_parts/) | Spécifie le titre de chaque partie du document.<br/>            Ces parties ne sont pas des parties de document mais des représentations conceptuelles des sections du document.<br/>            Read-only **List[str]**. |
| [`heading_pairs`](/slides/python-net/fr/aspose.slides/documentproperties/heading_pairs/) | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe.<br/>            Read-only **List[IHeadingPair]**. |

## Méthodes

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Définit une propriété personnalisée booléenne nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Définit une propriété personnalisée entière nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Définit une propriété personnalisée DateTime nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Définit une propriété personnalisée chaîne nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Définit une propriété personnalisée flottante nommée. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/fr/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Définit une propriété personnalisée double nommée. |
| [`get_custom_property_name(self, index)`](/slides/python-net/fr/aspose.slides/documentproperties/get_custom_property_name/#int) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| [`remove_custom_property(self, name)`](/slides/python-net/fr/aspose.slides/documentproperties/remove_custom_property/#str) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [`contains_custom_property(self, name)`](/slides/python-net/fr/aspose.slides/documentproperties/contains_custom_property/#str) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [`clear_custom_properties(self)`](/slides/python-net/fr/aspose.slides/documentproperties/clear_custom_properties/#) | Supprime toutes les propriétés personnalisées. |
| [`get_sensitivity_labels(self)`](/slides/python-net/fr/aspose.slides/documentproperties/get_sensitivity_labels/#) | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés de document personnalisées (Métadonnées du SDK Microsoft Information Protection). |
| [`clear_built_in_properties(self)`](/slides/python-net/fr/aspose.slides/documentproperties/clear_built_in_properties/#) | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [`clone(self)`](/slides/python-net/fr/aspose.slides/documentproperties/clone/#) | Clone l'objet actuel |
| [`clone_t(self)`](/slides/python-net/fr/aspose.slides/documentproperties/clone_t/#) | Clone l'objet actuel |


### Voir aussi
* classe [`DocumentProperties`](/slides/python-net/fr/aspose.slides/documentproperties)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)