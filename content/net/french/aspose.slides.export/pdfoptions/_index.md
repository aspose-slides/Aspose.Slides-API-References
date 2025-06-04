---
title: PdfOptions
second_title: Aspose.Sildes pour .NET Référence API
description: Fournit des options qui contrôlent comment une présentation est enregistrée au format Pdf.
type: docs
weight: 4140
url: /fr/aspose.slides.export/pdfoptions/
---

## Classe PdfOptions

Fournit des options qui contrôlent comment une présentation est enregistrée au format Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contient un ensemble de drapeaux spécifiant quels droits d'accès doivent être accordés lors de l'ouverture du document avec un accès utilisateur. Voir [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Retourne ou définit un tableau de noms de familles de polices définies par l'utilisateur que Aspose.Slides doit considérer comme communes. Lecture/écriture String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Applique la couleur transparente spécifiée à une image si `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indique si la compression la plus efficace (au lieu de celle par défaut) pour chaque image doit être sélectionnée automatiquement. Si défini sur Boolean.true, pour chaque image dans la présentation, l'algorithme de compression le plus approprié sera choisi, ce qui conduira à une taille plus petite du document PDF résultant. La sélection du meilleur ratio de compression d'image est coûteuse en termes de calcul et nécessite une quantité supplémentaire de RAM, et cette option est Boolean.false par défaut. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Niveau de conformité souhaité pour le document PDF généré. Lecture/écriture [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Retourne ou définit la police utilisée si la police source n'est pas trouvée. Lecture/écriture String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Détermine si tous les caractères de la police doivent être intégrés ou seulement le sous-ensemble utilisé. Lecture/écriture Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Détermine si Aspose.Slides va intégrer des polices communes pour les textes ASCII (plage de codes 33..127). Les polices pour les codes de caractères supérieurs à 127 sont toujours intégrées. La liste des polices communes comprend les 14 polices de base de PDF et des polices spécifiées par l'utilisateur. Lecture/écriture Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Retourne ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Obtient ou définit la couleur transparente de l'image. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Vrai pour convertir toutes les données OLE de la présentation en fichiers intégrés dans le PDF résultant. Lecture/écriture Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Retourne ou définit une valeur déterminant la qualité des images JPEG à l'intérieur du document PDF. Lecture/écriture Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Définit le mot de passe utilisateur pour protéger le document PDF. Lecture/écriture String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour mettre à jour les informations de progression en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indique si le texte doit être rasterisé en tant que bitmap et enregistré dans le PDF lorsque la police ne prend pas en charge le style gras. Cette approche peut améliorer la qualité du texte dans le PDF résultant pour certaines polices. Lecture/écriture Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Vrai pour convertir tous les métadonnées utilisées dans une présentation en images PNG. Lecture/écriture Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure des diapositives cachées ou non. Par défaut, c'est `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Boolean. La valeur par défaut est **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Retourne ou définit une valeur déterminant la résolution des images à l'intérieur du document PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Spécifie le type de compression à utiliser pour tout le contenu textuel du document. Lecture/écriture [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Retourne un objet qui reçoit des avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L'exemple suivant montre comment convertir PowerPoint en PDF avec des options personnalisées.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancie la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Définit la qualité Jpeg
	pdfOptions.JpegQuality = 90;
	// Définit le comportement pour les métadonnées
	pdfOptions.SaveMetafilesAsPng = true;
	// Définit le niveau de compression du texte
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Définit la norme PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Enregistre la présentation en tant que PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

L'exemple suivant montre comment convertir PowerPoint en PDF avec des diapositives cachées.

```csharp
[C#]
// Instancie une classe Presentation qui représente un fichier PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancie la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Ajoute des diapositives cachées
	pdfOptions.ShowHiddenSlides = true;
	// Enregistre la présentation en tant que PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

L'exemple suivant montre comment convertir PowerPoint en PDF protégé par mot de passe.

```csharp
[C#]
// Instancie un objet Presentation qui représente un fichier PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instancie la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Définit le mot de passe PDF et les droits d'accès
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Enregistre la présentation en tant que PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

L'exemple suivant montre comment convertir PowerPoint en PDF avec des notes.

```csharp
[C#]
// Instancie un objet Presentation qui représente un fichier de présentation
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Définir le type et la taille de la diapositive
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Voir aussi

* classe [SaveOptions](../saveoptions)
* interface [IPdfOptions](../ipdfoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->