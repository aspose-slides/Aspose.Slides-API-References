---
title: SwfOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.

**Héritage:**[`SwfOptions`](/slides/python-net/fr/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type SwfOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/swfoptions/__init__/#) | Constructeur par défaut. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/swfoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être interrompu.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/swfoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression d'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/swfoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/swfoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/swfoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives cachées ou non.<br/>            La valeur par défaut est `false`. |
| [`compressed`](/slides/python-net/fr/aspose.slides.export/swfoptions/compressed/) | Spécifie si le document SWF généré doit être compressé ou non.<br/>            La valeur par défaut est `true`. |
| [`viewer_included`](/slides/python-net/fr/aspose.slides.export/swfoptions/viewer_included/) | Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non.<br/>            La valeur par défaut est `true`. |
| [`show_page_border`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_page_border/) | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est true. |
| [`show_full_screen`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_full_screen/) | Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`show_page_stepper`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_page_stepper/) | Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`show_search`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_search/) | Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`show_top_pane`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_top_pane/) | Afficher/masquer tout le panneau supérieur. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`show_bottom_pane`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_bottom_pane/) | Afficher/masquer le panneau inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`show_left_pane`](/slides/python-net/fr/aspose.slides.export/swfoptions/show_left_pane/) | Afficher/masquer le panneau gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [`start_open_left_pane`](/slides/python-net/fr/aspose.slides.export/swfoptions/start_open_left_pane/) | Démarrer avec le panneau gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false. |
| [`enable_context_menu`](/slides/python-net/fr/aspose.slides.export/swfoptions/enable_context_menu/) | Activer/désactiver le menu contextuel. La valeur par défaut est true. |
| [`logo_image_bytes`](/slides/python-net/fr/aspose.slides.export/swfoptions/logo_image_bytes/) | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur.<br/>            L'image doit être un PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte. |
| [`logo_link`](/slides/python-net/fr/aspose.slides.export/swfoptions/logo_link/) | Obtient ou définit l'adresse hypertexte complète pour un logo.<br/>            N'a d'effet que si un [`SwfOptions.logo_image_bytes`](/slides/python-net/fr/aspose.slides.export/swfoptions/logo_image_bytes) est spécifié. |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/swfoptions/jpeg_quality/) | Spécifie la qualité des images JPEG.<br/>            La valeur par défaut est 95. |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/swfoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions).<br/>            Cette propriété ne prend pas en charge l'attribution d'objets du type [`HandoutLayoutingOptions`](/slides/python-net/fr/aspose.slides.export/handoutlayoutingoptions) |

### Voir aussi
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* classe [`SwfOptions`](/slides/python-net/fr/aspose.slides.export/swfoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)