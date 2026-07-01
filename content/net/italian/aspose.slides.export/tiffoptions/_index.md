---
title: TiffOptions
second_title: Aspose.Sildes per .NET API Reference
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.
type: docs
weight: 4550
url: /it/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata in formato TIFF.

```csharp
public class TiffOptions : SaveOptions, ITiffOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffOptions](tiffoptions)() | Costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BwConversionMode](../../aspose.slides.export/tiffoptions/bwconversionmode) { get; set; } | Specifica l'algoritmo per convertire un'immagine a colori in un'immagine in bianco e nero. Questa opzione verrà applicata solo se [`CompressionType`](./compressiontype) è impostato su CCITT4 o CCITT3 Lettura/Scrittura [`BlackWhiteConversionMode`](../blackwhiteconversionmode). Il valore predefinito è Default. |
| [CompressionType](../../aspose.slides.export/tiffoptions/compressiontype) { get; set; } | Specifica il tipo di compressione. Lettura/Scrittura [`TiffCompressionTypes`](../tiffcompressiontypes). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Restituisce o imposta il font usato nel caso in cui il font sorgente non sia trovato. Lettura/Scrittura String. |
| [DpiX](../../aspose.slides.export/tiffoptions/dpix) { get; set; } | Specifica la risoluzione orizzontale in punti per pollice. Lettura/Scrittura UInt32. |
| [DpiY](../../aspose.slides.export/tiffoptions/dpiy) { get; set; } | Specifica la risoluzione verticale in punti per pollice. Lettura/Scrittura UInt32. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Restituisce o imposta lo stile visivo del gradiente. Lettura/Scrittura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageSize](../../aspose.slides.export/tiffoptions/imagesize) { get; set; } | Specifica la dimensione di un'immagine TIFF generata. Il valore predefinito è 0x0, il che significa che le dimensioni dell'immagine generata verranno calcolate in base al valore della dimensione della diapositiva della presentazione. Lettura/Scrittura Size. |
| [InkOptions](../../aspose.slides.export/tiffoptions/inkoptions) { get; } | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [`IInkOptions`](../iinkoptions) |
| [PixelFormat](../../aspose.slides.export/tiffoptions/pixelformat) { get; set; } | Specifica il formato pixel per le immagini generate. Lettura/Scrittura [`ImagePixelFormat`](../imagepixelformat). |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Rappresenta un oggetto di callback per il salvataggio degli aggiornamenti di avanzamento in percentuale. Vedi [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/tiffoptions/showhiddenslides) { get; set; } | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/Scrittura Boolean. Il valore predefinito è **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/tiffoptions/slideslayoutoptions) { get; set; } | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/Scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Esempi

Il seguente esempio mostra come convertire PowerPoint in TIFF con dimensione predefinita.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    // Salva la presentazione in un documento TIFF
    presentation.Save("Tiffoutput_out.tiff", SaveFormat.Tiff);
}
```

Il seguente esempio mostra come convertire PowerPoint in TIFF con dimensione personalizzata.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file Presentation
using (Presentation pres = new Presentation("Convert_Tiff_Custom.pptx"))
{
    // Istanzia la classe TiffOptions
    TiffOptions opts = new TiffOptions();
    // Imposta il tipo di compressione
    opts.CompressionType = TiffCompressionTypes.Default;
    NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    opts.SlidesLayoutOption = notesOptions;
    // Tipi di compressione
    // Default - Specifica lo schema di compressione predefinito (LZW).
    // None - Specifica nessuna compressione.
    // CCITT3
    // CCITT4
    // LZW
    // RLE
    // La profondità dipende dal tipo di compressione e non può essere impostata manualmente.
    // L'unità di risoluzione è sempre uguale a “2” (punti per pollice)
    // Imposta DPI immagine
    opts.DpiX = 200;
    opts.DpiY = 100;
    // Imposta dimensione immagine
    opts.ImageSize = new Size(1728, 1078);
    // Salva la presentazione in TIFF con la dimensione immagine specificata
    pres.Save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
}
```

Il seguente esempio mostra come convertire PowerPoint in TIFF con formato pixel dell'immagine personalizzato.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file Presentation
using (Presentation presentation = new Presentation("DemoFile.pptx"))
{
    TiffOptions options = new TiffOptions();
    options.PixelFormat = ImagePixelFormat.Format8bppIndexed;
    /*
    ImagePixelFormat contiene i seguenti valori (come si può vedere dalla documentazione):
    Format1bppIndexed; // 1 bit per pixel, indicizzato.
    Format4bppIndexed; // 4 bit per pixel, indicizzato.
    Format8bppIndexed; // 8 bit per pixel, indicizzato.
    Format24bppRgb; // 24 bit per pixel, RGB.
    Format32bppArgb; // 32 bit per pixel, ARGB.
    */
    // Salva la presentazione in TIFF con la dimensione immagine specificata
    presentation.Save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
}
```

### Vedi anche

* classe [SaveOptions](../saveoptions)
* interfaccia [ITiffOptions](../itiffoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->