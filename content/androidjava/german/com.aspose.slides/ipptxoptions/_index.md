---
title: IPptxOptions
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Optionen zum Speichern von OpenXml-Präsentationen PPTX PPSX POTX PPTM PPSM POTM dar.
type: docs
url: /de/com.aspose.slides/ipptxoptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Stellt Optionen zum Speichern von OpenXml-Präsentationen (PPTX, PPSX, POTX, PPTM, PPSM, POTM) dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConformance()](#getConformance--) | Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. |
| [setConformance(int value)](#setConformance-int-) | Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. |
| [getZip64Mode()](#getZip64Mode--) | Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. |
| [getCompressionLevel()](#getCompressionLevel--) | Gibt die beim Speichern des Präsentationsdokuments verwendete Komprimierungsstufe an. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Gibt die beim Speichern des Präsentationsdokuments verwendete Komprimierungsstufe an. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. Der Standardwert ist [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Rückgabewert:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Gibt die Konformitätsklasse an, der das Präsentationsdokument entspricht. Der Standardwert ist [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Beispiel:
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
public abstract void setZip64Mode(int value)
```

Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Beispiel:
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
public abstract boolean getRefreshThumbnail()
```

Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Lese-/Schreib-Boolean. Standardwert ist **true**.

--------------------

> ```
> Beispiel:
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

Wenn der Optionswert **true** ist, wird das neue Vorschaubild erstellt.

Wenn der Optionswert **false** ist, wird das aktuelle Vorschaubild unverändert gespeichert.

**Rückgabewert:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Gibt an, ob das Vorschaubild der Präsentation aktualisiert wird. Lese-/Schreib-Boolean. Standardwert ist **true**.

--------------------

> ```
> Beispiel:
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

Wenn der Optionswert **true** ist, wird das neue Vorschaubild erstellt.

Wenn der Optionswert **false** ist, wird das aktuelle Vorschaubild unverändert gespeichert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Gibt die beim Speichern des Präsentationsdokuments verwendete Komprimierungsstufe an. Der Standardwert ist [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Beispiel:
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

Höhere Komprimierungsstufen erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Komprimierungsverhältnis hängt vom Inhalt der Präsentation ab.

**Rückgabewert:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Gibt die beim Speichern des Präsentationsdokuments verwendete Komprimierungsstufe an. Der Standardwert ist [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Beispiel:
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

Höhere Komprimierungsstufen erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Komprimierungsverhältnis hängt vom Inhalt der Präsentation ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |