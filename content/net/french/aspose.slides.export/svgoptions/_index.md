---
title: SVGOptions
second_title: Référence API Aspose.Sildes pour .NET
description: Représente les options SVG.
type: docs
weight: 4430
url: /fr/aspose.slides.export/svgoptions/
---
## classe SVGOptions

Représente les options SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Initialise une nouvelle instance de la classe SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Initialise une nouvelle instance de la classe SVGOptions en spécifiant l'objet ILinkEmbedController. |

## Propriétés

| Nom | Description |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Renvoie les paramètres par défaut. Lecture seule [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Renvoie les paramètres pour la génération du fichier SVG la plus simple et la plus petite. Lecture seule [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Renvoie les paramètres pour la génération du fichier SVG la plus précise. Lecture seule [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Lecture/écriture String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Un indicateur booléen indique si les parties recadrées restent dans le document. Si true, les parties recadrées seront supprimées, si false elles seront sérialisées dans le document (ce qui peut éventuellement entraîner un fichier plus volumineux). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Détermine si le texte 3D est désactivé dans le SVG. Lecture/écriture Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Obtient ou définit une valeur indiquant si le texte est rendu sans utiliser de ligatures. Lorsque la valeur est `true`, les ligatures seront désactivées dans la sortie rendue. Par défaut, cette propriété est définie sur `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Désactive la division des dégradés FromCornerX et FromCenter. Lecture/écriture Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 ne permet pas de définir des retraits pour les marqueurs. Le moteur d'écriture SVG d'Aspose.Slides propose une solution de contournement : il coupe l'extrémité de la ligne avec flèche, afin que la ligne ne chevauche pas les marqueurs. Cette option désactive ce comportement. Lecture/écriture Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Détermine une façon de gérer les polices chargées externement. Lecture/écriture [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Détermine la qualité d'encodage JPEG. Lecture/écriture Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Renvoie ou définit la limite de résolution inférieure pour la rasterisation des métafichiers. Lecture/écriture Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Représente le niveau de compression des images |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Renvoie et définit une interface de rappel qui permet à l'utilisateur de contrôler la conversion des formes. Lecture/écriture [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens contenant des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Boolean. La valeur par défaut est **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Détermine s'il faut appliquer la rotation spécifiée de la forme lors du rendu ou non. Lecture/écriture Boolean. La valeur par défaut est true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Détermine si le cadre de texte sera inclus dans la zone de rendu ou non. Lecture/écriture Boolean. La valeur par défaut est false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Détermine si le texte d'une diapositive sera enregistré sous forme d'images. Lecture/écriture Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit continuer ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Voir aussi

* classe [SaveOptions](../saveoptions)
* interface [ISVGOptions](../isvgoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->