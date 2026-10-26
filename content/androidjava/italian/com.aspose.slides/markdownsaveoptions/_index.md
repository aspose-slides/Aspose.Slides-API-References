---
title: MarkdownSaveOptions
second_title: Riferimento API Java per Aspose.Slides su Android
description: Rappresenta le opzioni che controllano come la presentazione deve essere salvata in markdown.
type: docs
url: /it/com.aspose.slides/markdownsaveoptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Rappresenta le opzioni che controllano come la presentazione deve essere salvata in markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExportType()](#getExportType--) | Specifica la specifica markdown per convertire la presentazione. |
| [setExportType(int value)](#setExportType-int-) | Specifica la specifica markdown per convertire la presentazione. |
| [getBasePath()](#getBasePath--) | Specifica il percorso di base dove il documento con le risorse verrà salvato. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specifica il percorso di base dove il documento con le risorse verrà salvato. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specifica il nome della cartella in cui salvare le immagini. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specifica il nome della cartella in cui salvare le immagini. |
| [getNewLineType()](#getNewLineType--) | Specifica se il documento generato deve avere nuove righe \\\\r(Macintosh), \\\\n(Unix) o \\\\r\\\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Specifica se il documento generato deve avere nuove righe \\\\r(Macintosh), \\\\n(Unix) o \\\\r\\\\n(Windows). |
| [getShowComments()](#getShowComments--) | Specifica se il documento generato deve mostrare i commenti o meno. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Specifica se il documento generato deve mostrare i commenti o meno. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Specifica se il documento generato deve mostrare il numero di ciascuna diapositiva o meno. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Specifica se il documento generato deve mostrare il numero di ciascuna diapositiva o meno. |
| [getFlavor()](#getFlavor--) | Specifica la specifica markdown per convertire la presentazione. |
| [setFlavor(int value)](#setFlavor-int-) | Specifica la specifica markdown per convertire la presentazione. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Ottiene o imposta la stringa di formato usata per le intestazioni del numero di diapositiva nell'output Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Ottiene o imposta la stringa di formato usata per le intestazioni del numero di diapositiva nell'output Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Specifica come gestire i caratteri di spazio regolari ripetuti durante l'esportazione Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Specifica come gestire i caratteri di spazio regolari ripetuti durante l'esportazione Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Se impostato su true, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Se impostato su true, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Si verifica per ogni immagine non SVG (bitmap o metafile) durante l'esportazione Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Si verifica per ogni immagine SVG durante l'esportazione Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Costruttore.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Specifica la specifica markdown per convertire la presentazione. Il valore predefinito è  TextOnly .

**Restituisce:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Specifică la specifica markdown per convertire la presentazione. Il valore predefinito è  TextOnly .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Specifică il percorso di base dove il documento con le risorse verrà salvato. Il valore predefinito è la directory corrente dell'applicazione.

**Restituisce:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Specifică il percorso di base dove il documento con le risorse verrà salvato. Il valore predefinito è la directory corrente dell'applicazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Specifică il nome della cartella in cui salvare le immagini. Il valore predefinito è  Images .

**Restituisce:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Specifică il nome della cartella in cui salvare le immagini. Il valore predefinito è  Images .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Specifică se il documento generato deve avere nuove righe \\\\r(Macintosh), \\\\n(Unix) o \\\\r\\\\n(Windows). Il valore predefinito è  Unix .

**Restituisce:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Specifică se il documento generato deve avere nuove righe \\\\r(Macintosh), \\\\n(Unix) o \\\\r\\\\n(Windows). Il valore predefinito è  Unix .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Specifică se il documento generato deve mostrare i commenti o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Specifică se il documento generato deve mostrare i commenti o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Specifică se il documento generato deve mostrare il numero di ciascuna diapositiva o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Specifică se il documento generato deve mostrare il numero di ciascuna diapositiva o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Specifică la specifica markdown per convertire la presentazione. Il valore predefinito è  Multi-markdown .

**Restituisce:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Specifică la specifica markdown per convertire la presentazione. Il valore predefinito è  Multi-markdown .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Ottiene o imposta la stringa di formato usata per le intestazioni del numero di diapositiva nell'output Markdown. Il formato deve includere il segnaposto "\{0\}", che verrà sostituito con l'indice della diapositiva durante l'esportazione. Esempio: "\# Slide \{0\}" produrrà "\# Slide 1", "\# Slide 2", ecc.

**Restituisce:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Ottiene o imposta la stringa di formato usata per le intestazioni del numero di diapositiva nell'output Markdown. Il formato deve includere il segnaposto "\{0\}", che verrà sostituito con l'indice della diapositiva durante l'esportazione. Esempio: "\# Slide \{0\}" produrrà "\# Slide 1", "\# Slide 2", ecc.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Specifică come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione Markdown. Questa proprietà definisce se gli spazi consecutivi sono: - preservati come caratteri di spazio regolari, - alternati tra spazi regolari e entità di spazio non interrotto (�), - o completamente sostituiti (dopo il primo) con uno spazio non interrotto per preservare l'allineamento visivo nell'output Markdown. Il valore predefinito è [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Restituisce:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Specifică come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione Markdown. Questa proprietà definisce se gli spazi consecutivi sono: - preservati come caratteri di spazio regolari, - alternati tra spazi regolari e entità di spazio non interrotto (�), - o completamente sostituiti (dopo il primo) con uno spazio non interrotto per preservare l'allineamento visivo nell'output Markdown. Il valore predefinito è [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Se impostato su true, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale. Il valore predefinito è false.

**Restituisce:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Se impostato su true, rimuove le righe vuote o composte solo da spazi bianchi dall'output Markdown finale. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Si verifica per ogni immagine non SVG (bitmap o metafile) durante l'esportazione Markdown. Consente di personalizzare come l'immagine viene salvata e referenziata. Se non gestito, l'immagine viene salvata localmente con un link relativo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Evento di salvataggio immagine Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Si verifica per ogni immagine SVG durante l'esportazione Markdown. Consente di sovrascrivere il salvataggio predefinito e la generazione del link. Se non gestito, l'SVG viene salvato localmente con un link relativo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Evento di salvataggio SVG Markdown. |