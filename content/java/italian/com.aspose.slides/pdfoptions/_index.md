---
title: PdfOptions
second_title: Riferimento API di Aspose.Slides per Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.
type: docs
url: /it/com.aspose.slides/pdfoptions/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Sets the Jpeg quality
>      pdfOptions.setJpegQuality((byte)90);
>      // Sets the behavior for metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Sets the text compression level
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Defines the PDF standard
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instantiates a Presentation class that represents a PowerPoint file
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Adds hidden slides
>      pdfOptions.setShowHiddenSlides(true);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instantiates a Presentation object that represents a PowerPoint file
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Sets PDF password and access permissions
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Saves the presentation as a PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Setting Slide Type and Size
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Costruttore predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere diapositive nascoste o meno. |
| [getTextCompression()](#getTextCompression--) | Specifica il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specifica il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Determina se Aspose.Slides incorporerà i font comuni per il testo ASCII (intervallo di codici 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Determina se Aspose.Slides incorporerà i font comuni per il testo ASCII (intervallo di codici 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides dovrebbe considerare comuni. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides dovrebbe considerare comuni. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. |
| [getJpegQuality()](#getJpegQuality--) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [getCompliance()](#getCompliance--) | Livello di conformità desiderato per il documento PDF generato. |
| [setCompliance(int value)](#setCompliance-int-) | Livello di conformità desiderato per il documento PDF generato. |
| [getPassword()](#getPassword--) | Impostazione della password utente per proteggere il documento PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Impostazione della password utente per proteggere il documento PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Vero per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Vero per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Vero per disegnare una cornice nera attorno a ogni diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Vero per disegnare una cornice nera attorno a ogni diapositiva. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Ottiene o imposta il colore trasparente dell'immagine. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Ottiene o imposta il colore trasparente dell'immagine. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applica il colore trasparente specificato a un'immagine se vero. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applica il colore trasparente specificato a un'immagine se vero. |
| [getIncludeOleData()](#getIncludeOleData--) | Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Costruttore predefinito.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifică se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifică se il documento generato deve includere diapositive nascoste o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Specifică il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. Lettura/Scrittura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Il valore predefinito è [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Restituisce:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Specifică il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. Lettura/Scrittura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Il valore predefinito è [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante.

--------------------

La selezione del miglior rapporto di compressione delle immagini è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è false per impostazione predefinita.

--------------------

Il valore predefinito è false.

**Restituisce:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione più piccola del documento PDF risultante.

--------------------

La selezione del miglior rapporto di compressione delle immagini è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è false per impostazione predefinita.

--------------------

Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Determina se Aspose.Slides incorporerà i font comuni per il testo ASCII (intervallo di codici 33..127). I font per codici carattere superiori a 127 sono sempre incorporati. L'elenco dei font comuni include i 14 font di base PDF e i font aggiuntivi specificati dall'utente. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**.

**Restituisce:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Determina se Aspose.Slides incorporerà i font comuni per il testo ASCII (intervallo di codici 33..127). I font per codici carattere superiori a 127 sono sempre incorporati. L'elenco dei font comuni include i 14 font di base PDF e i font aggiuntivi specificati dall'utente. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides dovrebbe considerare comuni. Lettura/Scrittura String[].

**Restituisce:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides dovrebbe considerare comuni. Lettura/Scrittura String[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Determina se tutti i caratteri del font devono essere incorporati o solo il sottoinsieme utilizzato. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini in un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100 dove 0 indica la qualità più bassa ma la massima compressione e 100 indica la migliore qualità ma la compressione minima.

Il valore predefinito è **100**.

**Restituisce:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini in un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100 dove 0 indica la qualità più bassa ma la massima compressione e 100 indica la migliore qualità ma la compressione minima.

Il valore predefinito è **100**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Livello di conformità desiderato per il documento PDF generato. Lettura/Scrittura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Il valore predefinito è [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Restituisce:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Livello di conformità desiderato per il documento PDF generato. Lettura/Scrittura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Il valore predefinito è [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Impostazione della password utente per proteggere il documento PDF. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Impostazione della password utente per proteggere il documento PDF. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. Vedi [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Restituisce:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

Contiene un insieme di flag che specificano quali permessi di accesso devono essere concessi quando il documento è aperto con accesso utente. Vedi [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Vero per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**. Un documento PDF può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita in formato PNG e salvata nel PDF come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito in grafica vettoriale PDF. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile è convertito in PNG, è possibile una perdita di qualità durante la scalatura del documento risultante. Se il Metafile è convertito in grafica vettoriale PDF, possono verificarsi problemi di prestazioni negli strumenti di visualizzazione PDF.

**Restituisce:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Vero per convertire tutti i metafili utilizzati in una presentazione in immagini PNG. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**. Un documento PDF può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita in formato PNG e salvata nel PDF come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito in grafica vettoriale PDF. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile è convertito in PNG, è possibile una perdita di qualità durante la scalatura del documento risultante. Se il Metafile è convertito in grafica vettoriale PDF, possono verificarsi problemi di prestazioni negli strumenti di visualizzazione PDF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. Lettura/Scrittura float.

Valore: L'effetto di questo parametro dipende da diversi fattori. L'algoritmo cerca di ottenere la dimensione ottimale dell'immagine in output in base al valore della proprietà, alla dimensione dell'immagine di origine e alla dimensione del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si raccomanda di usare passi di 16 o 32 per ottenere un effetto visibile.

--------------------

La proprietà influisce su dimensione del file, tempo di esportazione e qualità dell'immagine.

Il valore predefinito è **96**.

**Restituisce:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. Lettura/Scrittura float.

Valore: L'effetto di questo parametro dipende da diversi fattori. L'algoritmo cerca di ottenere la dimensione ottimale dell'immagine in output in base al valore della proprietà, alla dimensione dell'immagine di origine e alla dimensione del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si raccomanda di usare passi di 16 o 32 per ottenere un effetto visibile.

--------------------

La proprietà influisce su dimensione del file, tempo di esportazione e qualità dell'immagine.

Il valore predefinito è **96**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Vero per disegnare una cornice nera attorno a ogni diapositiva. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Vero per disegnare una cornice nera attorno a ogni diapositiva. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Ottiene o imposta il colore trasparente dell'immagine.

Valore: Il colore trasparente dell'immagine.

**Restituisce:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Ottiene o imposta il colore trasparente dell'immagine.

Valore: Il colore trasparente dell'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Applica il colore trasparente specificato a un'immagine se vero.

**Restituisce:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Applica il colore trasparente specificato a un'immagine se vero.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura/Scrittura boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Vero per convertire tutti i dati OLE dalla presentazione in file incorporati nel PDF risultante. Lettura/Scrittura boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |