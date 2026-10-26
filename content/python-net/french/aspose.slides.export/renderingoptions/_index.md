---
title: RenderingOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/renderingoptions/
---
## RenderingOptions classe

Fournit des options qui contrôlent la façon dont une présentation/diapositive est rendue.

**Héritage:**[`RenderingOptions`](/slides/python-net/fr/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type RenderingOptions expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/renderingoptions/__init__/#) | Constructeur par défaut. |

## Propriétés

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/renderingoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit des avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/renderingoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/renderingoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/renderingoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/renderingoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false** . |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/renderingoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/renderingoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/fr/aspose.slides.export/renderingoptions/disable_font_ligatures/) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser les ligatures.<br/>            Lorsqu'elle est définie sur `true`, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur `false`. |


### Voir aussi
* classe [`RenderingOptions`](/slides/python-net/fr/aspose.slides.export/renderingoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)