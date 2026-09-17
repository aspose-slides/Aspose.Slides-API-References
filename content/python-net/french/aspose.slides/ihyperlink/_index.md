---
title: IHyperlink class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ihyperlink/
---
## IHyperlink classe

Représente un hyperlien.

Le type IHyperlink expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`action_type`](/slides/python-net/fr/aspose.slides/ihyperlink/action_type/) | Renvoie le type de l'action de HyperLinkEx.<br/>            Lecture seule [`HyperlinkActionType`](/slides/python-net/fr/aspose.slides/hyperlinkactiontype). |
| [`external_url`](/slides/python-net/fr/aspose.slides/ihyperlink/external_url/) | Spécifie l'URL externe.<br/>            Si cette propriété n'est pas None, alors la propriété TargetSlide devient None.<br/>            Lecture seule **str**. |
| [`external_url_original`](/slides/python-net/fr/aspose.slides/ihyperlink/external_url_original/) | Représente un hyperlien défini pour cette portion sans tenir compte du contenu réel de la portion.<br/>            <br/>            PowerPoint se comporte spécifiquement pour les liens et leur texte correspondant dans une portion. Il permet de créer du texte pour l'hyperlien sous<br/>            la forme d'une URL valide, différente de l'adresse réelle du lien. Dans ce cas, lorsque vous visualisez le lien dans la fenêtre d'édition, il sera<br/>            modifié pour correspondre à la portion de texte. Cette propriété représente la valeur originale de l'hyperlien. |
| [`target_slide`](/slides/python-net/fr/aspose.slides/ihyperlink/target_slide/) | Si HyperlinkEx cible une diapositive spécifique, renvoie cette diapositive.<br/>            Si la propriété n'est pas None, alors la propriété ExternalUrl devient None.<br/>            Lecture seule [`ISlide`](/slides/python-net/fr/aspose.slides/islide). |
| [`target_frame`](/slides/python-net/fr/aspose.slides/ihyperlink/target_frame/) | Renvoie le cadre au sein du frameset HTML parent pour la cible<br/>            du hyperlien parent lorsqu'il existe.<br/>            Lecture/écriture **str**. |
| [`tooltip`](/slides/python-net/fr/aspose.slides/ihyperlink/tooltip/) | Renvoie la chaîne qui peut être affichée dans une interface utilisateur<br/>            en tant qu'associée à l'hyperlien parent.<br/>            Lecture/écriture **str**. |
| [`history`](/slides/python-net/fr/aspose.slides/ihyperlink/history/) | Détermine si la cible de l'hyperlien parent doit être ajoutée<br/>            à une liste d'hyperliens visualisés lorsqu'il est invoqué.<br/>            Lecture/écriture **bool**. |
| [`highlight_click`](/slides/python-net/fr/aspose.slides/ihyperlink/highlight_click/) | Détermine si l'hyperlien doit être mis en surbrillance au clic.<br/>            Lecture/écriture **bool**. |
| [`stop_sound_on_click`](/slides/python-net/fr/aspose.slides/ihyperlink/stop_sound_on_click/) | Détermine si le son doit être arrêté lors du clic sur l'hyperlien.<br/>            Lecture/écriture **bool**. |
| [`sound`](/slides/python-net/fr/aspose.slides/ihyperlink/sound/) | Représente le son en cours de lecture de l'hyperlien.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`color_source`](/slides/python-net/fr/aspose.slides/ihyperlink/color_source/) | Représente la source de la couleur de l'hyperlien - soit les styles, soit le format de la portion.<br/>            Lecture/écriture [`HyperlinkColorSource`](/slides/python-net/fr/aspose.slides/hyperlinkcolorsource). |

## Méthodes

| Method | Description |
| :- | :- |
| [`equals(self, hlink)`](/slides/python-net/fr/aspose.slides/ihyperlink/equals/#ihyperlink) | Détermine si les deux instances Hyperlink sont égales. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)