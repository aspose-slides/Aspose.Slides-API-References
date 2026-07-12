---
title: PptxOptions
second_title: Aspose.Slides für Android über Java API Reference
description: Stellt Optionen zum Speichern von OpenXml-Präsentationen PPTX, PPSX, POTX, PPTM, PPSM, POTM bereit.
type: docs
url: /de/com.aspose.slides/pptxoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Stellt Optionen zum Speichern von OpenXml-Präsentationen (PPTX, PPSX, POTX, PPTM, PPSM, POTM) bereit.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Erstellt eine neue Instanz von PptxOptions |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConformance()](#getConformance--) | Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. |
| [setConformance(int value)](#setConformance-int-) | Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. |
| [getZip64Mode()](#getZip64Mode--) | Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Gibt an, ob das Miniaturbild der Präsentation aktualisiert wird. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Gibt an, ob das Miniaturbild der Präsentation aktualisiert wird. |
| [getCompressionLevel()](#getCompressionLevel--) | Gibt das Komprimierungsniveau an, das beim Speichern des Präsentationsdokuments verwendet wird. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Gibt das Komprimierungsniveau an, das beim Speichern des Präsentationsdokuments verwendet wird. |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Erstellt eine neue Instanz von PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. Standardwert ist [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Rückgabewert:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. Standardwert ist [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Rückgabewert:**
int

### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Gibt an, ob das Miniaturbild der Präsentation aktualisiert wird. Lese-/Schreib-Boolean. Standardwert ist **true**.

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

Wenn der Optionswert **true** ist, wird das neue Miniaturbild erzeugt.

Wenn der Optionswert **false** ist, wird das aktuelle Miniaturbild unverändert gespeichert.

**Rückgabewert:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Gibt an, ob das Miniaturbild der Präsentation aktualisiert wird. Lese-/Schreib-Boolean. Standardwert ist **true**.

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

Wenn der Optionswert **true** ist, wird das neue Miniaturbild erzeugt.

Wenn der Optionswert **false** ist, wird das aktuelle Miniaturbild unverändert gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Gibt das Komprimierungsniveau an, das beim Speichern des Präsentationsdokuments verwendet wird. Der Standardwert ist [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Höhere Komprimierungsstufen erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab.

**Rückgabewert:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Gibt das Komprimierungsniveau an, das beim Speichern des Präsentationsdokuments verwendet wird. Der Standardwert ist [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Höhere Komprimierungsstufen erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |