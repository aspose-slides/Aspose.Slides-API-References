---
title: PptxOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/pptxoptions/
---
## PptxOptions classe

Représente les options pour enregistrer les présentations OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

**Inheritance:**[`PptxOptions`](/slides/python-net/fr/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type PptxOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/pptxoptions/__init__/#) | Crée une nouvelle instance de PptxOptions |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/pptxoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/pptxoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/pptxoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/pptxoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/pptxoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`conformance`](/slides/python-net/fr/aspose.slides.export/pptxoptions/conformance/) | Spécifie la classe de conformité à laquelle le document Presentation se conforme.<br/>            La valeur par défaut est [`Conformance.ECMA_376_2006`](/slides/python-net/fr/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/fr/aspose.slides.export/pptxoptions/zip_64_mode/) | Spécifie si le format ZIP64 est utilisé pour le document Presentation.<br/>            La valeur par défaut est [`Zip64Mode.IF_NECESSARY`](/slides/python-net/fr/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/fr/aspose.slides.export/pptxoptions/refresh_thumbnail/) | Spécifie si la vignette de la présentation sera rafraîchie.<br/>            Lecture/écriture **bool**.<br/>            Valeur par défaut **true**. |
| [`compression_level`](/slides/python-net/fr/aspose.slides.export/pptxoptions/compression_level/) | Spécifie le niveau de compression utilisé lors de l'enregistrement du document de présentation.<br/>            La valeur par défaut est [`CompressionLevel.LEVEL6`](/slides/python-net/fr/aspose.slides.export/compressionlevel/LEVEL6). |


### Voir aussi
* classe [`PptxOptions`](/slides/python-net/fr/aspose.slides.export/pptxoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)