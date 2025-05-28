---
title: SVGOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente des options SVG.
type: docs
weight: 4240
url: /fr/aspose.slides.export/svgoptions/
---

## Classe SVGOptions

Représente des options SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialise une nouvelle instance de la classe SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet contrôleur d'intégration de lien. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Renvoie les paramètres par défaut. Lecture seule [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Renvoie les paramètres pour la génération du fichier SVG le plus simple et le plus petit. Lecture seule [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Renvoie les paramètres pour la génération du fichier SVG la plus précise. Lecture seule [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée au cas où la police source n'est pas trouvée. Lecture/écriture String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Un indicateur booléen qui indique si les parties recadrées restent en tant que partie du document. Si vrai, les parties recadrées seront supprimées, si faux, elles seront sérialisées dans le document (ce qui peut éventuellement conduire à un fichier plus volumineux). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Détermine si le texte 3D est désactivé dans SVG. Lecture/écriture Booléen. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque défini sur `true`, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Désactive le fractionnement des dégradés FromCornerX et FromCenter. Lecture/écriture Booléen. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 n'a pas la capacité de définir des marges pour les marqueurs. Le moteur d'écriture SVG d'Aspose.Slides a une solution à ce problème : il recadre l'extrémité de la ligne avec une flèche, de sorte que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture/écriture Booléen. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Détermine la façon de gérer les polices chargées externément. Lecture/écriture [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Détermine la qualité de l'encodage JPEG. Lecture/écriture Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métachamps. Lecture/écriture Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Représente le niveau de compression des images |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion de formes. Lecture/écriture [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Booléen. La valeur par défaut est **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Détermine s'il faut effectuer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture Booléen. La valeur par défaut est vraie. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Détermine si le cadre de texte sera inclus dans une zone de rendu ou non. Lecture/écriture Booléen. La valeur par défaut est fausse. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Détermine si le texte sur une diapositive sera enregistré sous forme de graphique. Lecture/écriture Booléen. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continuera ou sera abandonné. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir Aussi

* classe [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NE MODIFIEZ PAS : généré par xmldocmd pour Aspose.Slides.dll -->