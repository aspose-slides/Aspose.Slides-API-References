---
title: SwfOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce opzioni che controllano come una presentazione viene salvata in formato Swf.
type: docs
url: /it/com.aspose.slides/swfoptions/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Fornisce opzioni che controllano come una presentazione viene salvata in formato Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Salvataggio della presentazione e delle pagine delle note
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Costruttore predefinito. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato dovrebbe includere o meno diapositive nascoste. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato dovrebbe includere o meno diapositive nascoste. |
| [getCompressed()](#getCompressed--) | Specifica se il documento SWF generato dovrebbe essere compresso o meno. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specifica se il documento SWF generato dovrebbe essere compresso o meno. |
| [getViewerIncluded()](#getViewerIncluded--) | Specifica se il documento SWF generato dovrebbe includere il visualizzatore di documenti integrato o meno. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specifica se il documento SWF generato dovrebbe includere il visualizzatore di documenti integrato o meno. |
| [getShowPageBorder()](#getShowPageBorder--) | Specifica se il bordo intorno alle pagine dovrebbe essere mostrato. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specifica se il bordo intorno alle pagine dovrebbe essere mostrato. |
| [getShowFullScreen()](#getShowFullScreen--) | Mostra/nascondi pulsante a schermo intero. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Mostra/nascondi pulsante a schermo intero. |
| [getShowPageStepper()](#getShowPageStepper--) | Mostra/nascondi selettore di pagina. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Mostra/nascondi selettore di pagina. |
| [getShowSearch()](#getShowSearch--) | Mostra/nascondi sezione di ricerca. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Mostra/nascondi sezione di ricerca. |
| [getShowTopPane()](#getShowTopPane--) | Mostra/nascondi l'intero pannello superiore. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Mostra/nascondi l'intero pannello superiore. |
| [getShowBottomPane()](#getShowBottomPane--) | Mostra/nascondi pannello inferiore. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Mostra/nascondi pannello inferiore. |
| [getShowLeftPane()](#getShowLeftPane--) | Mostra/nascondi pannello sinistro. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Mostra/nascondi pannello sinistro. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Inizia con il pannello sinistro aperto. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Inizia con il pannello sinistro aperto. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Abilita/disabilita menu contestuale. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Abilita/disabilita menu contestuale. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. |
| [getLogoLink()](#getLogoLink--) | Ottiene o imposta l'indirizzo ipertestuale completo per un logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Ottiene o imposta l'indirizzo ipertestuale completo per un logo. |
| [getJpegQuality()](#getJpegQuality--) | Specifica la qualità delle immagini JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Specifica la qualità delle immagini JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Costruttore predefinito.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifica se il documento generato dovrebbe includere o meno diapositive nascoste. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifica se il documento generato dovrebbe includere o meno diapositive nascoste. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Specifica se il documento SWF generato dovrebbe essere compresso o meno. Il valore predefinito è true.

**Restituisce:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Specifica se il documento SWF generato dovrebbe essere compresso o meno. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Specifica se il documento SWF generato dovrebbe includere il visualizzatore di documenti integrato o meno. Il valore predefinito è true.

**Restituisce:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Specifica se il documento SWF generato dovrebbe includere il visualizzatore di documenti integrato o meno. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Specifica se il bordo intorno alle pagine dovrebbe essere mostrato. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Specifica se il bordo intorno alle pagine dovrebbe essere mostrato. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Mostra/nascondi pulsante a schermo intero. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Mostra/nascondi pulsante a schermo intero. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Mostra/nascondi selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Mostra/nascondi selettore di pagina. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Mostra/nascondi sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Mostra/nascondi sezione di ricerca. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Mostra/nascondi l'intero pannello superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Mostra/nascondi l'intero pannello superiore. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Mostra/nascondi pannello inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Mostra/nascondi pannello inferiore. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Mostra/nascondi pannello sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Restituisce:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Mostra/nascondi pannello sinistro. Può essere sovrascritto in flashvars. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Inizia con il pannello sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false.

**Restituisce:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Inizia con il pannello sinistro aperto. Può essere sovrascritto in flashvars. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Abilita/disabilita menu contestuale. Il valore predefinito è true.

**Restituisce:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Abilita/disabilita menu contestuale. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. L'immagine dovrebbe essere PNG 32x64 pixel, altrimenti il logo potrebbe non essere visualizzato correttamente.

**Restituisce:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Immagine che verrà visualizzata come logo nell'angolo in alto a destra del visualizzatore. L'immagine dovrebbe essere PNG 32x64 pixel, altrimenti il logo potrebbe non essere visualizzato correttamente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Ottiene o imposta l'indirizzo ipertestuale completo per un logo. Ha effetto solo se è specificato un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Restituisce:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Ottiene o imposta l'indirizzo ipertestuale completo per un logo. Ha effetto solo se è specificato un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Specifica la qualità delle immagini JPEG. Il valore predefinito è 95.

**Restituisce:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Specifica la qualità delle immagini JPEG. Il valore predefinito è 95.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Questa proprietà non supporta l'assegnazione di oggetti di tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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

Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Questa proprietà non supporta l'assegnazione di oggetti di tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Esempio:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |