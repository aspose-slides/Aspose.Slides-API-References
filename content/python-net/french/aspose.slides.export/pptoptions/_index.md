---
title: PptOptions class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.export/pptoptions/
---
## PptOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format PPT.

**Héritage:**[`PptOptions`](/slides/python-net/fr/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)

Le type PptOptions expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.export/pptoptions/__init__/#) |  |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`warning_callback`](/slides/python-net/fr/aspose.slides.export/pptoptions/warning_callback/) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné.<br/>            Lecture/écriture [`IWarningCallback`](/slides/python-net/fr/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/fr/aspose.slides.export/pptoptions/progress_callback/) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage.<br/>            Voir [`IProgressCallback`](/slides/python-net/fr/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/fr/aspose.slides.export/pptoptions/default_regular_font/) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée.<br/>            Lecture-écriture **str**. |
| [`gradient_style`](/slides/python-net/fr/aspose.slides.export/pptoptions/gradient_style/) | Renvoie ou définit le style visuel du dégradé.<br/>            Lecture/écriture [`GradientStyle`](/slides/python-net/fr/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/fr/aspose.slides.export/pptoptions/skip_java_script_links/) | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. <br/>            Lecture/écriture **bool**. La valeur par défaut est **false**. |
| [`root_directory_clsid`](/slides/python-net/fr/aspose.slides.export/pptoptions/root_directory_clsid/) | Représente le GUID (CLSID) de la classe d'objet qui est stocké dans l'entrée du répertoire racine. Peut être utilisé pour l'activation COM<br/>            de l'application du document.<br/>            La valeur par défaut est '64818D11-4F9B-11CF-86EA-00AA00B929E8' qui correspond à 'Microsoft Powerpoint.Slide.8'. |


### Voir aussi
* classe [`PptOptions`](/slides/python-net/fr/aspose.slides.export/pptoptions)
* classe [`SaveOptions`](/slides/python-net/fr/aspose.slides.export/saveoptions)
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)