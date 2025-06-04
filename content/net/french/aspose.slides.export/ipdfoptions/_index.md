---
title: IPdfOptions
second_title: Référence de l'API Aspose.Slides pour .NET
description: Fournit des options qui contrôlent comment une présentation est enregistrée au format Pdf.
type: docs
weight: 3830
url: /fr/aspose.slides.export/ipdfoptions/
---

## Interface IPdfOptions

Fournit des options qui contrôlent comment une présentation est enregistrée au format Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contient un ensemble de drapeaux spécifiant quelles permissions d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur. Voir [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Renvoie ou définit un tableau de noms de familles de polices définis par l'utilisateur que Aspose.Slides doit considérer comme communs. Lecture/écriture String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Applique la couleur transparente spécifiée à une image si `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Renvoie l'interface ISaveOptions. Lecture seule [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si défini sur Boolean.true, pour chaque image dans la présentation l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultant. La sélection du meilleur ratio de compression d'image est coûteuse en calcul et nécessite une quantité supplémentaire de RAM, et cette option est Boolean.false par défaut. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Détermine si tous les caractères de la police doivent être intégrés ou seulement le sous-ensemble utilisé. Lecture/écriture Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Vrai pour intégrer des polices True Type pour les caractères ASCII 32-127. Les polices pour les codes de caractères supérieurs à 127 sont toujours intégrées. Lecture/écriture Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Obtient ou définit la couleur transparente de l'image. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Lecture/écriture Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Renvoie ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Définit un mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indique si le texte doit être rasterisé en tant que bitmap et enregistré au format PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Vrai pour convertir tous les métadonnées utilisées dans une présentation en images PNG. Lecture/écriture Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. La valeur par défaut est `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Renvoie ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Spécifie le type de compression à utiliser pour tout le contenu textuel dans le document. Lecture/écriture [`PdfTextCompression`](../pdftextcompression). |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->