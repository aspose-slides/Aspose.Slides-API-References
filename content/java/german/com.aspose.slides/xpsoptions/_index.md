---
title: XpsOptions
second_title: Aspose.Slides für Java API Referenz
description: Stellt Optionen bereit, die bestimmen, wie eine Präsentation im XPS-Format gespeichert wird.
type: docs
url: /de/com.aspose.slides/xpsoptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Stellt Optionen bereit, die steuern, wie eine Präsentation im XPS-Format gespeichert wird.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Speichert die Präsentation als XPS-Dokument
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instanziiert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instanziiert die TiffOptions-Klasse
>      XpsOptions options = new XpsOptions();
>      // Speichert MetaFiles als PNG
>      options.setSaveMetafilesAsPng(true);
>      // Speichert die Präsentation als XPS-Dokument
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True, um um jeden Folie einen schwarzen Rahmen zu zeichnen. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True, um um jeden Folie einen schwarzen Rahmen zu zeichnen. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Standardkonstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist **false**.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreib-Boolean.

--------------------

Standardwert ist **true**.

**Rückgabewert:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lese-/Schreib-Boolean.

--------------------

Standardwert ist **true**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True, um um jeden Folie einen schwarzen Rahmen zu zeichnen. Lese-/Schreib-Boolean.

--------------------

Standardwert ist **false**.

**Rückgabewert:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True, um um jeden Folie einen schwarzen Rahmen zu zeichnen. Lese-/Schreib-Boolean.

--------------------

Standardwert ist **false**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |