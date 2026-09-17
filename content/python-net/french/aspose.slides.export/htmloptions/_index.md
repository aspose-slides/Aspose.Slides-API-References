---
title: HtmlOptions class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.export/htmloptions/
---
## HtmlOptions classe

Représente des options d'exportation HTML.

**Héritage:**[`HtmlOptions`](/slides/python-net/fr/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type HtmlOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/fr/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | Crée un nouvel objet HtmlOptions spécifiant le rappel. |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/htmloptions/__init__/#) | Crée un nouvel objet HtmlOptions pour sauvegarder dans un fichier HTML unique. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/htmloptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement se poursuivra ou sera interrompu.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/htmloptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/htmloptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n’est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/htmloptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/htmloptions/skip_java_script_links/) | Spécifie s’il faut ignorer les hyperliens avec des appels JavaScript lors de l’enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/htmloptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l’exportation d’une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/htmloptions/ink_options/) | Fournit des options qui contrôlent l’apparence des objets encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/htmloptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives cachées ou non.<br/>            La valeur par défaut est `false`. |
| [`html_formatter`](/slides/python-net/fr/aspose.slides.export/htmloptions/html_formatter/) | Renvoie ou définit le modèle HTML.<br/>            Lecture/écriture [`IHtmlFormatter`](/slides/python-net/fr/aspose.slides.export/ihtmlformatter). |
| [`disable_font_ligatures`](/slides/python-net/fr/aspose.slides.export/htmloptions/disable_font_ligatures/) | Obtient ou définit une valeur indiquant si le texte est rendu sans ligatures.<br/>            Lorsqu’elle est définie sur `true`, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur `false`. |
| [`slide_image_format`](/slides/python-net/fr/aspose.slides.export/htmloptions/slide_image_format/) | Renvoie ou définit les options de format d’image de diapositive.<br/>            Lecture/écriture [`ISlideImageFormat`](/slides/python-net/fr/aspose.slides.export/islideimageformat). |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/htmloptions/jpeg_quality/) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.<br/>            Lecture/écriture **int**. |
| [`pictures_compression`](/slides/python-net/fr/aspose.slides.export/htmloptions/pictures_compression/) | Représente le niveau de compression des images |
| [`delete_pictures_cropped_areas`](/slides/python-net/fr/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | Un drapeau booléen indique si les parties recadrées restent dans le document. Si vrai les parties recadrées <br/>            seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un <br/>            fichier plus volumineux) |
| [`svg_responsive_layout`](/slides/python-net/fr/aspose.slides.export/htmloptions/svg_responsive_layout/) | True pour exclure les attributs de largeur et de hauteur du conteneur svg - cela rendra la mise en page réactive. False - sinon.<br/>            Lecture/écriture **bool**. |

### Voir aussi
* classe [`HtmlOptions`](/slides/python-net/fr/aspose.slides.export/htmloptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)