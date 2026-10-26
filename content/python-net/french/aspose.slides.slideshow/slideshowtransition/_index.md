---
title: SlideShowTransition class
second_title: Aspose.Slides pour Python via la référence API .NET
description: 
type: docs
url: /fr/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition classe

Représente la transition de diaporama.

Le type SlideShowTransition expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound/) | Renvoie ou définit les données audio intégrées.<br/>            Lecture/écriture [`IAudio`](/slides/python-net/fr/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound_mode/) | Définit ou renvoie le mode sonore pour la transition de diapositive.<br/>            Lecture/écriture [`TransitionSoundMode`](/slides/python-net/fr/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound_loop/) | Cet attribut indique si le son se répétera jusqu'à ce que le prochain événement sonore survienne dans<br/>            le diaporama.<br/>            Lecture/écriture **bool**. |
| [`advance_on_click`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | Spécifie si un clic de souris fera avancer la diapositive ou non. Si cet attribut n'est pas<br/>            spécifié, la valeur true est supposée.<br/>            Lecture/écriture **bool**. |
| [`advance_after`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/advance_after/) | Cet attribut indique si le diaporama passera à la diapositive suivante après un certain temps.<br/>            Lecture/écriture **bool**. |
| [`advance_after_time`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | Spécifie le temps, en millisecondes, après lequel la transition doit commencer. Ce réglage<br/>            peut être utilisé conjointement avec l'attribut advClick. Si cet attribut n'est pas spécifié<br/>            on suppose qu'aucune avance automatique n'aura lieu.<br/>            Lecture/écriture **int**. |
| [`speed`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/speed/) | Spécifie la vitesse de transition à utiliser lors du passage de la diapositive actuelle<br/>            à la suivante.<br/>            Lecture/écriture [`TransitionSpeed`](/slides/python-net/fr/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/value/) | Valeur de transition du diaporama.<br/>            Lecture seule [`ITransitionValueBase`](/slides/python-net/fr/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/type/) | Type de transition.<br/>            Lecture/écriture [`TransitionType`](/slides/python-net/fr/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | Indique si ce son est un son intégré ou non. Si cet attribut est défini sur true alors<br/>            l'application génératrice est avertie de vérifier l'attribut name spécifié pour ce son<br/>            dans sa liste de sons intégrés et peut alors afficher un nom personnalisé ou une interface selon les besoins.<br/>            Lecture-écriture **bool**. |
| [`sound_name`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound_name/) | Spécifie un nom lisible par l'homme pour le son de la transition. La propriété [`SlideShowTransition.sound`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/sound) doit être attribuée pour obtenir ou définir le nom du son.<br/>            Lecture-écriture **str**. |
| [`duration`](/slides/python-net/fr/aspose.slides.slideshow/slideshowtransition/duration/) | Renvoie ou définit la durée de l'effet de transition de diapositive en millisecondes.<br/>            Lecture/écriture **int**. |

### Voir aussi
* module [`aspose.slides.slideshow`](/slides/python-net/fr/aspose.slides.slideshow)
* bibliothèque [`Aspose.Slides`](/slides/python-net)