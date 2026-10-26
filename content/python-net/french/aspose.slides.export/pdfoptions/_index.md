---
title: PdfOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Pdf.

**Héritage:**[`PdfOptions`](/slides/python-net/fr/aspose.slides.export/pdfoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type PdfOptions expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/pdfoptions/__init__/#) | Constructeur par défaut. |

## Propriétés

| Property | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/pdfoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/pdfoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression d'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/pdfoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/pdfoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/pdfoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/pdfoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/pdfoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/pdfoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives cachées ou non.<br/>            La valeur par défaut est `false`. |
| [`text_compression`](/slides/python-net/fr/aspose.slides.export/pdfoptions/text_compression/) | Spécifie le type de compression à utiliser pour tout le contenu textuel du document.<br/>            Lecture/écriture [`PdfTextCompression`](/slides/python-net/fr/aspose.slides.export/pdftextcompression). |
| [`best_images_compression_ratio`](/slides/python-net/fr/aspose.slides.export/pdfoptions/best_images_compression_ratio/) | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée <br/>            automatiquement. Si la valeur est **bool**.true, pour chaque image de la présentation l'algorithme de compression le plus approprié sera choisi, ce qui entraînera une taille plus petite du document PDF résultant.<br/>            La sélection du meilleur taux de compression d'image est gourmande en calculs et consomme <br/>            une quantité supplémentaire de RAM, et cette option est **bool**.false par défaut. |
| [`embed_true_type_fonts_for_ascii`](/slides/python-net/fr/aspose.slides.export/pdfoptions/embed_true_type_fonts_for_ascii/) | Détermine si Aspose.Slides intègrera les polices communes pour le texte ASCII (plage de codes 33..127).<br/>            Les polices pour les codes de caractères supérieurs à 127 sont toujours intégrées.<br/>            La liste des polices communes comprend les 14 polices de base du PDF et des polices supplémentaires spécifiées par l'utilisateur.<br/>            Lecture/écriture **bool**. |
| [`additional_common_font_families`](/slides/python-net/fr/aspose.slides.export/pdfoptions/additional_common_font_families/) | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communes.<br/>            Lecture/écriture **str**[]. |
| [`embed_full_fonts`](/slides/python-net/fr/aspose.slides.export/pdfoptions/embed_full_fonts/) | Détermine si tous les caractères de la police doivent être intégrés ou seulement le sous-ensemble utilisé.<br/>            Lecture/écriture **bool**. |
| [`rasterize_unsupported_font_styles`](/slides/python-net/fr/aspose.slides.export/pdfoptions/rasterize_unsupported_font_styles/) | Indique si le texte doit être rasterisé en bitmap et enregistré dans le PDF lorsque la police ne supporte pas le style gras.<br/>            Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices.<br/>            Lecture/écriture **bool**. |
| [`jpeg_quality`](/slides/python-net/fr/aspose.slides.export/pdfoptions/jpeg_quality/) | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF.<br/>            Lecture/écriture **int**. |
| [`compliance`](/slides/python-net/fr/aspose.slides.export/pdfoptions/compliance/) | Niveau de conformité souhaité pour le document PDF généré.<br/>            Lecture/écriture [`PdfCompliance`](/slides/python-net/fr/aspose.slides.export/pdfcompliance). |
| [`password`](/slides/python-net/fr/aspose.slides.export/pdfoptions/password/) | Définition du mot de passe utilisateur pour protéger le document PDF.<br/>            Lecture/écriture **str**. |
| [`access_permissions`](/slides/python-net/fr/aspose.slides.export/pdfoptions/access_permissions/) | Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lors de l'ouverture du document avec accès utilisateur.<br/>            Voir [`PdfAccessPermissions`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions). |
| [`save_metafiles_as_png`](/slides/python-net/fr/aspose.slides.export/pdfoptions/save_metafiles_as_png/) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG.<br/>            Lecture/écriture **bool**. |
| [`sufficient_resolution`](/slides/python-net/fr/aspose.slides.export/pdfoptions/sufficient_resolution/) | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF.<br/>            <br/>La propriété affecte la taille du fichier, le temps d'exportation et la qualité de l'image.<br/><br/><br/>La valeur par défaut est **96**.<br/><br/><br/>            Lecture/écriture **float**. |
| [`draw_slides_frame`](/slides/python-net/fr/aspose.slides.export/pdfoptions/draw_slides_frame/) | Vrai pour dessiner un cadre noir autour de chaque diapositive.<br/>             Lecture/écriture **bool**. |
| [`image_transparent_color`](/slides/python-net/fr/aspose.slides.export/pdfoptions/image_transparent_color/) | Obtient ou définit la couleur transparente de l'image. |
| [`apply_image_transparent`](/slides/python-net/fr/aspose.slides.export/pdfoptions/apply_image_transparent/) | Applique la couleur transparente spécifiée à une image si `true`. |
| [`include_ole_data`](/slides/python-net/fr/aspose.slides.export/pdfoptions/include_ole_data/) | Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant.<br/>            Lecture/écriture **bool**. |

### Voir aussi
* classe [`PdfOptions`](/slides/python-net/fr/aspose.slides.export/pdfoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)