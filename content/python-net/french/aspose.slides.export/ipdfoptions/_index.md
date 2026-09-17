---
title: IPdfOptions class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.export/ipdfoptions/
---
## IPdfOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Pdf.

Le type IPdfOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`text_compression`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/text_compression/) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document.<br/>            Lecture/écriture [`PdfTextCompression`](/slides/python-net/fr/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/best_images_compression_ratio/) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée <br/>            automatiquement. Si elle est définie sur **bool**.true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant. <br/>            La sélection du meilleur taux de compression d'image est coûteuse en calcul et nécessite <br/>            une quantité supplémentaire de RAM, et cette option est **bool**.false par défaut. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/embed_true_type_fonts_for_ascii/) | Vrai pour intégrer les polices TrueType pour les caractères ASCII 32-127.<br/>            Les polices pour les codes de caractères supérieurs à 127 sont toujours intégrées.<br/>            Lecture/écriture **bool**. |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives masquées ou non.<br/>            Par défaut, `false`. |
| [`additional_common_font_families`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/additional_common_font_families/) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme courants.<br/>            Lecture/écriture **str**[]. |
| [`embed_full_fonts`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/embed_full_fonts/) | Détermine si tous les caractères de la police doivent être intégrés ou seulement le sous-ensemble utilisé.<br/>            Lecture/écriture **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/rasterize_unsupported_font_styles/) | Indique si le texte doit être rasterisé en bitmap et enregistré en PDF lorsque la police ne prend pas en charge le style gras.<br/>            Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices.<br/>            Lecture/écriture **bool**. |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/jpeg_quality/) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.<br/>            Lecture/écriture **int**. |
| [`compliance`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/compliance/) | Niveau de conformité souhaité pour le document PDF généré.<br/>            Lecture/écriture [`PdfCompliance`](/slides/python-net/fr/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/password/) | Définition du mot de passe utilisateur pour protéger le document PDF. <br/>            Lecture/écriture **str**. |
| [`access_permissions`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/access_permissions/) | Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsque le document est ouvert<br/>            avec un accès utilisateur. Voir [`PdfAccessPermissions`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/save_metafiles_as_png/) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG.<br/>            Lecture/écriture **bool**. |
| [`sufficient_resolution`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/sufficient_resolution/) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF.<br/>            <br/>La propriété affecte la taille du fichier, le temps d'exportation et la qualité de l'image.<br/><br/><br/>La valeur par défaut est **96** .<br/><br/><br/>            Lecture/écriture **float**. |
| [`draw_slides_frame`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/draw_slides_frame/) | Vrai pour dessiner un cadre noir autour de chaque diapositive.<br/>             Lecture/écriture **bool**. |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`image_transparent_color`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/image_transparent_color/) | Obtient ou définit la couleur transparente de l'image. |
| [`apply_image_transparent`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/apply_image_transparent/) | Applique la couleur transparente spécifiée à une image si `true`. |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`include_ole_data`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/include_ole_data/) | Vrai pour convertir toutes les données OLE de la présentation en fichiers embarqués dans le PDF résultant.<br/>            Lecture/écriture **bool**. |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/ipdfoptions/skip_java_script_links/) |  |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)