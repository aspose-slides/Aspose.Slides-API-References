---
title: PptxOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt opties voor het opslaan van OpenXml-presentaties PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /nl/com.aspose.slides/pptxoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Stelt opties voor het opslaan van OpenXml-presentaties (PPTX, PPSX, POTX, PPTM, PPSM, POTM) voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Maakt een nieuwe instantie van PptxOptions |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConformance()](#getConformance--) | Specificeert de conformiteitsklasse waaraan het Presentatiedocument voldoet. |
| [setConformance(int value)](#setConformance-int-) | Specificeert de conformiteitsklasse waaraan het Presentatiedocument voldoet. |
| [getZip64Mode()](#getZip64Mode--) | Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specificeert of de presentatiethumbnail wordt vernieuwd. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specificeert of de presentatiethumbnail wordt vernieuwd. |
| [getCompressionLevel()](#getCompressionLevel--) | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Maakt een nieuwe instantie van PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Specificeert de conformiteitsklasse waaraan het Presentatiedocument voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retourwaarde:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Specificeert de conformiteitsklasse waaraan het Presentatiedocument voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. De standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


**Retourwaarde:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```


Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. De standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```


Specificeert of de presentatiethumbnail wordt vernieuwd. Lezen/schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optiewaarde **true** is, wordt de nieuwe thumbnail gegenereerd.

Wanneer de optiewaarde **false** is, wordt de huidige thumbnail opgeslagen zoals hij is.

**Retourwaarde:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Specificeert of de presentatiethumbnail wordt vernieuwd. Lezen/schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optiewaarde **true** is, wordt de nieuwe thumbnail gegenereerd.

Wanneer de optiewaarde **false** is, wordt de huidige thumbnail opgeslagen zoals hij is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Hogere compressieniveaus produceren kleinere bestanden, maar vereisen meer verwerkingstijd. De feitelijke compressieverhouding hangt af van de inhoud van de presentatie.

**Retourwaarde:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. De standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Hogere compressieniveaus produceren kleinere bestanden, maar vereisen meer verwerkingstijd. De feitelijke compressieverhouding hangt af van de inhoud van de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |