---
title: LoadOptions class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/loadoptions/
---
## classe LoadOptions

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d'une présentation.

Le type LoadOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides/loadoptions/__init__/#) | Crée de nouvelles options de chargement par défaut. |
| [`__init__(self, load_format)`](/slides/python-net/fr/aspose.slides/loadoptions/__init__/#loadformat) | Crée de nouvelles options de chargement. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`load_format`](/slides/python-net/fr/aspose.slides/loadoptions/load_format/) | Renvoie ou définit le format d'une présentation à charger.<br/>            Lecture/écriture [`LoadFormat`](/slides/python-net/fr/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides/loadoptions/default_regular_font/) | Renvoie ou définit la police Regular utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`default_symbol_font`](/slides/python-net/fr/aspose.slides/loadoptions/default_symbol_font/) | Renvoie ou définit la police Symbol utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`default_asian_font`](/slides/python-net/fr/aspose.slides/loadoptions/default_asian_font/) | Renvoie ou définit la police Asian utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`password`](/slides/python-net/fr/aspose.slides/loadoptions/password/) | Renvoie ou définit le mot de passe.<br/>            Lecture/écriture **str**. |
| [`only_load_document_properties`](/slides/python-net/fr/aspose.slides/loadoptions/only_load_document_properties/) | Cette propriété n'a de sens que si le fichier de présentation est protégé par un mot de passe.<br/>            La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré.<br/>            La valeur false signifie que l'intégralité de la présentation chiffrée doit être chargée en utilisant le mot de passe correct.<br/>            Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée.<br/>            Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée.<br/>            Lecture/écriture **bool**. |
| [`warning_callback`](/slides/python-net/fr/aspose.slides/loadoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement se poursuivra ou sera abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/fr/aspose.slides/loadoptions/blob_management_options/) | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des Binary Large Objects (BLOBs),<br/>            telles que l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOBs en mémoire. Ces options sont destinées à établir<br/>            le meilleur ratio performance/consommation de mémoire pour un environnement ou des exigences particulières.<br/>            Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique – par exemple, un BLOB peut<br/>            être un audio, une vidéo ou la présentation elle-même. |
| [`document_level_font_sources`](/slides/python-net/fr/aspose.slides/loadoptions/document_level_font_sources/) | Spécifie les sources des polices externes à utiliser par la présentation.<br/>            Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d'autres présentations |
| [`interruption_token`](/slides/python-net/fr/aspose.slides/loadoptions/interruption_token/) | Le jeton pour surveiller les requêtes d'interruption.<br/>            <br/>            Ce jeton gère toute la durée de vie de l'instance [`IPresentation`](/slides/python-net/fr/aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement<br/>            ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [`InterruptionTokenSource.interrupt`](/slides/python-net/fr/aspose.slides/interruptiontokensource/interrupt) du<br/>            [`InterruptionTokenSource`](/slides/python-net/fr/aspose.slides/interruptiontokensource). |
| [`resource_loading_callback`](/slides/python-net/fr/aspose.slides/loadoptions/resource_loading_callback/) | Renvoie ou définit l'interface de rappel qui gère le chargement des ressources externes.<br/>            Lecture/écriture [`IResourceLoadingCallback`](/slides/python-net/fr/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/fr/aspose.slides/loadoptions/spreadsheet_options/) | Renvoie les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques. |
| [`default_text_language`](/slides/python-net/fr/aspose.slides/loadoptions/default_text_language/) | Renvoie ou définit la langue par défaut du texte de la présentation.<br/>             Lecture/écriture **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/fr/aspose.slides/loadoptions/delete_embedded_binary_objects/) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.<br/>            <br/>Les types des objets binaires incorporés :<br/><br/><br/>* VBA Project [`IPresentation.vba_project`](/slides/python-net/fr/aspose.slides/ipresentation/vba_project)<br/>* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/fr/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Lecture/écriture **bool**. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)