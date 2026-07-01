---
title: PdfOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Fornisce opzioni che controllano come una presentazione viene salvata nel formato Pdf.
type: docs
weight: 4310
url: /it/aspose.slides.export/pdfoptions/
---
## PdfOptions classe

Fornisce opzioni che controllano come una presentazione viene salvata nel formato Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfOptions](pdfoptions)() | Costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Contiene un insieme di flag che specificano quali autorizzazioni di accesso dovrebbero essere concesse quando il documento viene aperto con accesso utente. Vedi [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Restituisce o imposta un array di nomi di famiglie di caratteri definiti dall'utente che Aspose.Slides dovrebbe considerare comuni. Lettura/scrittura String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Applica il colore trasparente specificato a un'immagine se `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostata su Boolean.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. La selezione del miglior rapporto di compressione dell'immagine è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è Boolean.false per impostazione predefinita. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Livello di conformità desiderato per il documento PDF generato. Lettura/scrittura [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Restituisce o imposta il carattere usato nel caso in cui il carattere sorgente non sia trovato. Lettura-scrittura String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True per disegnare una cornice nera attorno a ciascuna diapositiva. Lettura/scrittura Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. Lettura/scrittura Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Determina se Aspose.Slides incorporerà i font comuni per il testo ASCII (intervallo di codici 33..127). I font per i codici dei caratteri superiori a 127 sono sempre incorporati. L'elenco dei font comuni include i 14 font base del PDF e font aggiuntivi specificati dall'utente. Lettura/scrittura Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Restituisce o imposta lo stile visivo del gradiente. Lettura/scrittura [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Ottiene o imposta il colore trasparente dell'immagine. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura/scrittura Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/scrittura Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Impostazione della password utente per proteggere il documento PDF. Lettura/scrittura String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Rappresenta un oggetto di callback per gli aggiornamenti di avanzamento del salvataggio in percentuale. Vedi [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il carattere non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni caratteri. Lettura/scrittura Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. Lettura/scrittura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Specifica se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Specifica se saltare i collegamenti ipertestuali con chiamate JavaScript durante il salvataggio della presentazione. Lettura/scrittura Boolean. Il valore predefinito è **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale nel documento. Lettura/scrittura [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Restituisce o imposta un oggetto che riceve avvisi e decide se il processo di caricamento continuerà o sarà interrotto. Lettura/scrittura [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Esempi

Il seguente esempio mostra come convertire PowerPoint in PDF con opzioni personalizzate.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Istanzia la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Imposta la qualità JPEG
	pdfOptions.JpegQuality = 90;
	// Imposta il comportamento per i metafili
	pdfOptions.SaveMetafilesAsPng = true;
	// Imposta il livello di compressione del testo
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definisce lo standard PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Salva la presentazione come PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Il seguente esempio mostra come convertire PowerPoint in PDF con diapositive nascoste.

```csharp
[C#]
// Istanzia una classe Presentation che rappresenta un file PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Istanzia la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Aggiunge diapositive nascoste
	pdfOptions.ShowHiddenSlides = true;
	// Salva la presentazione come PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Il seguente esempio mostra come convertire PowerPoint in PDF protetto da password.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Istanzia la classe PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Imposta la password PDF e le autorizzazioni di accesso
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Salva la presentazione come PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Il seguente esempio mostra come convertire PowerPoint in PDF con note.

```csharp
[C#]
// Istanzia un oggetto Presentation che rappresenta un file di presentazione
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Imposta il tipo e le dimensioni della diapositiva
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Vedi anche

* classe [SaveOptions](../saveoptions)
* interfaccia [IPdfOptions](../ipdfoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->