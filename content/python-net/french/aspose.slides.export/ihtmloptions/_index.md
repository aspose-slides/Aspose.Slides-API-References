---
title: IHtmlOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions classe

Représente des options d'exportation HTML.

Le type IHtmlOptions expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`html_formatter`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/html_formatter/) | Renvoie ou définit le modèle HTML.<br/>            Lecture/écriture [`IHtmlFormatter`](/slides/python-net/fr/aspose.slides.export/ihtmlformatter). |
| [`slide_image_format`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/slide_image_format/) | Renvoie ou définit les options de format d'image des diapositives.<br/>            Lecture/écriture [`ISlideImageFormat`](/slides/python-net/fr/aspose.slides.export/islideimageformat). |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives masquées ou non.<br/>            La valeur par défaut est `false`. |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/jpeg_quality/) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.<br/>            Lecture/écriture **int**. |
| [`pictures_compression`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/pictures_compression/) | Représente le niveau de compression des images<br/>            Lecture/écriture [`IHtmlOptions.pictures_compression`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/pictures_compression). |
| [`delete_pictures_cropped_areas`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | Un indicateur booléen indique si les parties recadrées restent présentes dans le document. Si vrai, les parties recadrées <br/>            seront supprimées, si faux elles seront sérialisées dans le document (ce qui peut éventuellement conduire à un <br/>            fichier plus volumineux)<br/>            Lecture/écriture **bool**. |
| [`svg_responsive_layout`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | Vrai pour exclure les attributs de largeur et de hauteur du conteneur SVG - cela rendra la mise en page réactive. Faux - sinon.<br/>            Lecture/écriture **bool**. |
| [`disable_font_ligatures`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures.<br/>            Lorsqu'elle est définie sur `true`, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur `false`. |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)