---
title: Hyperlink class
second_title: Aspose.Slides pour Python via la référence de l'API .NET
description: 
type: docs
url: /fr/aspose.slides/hyperlink/
---
## Classe Hyperlink

Représente un hyperlien.

**Héritage:**[`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink) → [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)

Le type Hyperlink expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, url)`](/slides/python-net/fr/aspose.slides/hyperlink/__init__/#str) | Crée une instance d'un hyperlien. |
| [`__init__(self, slide)`](/slides/python-net/fr/aspose.slides/hyperlink/__init__/#islide) | Crée une instance d'un hyperlien qui pointe vers une diapositive spécifique.<br/>            Remarque : l'hyperlien créé doit être affecté à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |
| [`__init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click)`](/slides/python-net/fr/aspose.slides/hyperlink/__init__/#hyperlink-str-str-bool-bool-bool) | Crée une instance d'un hyperlien en utilisant un autre hyperlien comme source, en écrasant les propriétés secondaires. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`no_action`](/slides/python-net/fr/aspose.slides/hyperlink/no_action/) | Renvoie un hyperlien spécial « ne rien faire ». <br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`media`](/slides/python-net/fr/aspose.slides/hyperlink/media/) | Renvoie un hyperlien spécial « lire le fichier multimédia ». Utilisé dans AudioFrame et VideoFrame.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`next_slide`](/slides/python-net/fr/aspose.slides/hyperlink/next_slide/) | Renvoie un hyperlien vers la diapositive suivante.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`previous_slide`](/slides/python-net/fr/aspose.slides/hyperlink/previous_slide/) | Renvoie un hyperlien vers la diapositive précédente.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`first_slide`](/slides/python-net/fr/aspose.slides/hyperlink/first_slide/) | Renvoie un hyperlien vers la première diapositive de la présentation.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`last_slide`](/slides/python-net/fr/aspose.slides/hyperlink/last_slide/) | Renvoie un hyperlien vers la dernière diapositive de la présentation.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`last_vieved_slide`](/slides/python-net/fr/aspose.slides/hyperlink/last_vieved_slide/) | Renvoie un hyperlien vers la dernière diapositive consultée.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`end_show`](/slides/python-net/fr/aspose.slides/hyperlink/end_show/) | Renvoie un hyperlien qui termine le diaporama.<br/>            Lecture seule [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink). |
| [`action_type`](/slides/python-net/fr/aspose.slides/hyperlink/action_type/) | Renvoie le type d'action de l'Hyperlink.<br/>            Lecture seule [`HyperlinkActionType`](/slides/python-net/fr/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/fr/aspose.slides/hyperlink/external_url/) | Spécifie l'URL externe.<br/>            Lecture seule **str**. |
| [`target_slide`](/slides/python-net/fr/aspose.slides/hyperlink/target_slide/) | Si l'Hyperlink pointe vers une diapositive spécifique, renvoie cette diapositive.<br/>            Lecture seule [`ISlide`](/slides/python-net/fr/aspose.slides/islide). |
| [`external_url_original`](/slides/python-net/fr/aspose.slides/hyperlink/external_url_original/) | Représente un hyperlien défini pour cette portion sans tenir compte du contenu réel de la portion.<br/>            <br/>            PowerPoint se comporte de manière spécifique pour les liens et le texte correspondant dans une portion. Il permet de créer du texte pour l'hyperlien sous forme d'URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsqu'on visualise le lien dans la fenêtre d'édition, il sera modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien. |
| [`target_frame`](/slides/python-net/fr/aspose.slides/hyperlink/target_frame/) | Renvoie le cadre du frameset HTML parent pour la cible<br/>            de l'hyperlien parent lorsqu'il existe.<br/>            Lecture/écriture **str**. |
| [`tooltip`](/slides/python-net/fr/aspose.slides/hyperlink/tooltip/) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur<br/>            en tant qu'associée à l'hyperlien parent.<br/>            Lecture/écriture **str**. |
| [`history`](/slides/python-net/fr/aspose.slides/hyperlink/history/) | Détermine si la cible de l'hyperlien parent doit être ajoutée<br/>            à une liste d'hyperliens consultés lorsqu'elle est invoquée.<br/>            Lecture/écriture **bool**. |
| [`highlight_click`](/slides/python-net/fr/aspose.slides/hyperlink/highlight_click/) | Détermine si l'hyperlien doit être mis en évidence au clic.<br/>            Lecture/écriture **bool**. |
| [`stop_sound_on_click`](/slides/python-net/fr/aspose.slides/hyperlink/stop_sound_on_click/) | Détermine si le son doit être interrompu lors du clic sur l'hyperlien.<br/>            Lecture/écriture **bool**. |
| [`sound`](/slides/python-net/fr/aspose.slides/hyperlink/sound/) | Représente le son en cours de lecture de l'hyperlien.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/fr/aspose.slides/hyperlink/color_source/) | Représente la source de la couleur de l'hyperlien – soit les styles, soit le format de la portion.<br/>            Lecture/écriture [`HyperlinkColorSource`](/slides/python-net/fr/aspose.slides/hyperlinkcolorsource). |
| [`slide`](/slides/python-net/fr/aspose.slides/hyperlink/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/hyperlink/presentation/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/fr/aspose.slides/hyperlink/equals/#ihyperlink) | Détermine si les deux instances d'Hyperlink sont égales. |

### Voir aussi
* classe [`Hyperlink`](/slides/python-net/fr/aspose.slides/hyperlink)
* classe [`PVIObject`](/slides/python-net/fr/aspose.slides/pviobject)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)