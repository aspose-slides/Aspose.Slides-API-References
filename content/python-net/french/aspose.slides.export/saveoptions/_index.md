---
title: SaveOptions class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/saveoptions/
---
## SaveOptions classe

Classe abstraite avec des options qui contrôlent la façon dont une présentation est enregistrée.

Le type SaveOptions expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/saveoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu.<br/>Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/saveoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage.<br/>Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/saveoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>Lecture/écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/saveoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/saveoptions/skip_java_script_links/) | Spécifie si les hyperliens avec des appels JavaScript doivent être ignorés lors de l'enregistrement de la présentation.<br/>Lecture/écriture **bool**. La valeur par défaut est **false**. |

### Voir aussi
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)