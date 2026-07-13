---
title: PptxOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le opzioni per il salvataggio di presentazioni OpenXml PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /it/com.aspose.slides/pptxoptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Rappresenta le opzioni per il salvataggio di presentazioni OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Crea una nuova istanza di PptxOptions |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConformance()](#getConformance--) | Specifica la classe di conformità a cui il documento Presentation aderisce. |
| [setConformance(int value)](#setConformance-int-) | Specifica la classe di conformità a cui il documento Presentation aderisce. |
| [getZip64Mode()](#getZip64Mode--) | Specifica se il formato ZIP64 è utilizzato per il documento Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifica se il formato ZIP64 è utilizzato per il documento Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specifica se la miniatura della presentazione verrà aggiornata. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specifica se la miniatura della presentazione verrà aggiornata. |
| [getCompressionLevel()](#getCompressionLevel--) | Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Crea una nuova istanza di PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Specifica la classe di conformità a cui il documento Presentation aderisce. Il valore predefinito è [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Restituisce:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Specifica la classe di conformità a cui il documento Presentation aderisce. Il valore predefinito è [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
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
public final void setZip64Mode(int value)
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
public final boolean getRefreshThumbnail()
```

Specifica se la miniatura della presentazione verrà aggiornata. Booleano leggibile/scrivibile. Il valore predefinito è **true**.

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

Quando il valore dell'opzione è **true**, la nuova miniatura verrà generata.

Quando il valore dell'opzione è **false**, la miniatura corrente verrà salvata così com'è.

**Restituisce:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Specifica se la miniatura della presentazione verrà aggiornata. Booleano leggibile/scrivibile. Il valore predefinito è **true**.

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

Quando il valore dell'opzione è **true**, la nuova miniatura verrà generata.

Quando il valore dell'opzione è **false**, la miniatura corrente verrà salvata così com'è.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. Il valore predefinito è [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
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

Livelli di compressione più alti producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione.

**Restituisce:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Specifica il livello di compressione utilizzato durante il salvataggio del documento della presentazione. Il valore predefinito è [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
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

Livelli di compressione più alti producono file più piccoli ma richiedono più tempo di elaborazione. Il rapporto di compressione effettivo dipende dal contenuto della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |