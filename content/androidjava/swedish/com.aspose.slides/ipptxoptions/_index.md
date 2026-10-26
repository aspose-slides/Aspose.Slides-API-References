---
title: IPptxOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar alternativ för att spara OpenXml-presentationer PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /sv/com.aspose.slides/ipptxoptions/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Representerar alternativ för att spara OpenXml-presentationer (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Metoder

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Anger konformitetsklassen som presentationsdokumentet följer. |
| [setConformance(int value)](#setConformance-int-) | Anger konformitetsklassen som presentationsdokumentet följer. |
| [getZip64Mode()](#getZip64Mode--) | Anger om ZIP64-formatet används för presentationsdokumentet. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Anger om ZIP64-formatet används för presentationsdokumentet. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Anger om presentationsminiatyren ska uppdateras. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Anger om presentationsminiatyren ska uppdateras. |
| [getCompressionLevel()](#getCompressionLevel--) | Anger komprimeringsnivån som används när presentationsdokumentet sparas. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Anger komprimeringsnivån som används när presentationsdokumentet sparas. |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Anger konformitetsklassen som presentationsdokumentet följer. Standardvärdet är [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Returnerar:**
int

### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Anger konformitetsklassen som presentationsdokumentet följer. Standardvärdet är [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Anger om ZIP64-formatet används för presentationsdokumentet. Standardvärdet är [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Returnerar:**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```

Anger om ZIP64-formatet används för presentationsdokumentet. Standardvärdet är [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

Anger om presentationsminiatyren ska uppdateras. Läs/skriv boolean. Standardvärdet är **true**.

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

När alternativvärdet är **true** genereras den nya miniatyren.

När alternativvärdet är **false** sparas den aktuella miniatyren som den är.

**Returnerar:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Anger om presentationsminiatyren ska uppdateras. Läs/skriv boolean. Standardvärdet är **true**.

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

När alternativvärdet är **true** genereras den nya miniatyren.

När alternativvärdet är **false** sparas den aktuella miniatyren som den är.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Högre komprimeringsnivåer ger mindre filer men kräver mer beräkningstid. Den faktiska komprimeringsgraden beror på innehållet i presentationen.

**Returnerar:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Anger komprimeringsnivån som används när presentationsdokumentet sparas. Standardvärdet är [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Högre komprimeringsnivåer ger mindre filer men kräver mer beräkningstid. Den faktiska komprimeringsgraden beror på innehållet i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |