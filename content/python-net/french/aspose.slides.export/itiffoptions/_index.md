---
title: ITiffOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/itiffoptions/
---
## ITiffOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.

Le type ITiffOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`image_size`](/slides/python-net/fr/aspose.slides.export/itiffoptions/image_size/) | Spécifie la taille d'une image TIFF générée.<br/>            Valeur par défaut est 0x0, ce qui signifie que les tailles d'image générées seront calculées en fonction de la taille des diapositives de la présentation.<br/>            Lecture/écriture [`Size`](/slides/python-net/fr/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/fr/aspose.slides.export/itiffoptions/dpi_x/) | Spécifie la résolution horizontale en points par pouce.<br/>            Lecture/écriture **int**. |
| [`dpi_y`](/slides/python-net/fr/aspose.slides.export/itiffoptions/dpi_y/) | Spécifie la résolution verticale en points par pouce.<br/>            Lecture/écriture **int**. |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/itiffoptions/show_hidden_slides/) | Indique si le document généré doit inclure les diapositives masquées ou non.<br/>            Valeur par défaut est `false`. |
| [`compression_type`](/slides/python-net/fr/aspose.slides.export/itiffoptions/compression_type/) | Spécifie le type de compression.<br/>            Lecture/écriture [`TiffCompressionTypes`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/fr/aspose.slides.export/itiffoptions/pixel_format/) | Spécifie le format de pixel pour les images générées.<br/>            Lecture/écriture [`ImagePixelFormat`](/slides/python-net/fr/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/fr/aspose.slides.export/itiffoptions/slides_layout_options/) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](/slides/python-net/fr/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/fr/aspose.slides.export/itiffoptions/bw_conversion_mode/) | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc.<br/>            Cette option ne sera appliquée que si [`ITiffOptions.compression_type`](/slides/python-net/fr/aspose.slides.export/itiffoptions/compression_type) <br/>            est défini sur [`TiffCompressionTypes.CCITT4`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes/CCITT4) ou [`TiffCompressionTypes.CCITT3`](/slides/python-net/fr/aspose.slides.export/tiffcompressiontypes/CCITT3)<br/>            Lecture/écriture [`BlackWhiteConversionMode`](/slides/python-net/fr/aspose.slides.export/blackwhiteconversionmode).<br/>            La valeur par défaut est [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/fr/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |
| [`ink_options`](/slides/python-net/fr/aspose.slides.export/itiffoptions/ink_options/) | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté.<br/>            Lecture seule [`IInkOptions`](/slides/python-net/fr/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)