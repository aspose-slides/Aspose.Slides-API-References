---
title: IPdfOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Pdf.
type: docs
url: /it/com.aspose.slides/ipdfoptions/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato PDF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Specifica il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Specifica il tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | True per incorporare i font TrueType per i caratteri ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | True per incorporare i font TrueType per i caratteri ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere diapositivi nascosti o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere diapositivi nascosti o no. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides deve considerare comuni. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides deve considerare comuni. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. |
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True per convertire tutti i metafili usati in una presentazione in immagini PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True per convertire tutti i metafili usati in una presentazione in immagini PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True per disegnare una cornice nera attorno a ogni diapositiva. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True per disegnare una cornice nera attorno a ogni diapositiva. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Ottiene o imposta il colore trasparente dell'immagine. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Ottiene o imposta il colore trasparente dell'immagine. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Applica il colore trasparente specificato a un'immagine se true. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Applica il colore trasparente specificato a un'immagine se true. |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getIncludeOleData()](#getIncludeOleData--) | True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Specifică tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. Lettura/Scrittura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Il valore predefinito è [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Restituisce:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Specifică tipo di compressione da utilizzare per tutti i contenuti testuali nel documento. Lettura/Scrittura [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

Il valore predefinito è [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione minore del documento PDF risultante.

--------------------

La selezione del miglior rapporto di compressione delle immagini è computazionalmente costosa e richiede una quantità aggiuntiva di RAM, e questa opzione è false per impostazione predefinita.

--------------------

Il valore predefinito è false.

**Restituisce:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indica se la compressione più efficace (invece di quella predefinita) per ogni immagine deve essere selezionata automaticamente. Se impostato su true, per ogni immagine nella presentazione verrà scelto l'algoritmo di compressione più appropriato, il che porterà a una dimensione minore del documento PDF risultante.

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
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

True per incorporare i font TrueType per i caratteri ASCII 32-127. I font per codici di carattere superiori a 127 sono sempre incorporati. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**.

**Restituisce:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

True per incorporare i font TrueType per i caratteri ASCII 32-127. I font per codici di carattere superiori a 127 sono sempre incorporati. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Specifică se il documento generato deve includere diapositivi nascosti o no. Il valore predefinito è false.

**Restituisce:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Specifică se il documento generato deve includere diapositivi nascosti o no. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides deve considerare comuni. Lettura/Scrittura String[].

**Restituisce:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Restituisce o imposta un array di nomi di famiglie di font definiti dall'utente che Aspose.Slides deve considerare comuni. Lettura/Scrittura String[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Determina se tutti i caratteri del font devono essere incorporati o solo un sottoinsieme utilizzato. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Indica se il testo deve essere rasterizzato come bitmap e salvato in PDF quando il font non supporta lo stile grassetto. Questo approccio può migliorare la qualità del testo nel PDF risultante per alcuni font. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
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
public abstract byte getJpegQuality()
```

Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100 dove 0 significa qualità minima ma massima compressione e 100 significa qualità massima ma compressione minima.

Il valore predefinito è **100**.

**Restituisce:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100 dove 0 significa qualità minima ma massima compressione e 100 significa qualità massima ma compressione minima.

Il valore predefinito è **100**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Livello di conformità desiderato per il documento PDF generato. Lettura/Scrittura [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

Il valore predefinito è [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Restituisce:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
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
public abstract String getPassword()
```

Impostazione della password utente per proteggere il documento PDF. Lettura/Scrittura String.

**Restituisce:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Impostazione della password utente per proteggere il documento PDF. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
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
public abstract void setAccessPermissions(int value)
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
public abstract boolean getSaveMetafilesAsPng()
```

True per convertire tutti i metafili usati in una presentazione in immagini PNG. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**. Il documento PDF può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita in formato PNG e salvata nel PDF come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito in grafica vettoriale PDF. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile è convertito in PNG, è possibile una perdita di qualità durante lo scaling del documento risultante. Se il Metafile è convertito in grafica vettoriale PDF, potrebbero verificarsi problemi di prestazioni nello strumento di visualizzazione PDF.

**Restituisce:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True per convertire tutti i metafili usati in una presentazione in immagini PNG. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **true**. Il documento PDF può contenere grafica vettoriale e immagini raster. Se SaveMetafilesAsPng è impostato su true, l'immagine Metafile di origine viene convertita in formato PNG e salvata nel PDF come immagine raster. Se SaveMetafilesAsPng è impostato su false, il Metafile di origine viene convertito in grafica vettoriale PDF. Ogni approccio ha vantaggi e svantaggi. Per esempio, se il Metafile è convertito in PNG, è possibile una perdita di qualità durante lo scaling del documento risultante. Se il Metafile è convertito in grafica vettoriale PDF, potrebbero verificarsi problemi di prestazioni nello strumento di visualizzazione PDF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. Lettura/Scrittura float.

Valore: L'effetto di questo parametro dipende da diversi fattori. L'algoritmo tenta di ottenere la migliore dimensione dell'immagine in output in base al valore della proprietà, alle dimensioni dell'immagine di origine e alle dimensioni del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si consiglia di usare passi di 16 o 32 per ottenere un effetto visibile.

--------------------

La proprietà influisce su dimensione del file, tempo di esportazione e qualità dell'immagine.

Il valore predefinito è **96**.

**Restituisce:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Restituisce o imposta un valore che determina la risoluzione delle immagini all'interno del documento PDF. Lettura/Scrittura float.

Valore: L'effetto di questo parametro dipende da diversi fattori. L'algoritmo tenta di ottenere la migliore dimensione dell'immagine in output in base al valore della proprietà, alle dimensioni dell'immagine di origine e alle dimensioni del frame dell'immagine. L'uso di valori di proprietà simili può dare lo stesso risultato. Si consiglia di usare passi di 16 o 32 per ottenere un effetto visibile.

--------------------

La proprietà influisce su dimensione del file, tempo di esportazione e qualità dell'immagine.

Il valore predefinito è **96**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True per disegnare una cornice nera attorno a ogni diapositiva. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Restituisce:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True per disegnare una cornice nera attorno a ogni diapositiva. Lettura/Scrittura boolean.

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Ottiene o imposta il colore trasparente dell'immagine.

Valore: Il colore trasparente dell'immagine.

**Restituisce:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Ottiene o imposta il colore trasparente dell'immagine.

Valore: Il colore trasparente dell'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Applica il colore trasparente specificato a un'immagine se true.

**Restituisce:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Applica il colore trasparente specificato a un'immagine se true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. Lettura/Scrittura boolean.

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
public abstract void setIncludeOleData(boolean value)
```

True per convertire tutti i dati OLE della presentazione in file incorporati nel PDF risultante. Lettura/Scrittura boolean.

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
>      if (pres != null) presentation.dispose();
>  }
> ```

--------------------

Il valore predefinito è **false**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |