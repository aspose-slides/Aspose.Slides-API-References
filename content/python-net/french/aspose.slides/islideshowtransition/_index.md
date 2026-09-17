---
title: ISlideShowTransition class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/islideshowtransition/
---
## ISlideShowTransition classe

Représente la transition du diaporama.

Le type ISlideShowTransition expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`sound`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound/) | Renvoie ou définit les données audio intégrées.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound_mode/) | Définit ou renvoie le mode son pour la transition de diapositive.<br/>            Lecture/écriture [`TransitionSoundMode`](/slides/python-net/fr/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound_loop/) | Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore se produise dans le diaporama.<br/>            Lecture/écriture **bool**. |
| [`advance_on_click`](/slides/python-net/fr/aspose.slides/islideshowtransition/advance_on_click/) | Indique si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas spécifié, la valeur true est supposée.<br/>            Lecture/écriture **bool**. |
| [`advance_after`](/slides/python-net/fr/aspose.slides/islideshowtransition/advance_after/) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps.<br/>            Lecture/écriture **bool**. |
| [`advance_after_time`](/slides/python-net/fr/aspose.slides/islideshowtransition/advance_after_time/) | Indique le temps, en millisecondes, après lequel la transition doit commencer. Ce réglage peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié, il est supposé qu'aucune avance automatique n'est prévue.<br/>            Lecture/écriture **int**. |
| [`speed`](/slides/python-net/fr/aspose.slides/islideshowtransition/speed/) | Indique la vitesse de transition à utiliser lors du passage de la diapositive actuelle à la suivante.<br/>            Lecture/écriture [`TransitionSpeed`](/slides/python-net/fr/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/fr/aspose.slides/islideshowtransition/value/) | Valeur de transition du diaporama.<br/>            Lecture seule [`ITransitionValueBase`](/slides/python-net/fr/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/fr/aspose.slides/islideshowtransition/type/) | Type de transition.<br/>            Lecture/écriture [`TransitionType`](/slides/python-net/fr/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound_is_built_in/) | Indique si ce son est un son intégré ou non. Si cet attribut est défini sur true, l'application génératrice est alertée pour vérifier l'attribut name spécifié pour ce son dans sa liste de sons intégrés et peut alors fournir un nom personnalisé ou une interface utilisateur selon les besoins.<br/>            Lecture/écriture **bool**. |
| [`sound_name`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound_name/) | Indique un nom lisible par l'homme pour le son de la transition. La propriété [`ISlideShowTransition.sound`](/slides/python-net/fr/aspose.slides/islideshowtransition/sound) doit être assignée pour obtenir ou définir le nom du son.<br/>            Lecture/écriture **str**. |
| [`duration`](/slides/python-net/fr/aspose.slides/islideshowtransition/duration/) | Obtient ou définit la durée de l'effet de transition de diapositive en millisecondes.<br/>            Lecture/écriture **int**. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)