---
title: TiffOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.

**Héritage:**[`TiffOptions`](/slides/python-net/fr/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type TiffOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/tiffoptions/__init__/#) | Constructeur par défaut. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/tiffoptions/warning_callback/) | Retourne ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être arrêté.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/tiffoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/tiffoptions/default_regular_font/) | Retourne ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/tiffoptions/gradient_style/) | Retourne ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/tiffoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/tiffoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Encre dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/tiffoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives masquées ou non.<br/>            La valeur par défaut est `false`. |
| [`image_size`](/slides/python-net/fr/aspose.slides.export/tiffoptions/image_size/) | Spécifie la taille d'une image TIFF générée.<br/>            La valeur par défaut est 0x0, ce qui signifie que les tailles d'image générées seront calculées en fonction de la valeur de la taille des diapositives de la présentation.<br/>            Lecture/écriture [`Size`](/slides/python-net/fr/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/fr/aspose.slides.export/tiffoptions/dpi_x/) | Spécifie la résolution horizontale en points par pouce.<br/>            Lecture/écriture **int**. |
| [`dpi_y`](/slides/python-net/fr/aspose.slides.export/tiffoptions/dpi_y/) | Spécifie la résolution verticale en points par pouce.<br/>            Lecture/écriture **int**. |
| [`compression_type`](/slides/python-net/fr/aspose.slides.export/tiffoptions/compression_type/) | Spécifie le type de compression.<br/>            Lecture/écriture [`TiffCompressionTypes`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fr/aspose.slides.export/tiffoptions/pixel_format/) | Spécifie le format des pixels pour les images générées.<br/>            Lecture/écriture [`ImagePixelFormat`](/slides/python-net/fr/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/tiffoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/fr/aspose.slides.export/tiffoptions/bw_conversion_mode/) | Spécifie l'algorithme de conversion d'une image couleur en une image noir et blanc.<br/>            Cette option ne sera appliquée que si [`TiffOptions.compression_type`](/slides/python-net/fr/aspose.slides.export/tiffoptions/compression_type) <br/>            est défini sur [`TiffCompressionTypes.CCITT4`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes/CCITT4) ou [`TiffCompressionTypes.CCITT3`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lecture/écriture [`BlackWhiteConversionMode`](/slides/python-net/fr/aspose.slides.export/blackwhiteconversionmode).<br/>            La valeur par défaut est [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fr/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### Voir aussi
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* classe [`TiffOptions`](/slides/python-net/fr/aspose.slides.export/tiffoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)