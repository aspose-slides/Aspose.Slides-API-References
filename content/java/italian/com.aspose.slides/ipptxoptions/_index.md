---
title: IPptxOptions
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le opzioni per salvare presentazioni OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /it/com.aspose.slides/ipptxoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Rappresenta le opzioni per salvare presentazioni OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConformance()](#getConformance--) | Specifica la classe di conformità a cui il documento Presentation è conforme. |
| [setConformance(int value)](#setConformance-int-) | Specifica la classe di conformità a cui il documento Presentation è conforme. |
| [getZip64Mode()](#getZip64Mode--) | Specifica se il formato ZIP64 è utilizzato per il documento Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifica se il formato ZIP64 è utilizzato per il documento Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specifica se la miniatura della presentazione sarà aggiornata. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specifica se la miniatura della presentazione sarà aggiornata. |
| [getCompressionLevel()](#getCompressionLevel--) | Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Specifica la classe di conformità a cui il documento Presentation è conforme. Il valore predefinito è [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Restituisce:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Specifica la classe di conformità a cui il documento Presentation è conforme. Il valore predefinito è [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Specifica se il formato ZIP64 è utilizzato per il documento Presentation. Il valore predefinito è [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

Specifica se il formato ZIP64 è utilizzato per il documento Presentation. Il valore predefinito è [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

Specifica se la miniatura della presentazione sarà aggiornata. Booleano lettura/scrittura. Il valore predefinito è **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Quando il valore dell'opzione è **true**, verrà generata una nuova miniatura.

Quando il valore dell'opzione è **false**, la miniatura corrente verrà salvata così com'è.

**Restituisce:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Specifica se la miniatura della presentazione sarà aggiornata. Booleano lettura/scrittura. Il valore predefinito è **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Quando il valore dell'opzione è **true**, verrà generata una nuova miniatura.

Quando il valore dell'opzione è **false**, la miniatura corrente verrà salvata così com'è.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. Il valore predefinito è [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Esempio:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Livelli di compressione più elevati producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione.

**Restituisce:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Specifica il livello di compressione utilizzato durante il salvataggio del documento di presentazione. Il valore predefinito è [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Esempio:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Livelli di compressione più elevati producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |