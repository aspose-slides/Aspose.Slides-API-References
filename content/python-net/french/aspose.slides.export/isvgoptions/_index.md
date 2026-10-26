---
title: ISVGOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/isvgoptions/
---
## ISVGOptions classe

Représente des options SVG.

Le type ISVGOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`vectorize_text`](/slides/python-net/fr/aspose.slides.export/isvgoptions/vectorize_text/) | Détermine si le texte d'une diapositive sera enregistré en tant que graphiques.<br/>            Lecture/écriture **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/fr/aspose.slides.export/isvgoptions/metafile_rasterization_dpi/) | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers.<br/>            Lecture/écriture **int**. |
| [`disable_3d_text`](/slides/python-net/fr/aspose.slides.export/isvgoptions/disable_3d_text/) | Détermine si le texte 3D est désactivé dans SVG.<br/>            Lecture/écriture **bool**. |
| [`disable_gradient_split`](/slides/python-net/fr/aspose.slides.export/isvgoptions/disable_gradient_split/) | Désactive le fractionnement des dégradés FromCornerX et FromCenter.<br/>            Lecture/écriture **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/fr/aspose.slides.export/isvgoptions/disable_line_end_cropping/) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs.<br/>            Le moteur d'écriture SVG d'Aspose.Slides propose une solution de contournement pour ce problème :<br/>            il recadre la fin de ligne avec la flèche, de sorte que la ligne ne chevauche pas les marqueurs.<br/>            Cette option désactive ce comportement.<br/>            Lecture/écriture **bool**. |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/isvgoptions/jpeg_quality/) | Détermine la qualité d'encodage JPEG.<br/>            Lecture/écriture **int**. |
| [`shape_formatting_controller`](/slides/python-net/fr/aspose.slides.export/isvgoptions/shape_formatting_controller/) | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes.<br/>            Lecture/écriture [`ISvgShapeFormattingController`](/slides/python-net/fr/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/fr/aspose.slides.export/isvgoptions/pictures_compression/) | Représente le niveau de compression des images<br/>            Lecture/écriture [`ISVGOptions.pictures_compression`](/slides/python-net/fr/aspose.slides.export/isvgoptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/fr/aspose.slides.export/isvgoptions/delete_pictures_cropped_areas/) | Un indicateur booléen indique si les parties recadrées restent dans le document. Si vrai, les parties recadrées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux)<br/>            Lecture/écriture **bool**. |
| [`use_frame_size`](/slides/python-net/fr/aspose.slides.export/isvgoptions/use_frame_size/) | Détermine si le cadre de texte sera inclus dans une zone de rendu ou non.<br/>            Lecture/écriture **bool**.<br/>            La valeur par défaut est false. |
| [`use_frame_rotation`](/slides/python-net/fr/aspose.slides.export/isvgoptions/use_frame_rotation/) | Détermine s'il faut effectuer la rotation spécifiée de la forme lors du rendu ou non.<br/>            Lecture/écriture **bool**.<br/>            La valeur par défaut est true. |
| [`external_fonts_handling`](/slides/python-net/fr/aspose.slides.export/isvgoptions/external_fonts_handling/) | Détermine une manière de gérer les polices chargées externement.<br/>            Lecture/écriture [`SvgExternalFontsHandling`](/slides/python-net/fr/aspose.slides.export/svgexternalfontshandling). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/isvgoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/fr/aspose.slides.export/isvgoptions/disable_font_ligatures/) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser les ligatures.<br/>            Lorsqu'elle est définie sur `true`, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur `false`. |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/isvgoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/isvgoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/isvgoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/isvgoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/isvgoptions/skip_java_script_links/) |  |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)