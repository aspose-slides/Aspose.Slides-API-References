---
title: IPptxOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft opties weer voor het opslaan van OpenXml-presentaties PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /nl/com.aspose.slides/ipptxoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Geeft opties weer voor het opslaan van OpenXml-presentaties (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConformance()](#getConformance--) | Specificeert de conformiteitsklasse waaraan het Presentation-document voldoet. |
| [setConformance(int value)](#setConformance-int-) | Specificeert de conformiteitsklasse waaraan het Presentation-document voldoet. |
| [getZip64Mode()](#getZip64Mode--) | Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation-document. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation-document. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specificeert of de miniatuur van de presentatie wordt ververst. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specificeert of de miniatuur van de presentatie wordt ververst. |
| [getCompressionLevel()](#getCompressionLevel--) | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentation-document. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentation-document. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Specificeert de conformiteitsklasse waaraan het Presentation-document voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Retourwaarde:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Specificeert de conformiteitsklasse waaraan het Presentation-document voldoet. Standaardwaarde is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation-document. De standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

Specificeert of het ZIP64-formaat wordt gebruikt voor het Presentation-document. De standaardwaarde is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```

Specificeert of de miniatuur van de presentatie wordt ververst. Lezen/Schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optie waarde **true** is, wordt de nieuwe miniatuur gegenereerd.

Wanneer de optie waarde **false** is, wordt de huidige miniatuur ongewijzigd opgeslagen.

**Retourwaarde:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Specificeert of de miniatuur van de presentatie wordt ververst. Lezen/Schrijven boolean. Standaardwaarde is **true**.

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

Wanneer de optie waarde **true** is, wordt de nieuwe miniatuur gegenereerd.

Wanneer de optie waarde **false** is, wordt de huidige miniatuur ongewijzigd opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentation-document. De standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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
public abstract void setCompressionLevel(int value)
```

Specificeert het compressieniveau dat wordt gebruikt bij het opslaan van het presentation-document. De standaardwaarde is [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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