---
title: MarkdownSaveOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/markdownsaveoptions/
---
## classe MarkdownSaveOptions

Représente les options qui contrôlent comment la présentation doit être enregistrée en markdown.

**Héritage:**[`MarkdownSaveOptions`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type MarkdownSaveOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/__init__/#) | Ctor. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture/écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation.<br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`export_type`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/export_type/) | Spécifie la spécification markdown pour convertir la présentation.<br/>            La valeur par défaut est `TextOnly`. |
| [`base_path`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/base_path/) | Spécifie le chemin de base où le document avec les ressources sera enregistré.<br/>            La valeur par défaut est le répertoire actuel de l'application. |
| [`images_save_folder_name`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | Spécifie le nom du dossier pour enregistrer les images.<br/>            La valeur par défaut est `Images`. |
| [`new_line_type`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/new_line_type/) | Spécifie si le document généré doit avoir des retours à la ligne \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows).<br/>            La valeur par défaut est `Unix`. |
| [`show_comments`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/show_comments/) | Spécifie si le document généré doit afficher les commentaires ou non.<br/>            La valeur par défaut est `false`. |
| [`show_hidden_slides`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | Spécifie si le document généré doit inclure les diapositives cachées ou non.<br/>            La valeur par défaut est `false`. |
| [`show_slide_number`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/show_slide_number/) | Spécifie si le document généré doit afficher le numéro de chaque diapositive ou non.<br/>            La valeur par défaut est `false`. |
| [`flavor`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/flavor/) | Spécifie la spécification markdown pour convertir la présentation.<br/>            La valeur par défaut est `Multi-markdown`. |
| [`slide_number_format`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Renvoie ou définit la chaîne de format utilisée pour les en-têtes de numéro de diapositive dans la sortie Markdown.<br/>            Le format doit inclure l'espace réservé \"{0}\", qui sera remplacé par l'index de la diapositive lors de l'exportation.<br/>            Exemple : \"# Slide {0}\" produira \"# Slide 1\", \"# Slide 2\", etc. |
| [`handle_repeated_spaces`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | Si défini sur `true`, supprime les lignes vides ou contenant uniquement des espaces du résultat Markdown final.<br/>            La valeur par défaut est `false`. |

### Voir aussi
* classe [`MarkdownSaveOptions`](/slides/python-net/fr/aspose.slides.export/markdownsaveoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)