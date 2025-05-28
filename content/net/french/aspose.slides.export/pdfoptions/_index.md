---
title: PdfOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Pdf.
type: docs
weight: 3950
url: /fr/aspose.slides.export/pdfoptions/
---
## PdfOptions class

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Constructeur par défaut. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contient un ensemble d'indicateurs spécifiant les autorisations d'accès à accorder lorsque le document est ouvert avec un accès utilisateur. Voir[`PdfAccessPermissions`](../pdfaccesspermissions) . |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Renvoie ou définit un tableau de noms définis par l'utilisateur de familles de polices qu'Aspose.Slides devrait considérer comme communes. Lecture/écritureString []. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Applique la couleur transparente spécifiée à une image si`vrai` . |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si réglé surBoolean.true, pour chaque image en présentation, l'algorithme de compression le plus approprié sera choisi, ce qui conduira à la plus petite taille du document PDF résultant.  La sélection du meilleur taux de compression d'image est coûteuse en calcul et prend une quantité supplémentaire de RAM, et cette option estBoolean.false par défaut. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture[`PdfCompliance`](../pdfcompliance) . |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée dans le cas où la police source est introuvable. Lecture-écritureString . |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True pour dessiner un cadre noir autour de chaque diapositive. Lecture/écritureBoolean . |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Détermine si tous les caractères de la police doivent être incorporés ou uniquement un sous-ensemble utilisé. Lecture/écritureBoolean . |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Détermine si Aspose.Slides incorporera les polices communes pour le texte ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours incorporées. La liste des polices communes inclut les 14 polices de base du PDF et les polices supplémentaires spécifiées par l'utilisateur. Lire écrireBoolean . |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtient ou définit la couleur transparente de l'image. |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Renvoie ou définit une valeur déterminant la qualité des images JPEG dans le document PDF. Lecture/écritureByte . |
| [NotesCommentsLayouting](../../aspose.slides.export/pdfoptions/notescommentslayouting) { get; } | Fournit des options qui contrôlent la façon dont les notes et les commentaires sont placés dans le document exporté. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Définition du mot de passe utilisateur pour protéger le document PDF. Lecture/écritureString . |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour enregistrer les mises à jour de progression en pourcentage. Voir[`IProgressCallback`](../../aspose.slides/iprogresscallback) . |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écritureBoolean . |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure ou non des diapositives masquées. La valeur par défaut est`faux` . |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Renvoie ou définit une valeur déterminant la résolution des images dans le document PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture[`PdfTextCompression`](../pdftextcompression) . |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie des ensembles d'un objet qui reçoit des avertissements et décide si le processus de chargement va continuer ou sera abandonné. Lecture/écriture[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback) . |

### Voir également

* class [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
