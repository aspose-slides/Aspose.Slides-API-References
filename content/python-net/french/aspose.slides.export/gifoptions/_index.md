---
title: GifOptions class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.export/gifoptions/
---
## GifOptions classe

Représente les options d'exportation GIF.

**Héritage:**[`GifOptions`](/slides/python-net/fr/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type GifOptions expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/gifoptions/__init__/#) | Initialise une nouvelle instance de la classe GifOptions. |

## Propriétés

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/gifoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/gifoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/gifoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/gifoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/gifoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false** . |
| [`frame_size`](/slides/python-net/fr/aspose.slides.export/gifoptions/frame_size/) | Obtient ou définit la taille du cadre. |
| [`export_hidden_slides`](/slides/python-net/fr/aspose.slides.export/gifoptions/export_hidden_slides/) | Détermine si les diapositives cachées seront exportées.<br/>            La valeur par défaut est false. |
| [`transition_fps`](/slides/python-net/fr/aspose.slides.export/gifoptions/transition_fps/) | Obtient ou définit les FPS de transition [frames/sec]<br/>            La valeur par défaut est 25. |
| [`default_delay`](/slides/python-net/fr/aspose.slides.export/gifoptions/default_delay/) | Obtient ou définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si [`ISlideShowTransition.advance_after_time`](/slides/python-net/fr/aspose.slides/islideshowtransition/advance_after_time) n'est pas défini.<br/>            La valeur par défaut est 1000. |


### Voir aussi
* classe [`GifOptions`](/slides/python-net/fr/aspose.slides.export/gifoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)