---
title: SVGOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/svgoptions/
---
## SVGOptions classe

Représente des options SVG.

**Héritage:**[`SVGOptions`](/slides/python-net/fr/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type SVGOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/svgoptions/__init__/#) | Initialise une nouvelle instance de la classe SVGOptions. |
| [`__init__(self, link_embed_controller)`](/slides/python-net/fr/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet contrôleur d'intégration du lien. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/svgoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/svgoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/svgoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source est introuvable.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/svgoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/svgoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/svgoptions/ink_options/) | Fournit des options contrôlant l'apparence des objets Encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/fr/aspose.slides.export/svgoptions/use_frame_size/) | Détermine si le cadre de texte sera inclus dans une zone de rendu ou non.<br/>            Lecture/écriture **bool**.<br/>            La valeur par défaut est false. |
| [`use_frame_rotation`](/slides/python-net/fr/aspose.slides.export/svgoptions/use_frame_rotation/) | Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non.<br/>            Lecture/écriture **bool**.<br/>            La valeur par défaut est true. |
| [`vectorize_text`](/slides/python-net/fr/aspose.slides.export/svgoptions/vectorize_text/) | Détermine si le texte d'une diapositive sera enregistré sous forme de graphiques.<br/>            Lecture/écriture **bool**. |
| [`metafile_rasterization_dpi`](/slides/python-net/fr/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | Renvoie ou définit la limite de résolution minimale pour la rasterisation des métafichiers.<br/>            Lecture/écriture **int**. |
| [`disable_3d_text`](/slides/python-net/fr/aspose.slides.export/svgoptions/disable_3d_text/) | Détermine si le texte 3D est désactivé dans le SVG.<br/>            Lecture/écriture **bool**. |
| [`disable_gradient_split`](/slides/python-net/fr/aspose.slides.export/svgoptions/disable_gradient_split/) | Désactive le fractionnement des dégradés FromCornerX et FromCenter.<br/>            Lecture/écriture **bool**. |
| [`disable_line_end_cropping`](/slides/python-net/fr/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs.<br/>            Le moteur d'écriture SVG d'Aspose.Slides possède une solution de contournement pour ce problème :<br/>            il recadre l'extrémité de la ligne avec la flèche, de sorte que la ligne ne se superpose pas aux marqueurs.<br/>            Cette option désactive ce comportement.<br/>            Lecture/écriture **bool**. |
| [`default`](/slides/python-net/fr/aspose.slides.export/svgoptions/default/) | Renvoie les paramètres par défaut.<br/>            Lecture seule [`SVGOptions`](/slides/python-net/fr/aspose.slides.export/svgoptions). |
| [`simple`](/slides/python-net/fr/aspose.slides.export/svgoptions/simple/) | Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit.<br/>            Lecture seule [`SVGOptions`](/slides/python-net/fr/aspose.slides.export/svgoptions). |
| [`wysiwyg`](/slides/python-net/fr/aspose.slides.export/svgoptions/wysiwyg/) | Renvoie les paramètres pour la génération du fichier SVG le plus précis.<br/>            Lecture seule [`SVGOptions`](/slides/python-net/fr/aspose.slides.export/svgoptions). |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/svgoptions/jpeg_quality/) | Détermine la qualité d'encodage JPEG.<br/>            Lecture/écriture **int**. |
| [`shape_formatting_controller`](/slides/python-net/fr/aspose.slides.export/svgoptions/shape_formatting_controller/) | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes.<br/>            Lecture/écriture [`ISvgShapeFormattingController`](/slides/python-net/fr/aspose.slides.export/isvgshapeformattingcontroller). |
| [`pictures_compression`](/slides/python-net/fr/aspose.slides.export/svgoptions/pictures_compression/) | Représente le niveau de compression des images |
| [`delete_pictures_cropped_areas`](/slides/python-net/fr/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | Un indicateur booléen indique si les parties recadrées restent intégrées au document. Si vrai les parties recadrées seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |
| [`external_fonts_handling`](/slides/python-net/fr/aspose.slides.export/svgoptions/external_fonts_handling/) | Détermine la manière de gérer les polices chargées extérieurement.<br/>            Lecture/écriture [`SvgExternalFontsHandling`](/slides/python-net/fr/aspose.slides.export/svgexternalfontshandling). |
| [`disable_font_ligatures`](/slides/python-net/fr/aspose.slides.export/svgoptions/disable_font_ligatures/) | Renvoie ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures.<br/>            Lorsqu'elle est définie sur `true`, les ligatures seront désactivées dans le rendu. Par défaut, cette propriété est définie sur `false`. |


### Voir aussi
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* classe [`SVGOptions`](/slides/python-net/fr/aspose.slides.export/svgoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)