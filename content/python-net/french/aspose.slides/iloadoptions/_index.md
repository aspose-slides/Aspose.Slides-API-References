---
title: ILoadOptions class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/iloadoptions/
---
## ILoadOptions classe

Permet de spécifier des options supplémentaires (comme le format ou la police par défaut) lors du chargement d’une présentation.

Le type ILoadOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`load_format`](/slides/python-net/fr/aspose.slides/iloadoptions/load_format/) | Renvoie ou définit le format d’une présentation à charger.<br/>            Lecture/écriture [`LoadFormat`](/slides/python-net/fr/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides/iloadoptions/default_regular_font/) | Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`default_symbol_font`](/slides/python-net/fr/aspose.slides/iloadoptions/default_symbol_font/) | Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`default_asian_font`](/slides/python-net/fr/aspose.slides/iloadoptions/default_asian_font/) | Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`password`](/slides/python-net/fr/aspose.slides/iloadoptions/password/) | Renvoie ou définit le mot de passe.<br/>            Lecture-écriture **str**. |
| [`only_load_document_properties`](/slides/python-net/fr/aspose.slides/iloadoptions/only_load_document_properties/) | Cette propriété est pertinente si le fichier de présentation est protégé par un mot de passe.<br/>            La valeur true indique que seules les propriétés du document doivent être chargées depuis un fichier de présentation chiffré <br/>            et que le mot de passe doit être ignoré.<br/>            La valeur false indique que l’ensemble de la présentation chiffrée doit être chargé en utilisant le bon <br/>            mot de passe.<br/>            Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée.<br/>            Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors<br/>            les propriétés du document ne peuvent pas être chargées et une exception sera levée.<br/>            Lecture-écriture **bool**. |
| [`warning_callback`](/slides/python-net/fr/aspose.slides/iloadoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement <br/>            doit continuer ou être interrompu.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/fr/aspose.slides/iloadoptions/blob_management_options/) | Représente les options qui peuvent être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs),<br/>            comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options sont destinées à définir<br/>            le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particuliers.<br/>            Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique - c’est-à-dire qu’un BLOB peut <br/>            être un audio, une vidéo ou la présentation elle-même. |
| [`document_level_font_sources`](/slides/python-net/fr/aspose.slides/iloadoptions/document_level_font_sources/) | Spécifie les sources des polices externes à utiliser par la présentation.<br/>            Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d’autres présentations |
| [`interruption_token`](/slides/python-net/fr/aspose.slides/iloadoptions/interruption_token/) | Le jeton pour surveiller les demandes d’interruption.<br/>            <br/>            Ce jeton gère toute la durée de vie de l’instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement ou l’enregistrement de la presentaion, sera interrompue en appelant la méthode [`IInterruptionTokenSource.interrupt`](/slides/python-net/fr/aspose.slides/iinterruptiontokensource/interrupt) de <br/>            [`IInterruptionTokenSource`](/slides/python-net/fr/aspose.slides/iinterruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/fr/aspose.slides/iloadoptions/resource_loading_callback/) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes.<br/>            Lecture/écriture [`IResourceLoadingCallback`](/slides/python-net/fr/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/fr/aspose.slides/iloadoptions/spreadsheet_options/) | Représente les options qui peuvent être utilisées pour spécifier le comportement supplémentaire des feuilles de calcul. |
| [`default_text_language`](/slides/python-net/fr/aspose.slides/iloadoptions/default_text_language/) | Renvoie ou définit la langue par défaut du texte de la présentation.<br/>             Lecture/écriture **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/fr/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation.<br/>            <br/>Les types des objets binaires intégrés :<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/fr/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/fr/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lecture/écriture **bool**. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)