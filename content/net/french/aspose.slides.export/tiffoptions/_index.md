---
title: TiffOptions
second_title: Référence API Aspose.Sildes pour .NET
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.
type: docs
weight: 4570
url: /fr/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Constructeurs

| Name | Description |
| --- | --- |
| [TiffOptions](tiffoptions)() | Constructeur par défaut. |

## Propriétés

| Name | Description |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Spécifie l'algorithme de conversion d'une image couleur en image noir et blanc. Cette option ne sera appliquée que si [`CompressionType`](./compressiontype) est défini sur CCITT4 ou CCITT3 Lecture/écriture [`BlackWhiteConversionMode`](../blackwhiteconversionmode). La valeur par défaut est Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Spécifie le type de compression. Lecture/écriture [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Lecture-écriture String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Spécifie la résolution horizontale en points par pouce. Lecture/écriture UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Spécifie la résolution verticale en points par pouce. Lecture/écriture UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Renvoie ou définit le style visuel du dégradé. Lecture/écriture [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Spécifie la taille d'une image TIFF générée. La valeur par défaut est 0x0, ce qui signifie que les tailles d'image générées seront calculées en fonction de la valeur de la taille des diapositives de la présentation. Lecture/écriture Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Fournit des options qui contrôlent l'apparence des objets Ink dans le document exporté. Lecture seule [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Spécifie le format de pixel pour les images générées. Lecture/écriture [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Représente un objet de rappel pour les mises à jour de progression de sauvegarde en pourcentage. Voir [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Spécifie s'il faut ignorer les hyperliens avec des appels JavaScript lors de l'enregistrement de la présentation. Lecture/écriture Boolean. La valeur par défaut est **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Exemples

L'exemple suivant montre comment convertir PowerPoint en TIFF avec la taille par défaut.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier de présentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Enregistrement de la présentation au document TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

L'exemple suivant montre comment convertir PowerPoint en TIFF avec une taille personnalisée.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Instancier la classe TiffOptions
    TiffOptions opts = new TiffOptions();
    // Définir le type de compression
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Types de compression
    // Default - Spécifie le schéma de compression par défaut (LZW).
    // None - Indique aucune compression.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // La profondeur dépend du type de compression et ne peut pas être définie manuellement.
    // L'unité de résolution  est toujours égale à "2" (points par pouce)
    // Définir le DPI de l'image
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Définir la taille de l'image
    opts.ImageSize = new Size(1728, 1078);
    // Enregistrer la présentation au format TIFF avec la taille d'image spécifiée
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

L'exemple suivant montre comment convertir PowerPoint en TIFF avec un format de pixel d'image personnalisé.

```csharp
[C#]
// Instancier un objet Presentation qui représente un fichier Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contient les valeurs suivantes (comme indiqué dans la documentation) :
    Format1bppIndexed; // 1 bit par pixel, indexé.
    Format4bppIndexed; // 4 bits par pixel, indexé.
    Format8bppIndexed; // 8 bits par pixel, indexé.
    Format24bppRgb; // 24 bits par pixel, RVB.
    Format32bppArgb; // 32 bits par pixel, ARGB.
    */
    // Enregistrer la présentation au format TIFF avec la taille d'image spécifiée
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Voir aussi

* classe [SaveOptions](../saveoptions)
* interface [ITiffOptions](../itiffoptions)
* espace de noms [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->