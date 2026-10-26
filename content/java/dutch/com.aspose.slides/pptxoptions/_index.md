---
title: PptxOptions
second_title: Aspose.Slides voor Java API-referentie
description: Stelt opties voor het opslaan van OpenXml-presentaties PPTX PPSX POTX PPTM PPSM POTM voor.
type: docs
url: /nl/com.aspose.slides/pptxoptions/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Stelt opties voor het opslaan van OpenXml-presentaties (PPTX, PPSX, POTX, PPTM, PPSM, POTM) voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Maakt een nieuw exemplaar van PptxOptions |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getConformance()](#getConformance--) | Geeft de conformiteitsklasse op waaraan het Presentatiedocument voldoet. |
| [setConformance(int value)](#setConformance-int-) | Geeft de conformiteitsklasse op waaraan het Presentatiedocument voldoet. |
| [getZip64Mode()](#getZip64Mode--) | Bepaalt of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Bepaalt of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Bepaalt of de miniatuur van de presentatie wordt ververst. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Bepaalt of de miniatuur van de presentatie wordt ververst. |
| [getCompressionLevel()](#getCompressionLevel--) | Bepaalt het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Bepaalt het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Maakt een nieuw exemplaar van PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Geeft de conformiteitsklasse op waaraan het Presentatiedocument voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retourwaarde:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Geeft de conformiteitsklasse op waaraan het Presentatiedocument voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Bepaalt of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. Standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


Bepaalt of het ZIP64-formaat wordt gebruikt voor het Presentatiedocument. Standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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


Bepaalt of de miniatuur van de presentatie wordt ververst. Lezen/Schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optiewaarde **true** is, wordt de nieuwe miniatuur gegenereerd.

Wanneer de optiewaarde **false** is, wordt de huidige miniatuur ongewijzigd opgeslagen.

**Retourwaarde:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


Bepaalt of de miniatuur van de presentatie wordt ververst. Lezen/Schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optiewaarde **true** is, wordt de nieuwe miniatuur gegenereerd.

Wanneer de optiewaarde **false** is, wordt de huidige miniatuur ongewijzigd opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


Bepaalt het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. Standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Hogere compressieniveaus leveren kleinere bestanden op, maar vergen meer verwerkingstijd. De feitelijke compressieverhouding hangt af van de inhoud van de presentatie.

**Retourwaarde:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


Bepaalt het compressieniveau dat wordt gebruikt bij het opslaan van het presentatiedocument. Standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Hogere compressieniveaus leveren kleinere bestanden op, maar vergen meer verwerkingstijd. De feitelijke compressieverhouding hangt af van de inhoud van de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |