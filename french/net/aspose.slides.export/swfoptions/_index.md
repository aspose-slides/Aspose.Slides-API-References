---
title: SwfOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Swf.
type: docs
weight: 4120
url: /fr/net/aspose.slides.export/swfoptions/
---
## SwfOptions class

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Swf.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SwfOptions](swfoptions)() | Constructeur par défaut. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est`vrai` . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée dans le cas où la police source est introuvable. Lecture-écritureString . |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | Activer/désactiver le menu contextuel. La valeur par défaut est true. |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Spécifie la qualité des images JPEG. La valeur par défaut est 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Image qui sera affichée sous forme de logo dans le coin supérieur droit de la visionneuse. L'image doit être une image PNG de 32 x 64 pixels, sinon le logo peut s'afficher de manière incorrecte. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Obtient ou définit l'adresse complète du lien hypertexte d'un logo. N'a d'effet que si un[`LogoImageBytes`](./logoimagebytes) est spécifié. |
| [NotesCommentsLayouting](../../aspose.slides.export/swfoptions/notescommentslayouting) { get; } | Fournit des options qui contrôlent la façon dont les notes et les commentaires sont placés dans le document exporté. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Afficher/masquer le volet inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure ou non des diapositives masquées. La valeur par défaut est`faux` . |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Afficher/masquer le volet de gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Afficher/masquer le stepper de la page. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Afficher/masquer tout le volet supérieur. Peut être remplacé dans les flashvars. La valeur par défaut est true. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Commencez avec le volet de gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Spécifie si le document SWF généré doit inclure ou non la visionneuse de documents intégrée. La valeur par défaut est`vrai` . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie des ensembles d'un objet qui reçoit des avertissements et décide si le processus de chargement va continuer ou sera abandonné. Lecture/écriture[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Voir également

* class [SaveOptions](../saveoptions)
* interface [ISwfOptions](../iswfoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->