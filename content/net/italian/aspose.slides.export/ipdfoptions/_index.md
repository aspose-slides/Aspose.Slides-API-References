---
title: IPdfOptions
second_title: Riferimento API Aspose.Sildes per .NET
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.
type: docs
weight: 3980
url: /it/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfaccia

Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento viene aperto con accesso utente. Vedi [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Restituisce o imposta un array di nomi di famiglie di caratteri definiti dall'utente che Aspose.Slides deve considerare comuni. Lettura/scrittura String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Applica il colore trasparente specificato a un'immagine se `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Restituisce l'interfaccia ISaveOptions. Solo lettura [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostata su Boolean.true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante. La selezione del miglior rapporto di compressione dell'immagine è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è Boolean.false per impostazione predefinita. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Livello di conformità desiderato per il documento PDF generato. Lettura/scrittura [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True per disegnare una cornice nera attorno a ogni diapositiva. Lettura/scrittura Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. Lettura/scrittura Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True per incorporare i caratteri TrueType per i caratteri ASCII 32-127. I font per i codici di carattere superiori a 127 sono sempre incorporati. Lettura/scrittura Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Ottiene o imposta il colore trasparente dell'immagine. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura/scrittura Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Restituisce o imposta un valore che determina la qualità delle immagini JPEG nel documento PDF. Lettura/scrittura Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Impostazione della password utente per proteggere il documento PDF. Lettura/scrittura String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font. Lettura/scrittura Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. Lettura/scrittura Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Specifica se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Restituisce o imposta un valore che determina la risoluzione delle immagini nel documento PDF. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Specifica il tipo di compressione da utilizzare per tutto il contenuto testuale nel documento. Lettura/scrittura [`PdfTextCompression`](../pdftextcompression). |

### Vedi anche

* interfaccia [ISaveOptions](../isaveoptions)
* spazio dei nomi [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->