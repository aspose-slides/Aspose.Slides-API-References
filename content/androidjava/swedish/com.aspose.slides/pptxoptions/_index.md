---
title: PptxOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar alternativ för att spara OpenXml-presentationer PPTX, PPSX, POTX, PPTM, PPSM och POTM.
type: docs
url: /sv/com.aspose.slides/pptxoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Representerar alternativ för att spara OpenXml-presentationer (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Skapar en ny instans av PptxOptions |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConformance()](#getConformance--) | Anger konformitetsklassen som presentationsdokumentet följer. |
| [setConformance(int value)](#setConformance-int-) | Anger konformitetsklassen som presentationsdokumentet följer. |
| [getZip64Mode()](#getZip64Mode--) | Anger om ZIP64-formatet används för presentationsdokumentet. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Anger om ZIP64-formatet används för presentationsdokumentet. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Anger om presentationsminiatyren ska uppdateras. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Anger om presentationsminiatyren ska uppdateras. |
| [getCompressionLevel()](#getCompressionLevel--) | Anger komprimeringsnivån som används när presentationsdokumentet sparas. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Anger komprimeringsnivån som används när presentationsdokumentet sparas. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Skapar en ny instans av PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Anger konformitetsklassen som presentationsdokumentet följer. Standardvärdet är [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Returnerar:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Anger konformitetsklassen som presentationsdokumentet följer. Standardvärdet är [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
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
public final void setZip64Mode(int value)
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
public final boolean getRefreshThumbnail()
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

När alternativvärdet är **true**, kommer den nya miniatyren att genereras.

När alternativvärdet är **false**, sparas den aktuella miniatyren som den är.

**Returnerar:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
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

När alternativvärdet är **true**, kommer den nya miniatyren att genereras.

När alternativvärdet är **false**, sparas den aktuella miniatyren som den är.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
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

Högre komprimeringsnivåer ger mindre filer men kräver mer bearbetningstid. Den faktiska komprimeringsgraden beror på innehållet i presentationen.

**Returnerar:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
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

Högre komprimeringsnivåer ger mindre filer men kräver mer bearbetningstid. Den faktiska komprimeringsgraden beror på innehållet i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |