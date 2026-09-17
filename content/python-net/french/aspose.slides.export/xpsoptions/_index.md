---
title: XpsOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/xpsoptions/
---
## XpsOptions classe

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format XPS.

**Héritage:**[`XpsOptions`](/slides/python-net/fr/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type XpsOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/xpsoptions/__init__/#) | Constructeur par défaut. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/xpsoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être annulé.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/xpsoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/xpsoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/xpsoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/xpsoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/xpsoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives cachées ou non.<br/>            La valeur par défaut est `false`. |
| [`save_metafiles_as_png`](/slides/python-net/fr/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG.<br/>            Lecture/écriture **bool**. |
| [`draw_slides_frame`](/slides/python-net/fr/aspose.slides.export/xpsoptions/draw_slides_frame/) | Vrai pour dessiner un cadre noir autour de chaque diapositive.<br/>             Lecture/écriture **bool**. |

### Voir aussi
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* classe [`XpsOptions`](/slides/python-net/fr/aspose.slides.export/xpsoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)