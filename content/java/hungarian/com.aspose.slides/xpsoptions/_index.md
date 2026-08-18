---
title: XpsOptions
second_title: Aspose.Slides Java API hivatkozás
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy bemutató XPS formátumban.
type: docs
url: /hu/com.aspose.slides/xpsoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy bemutató XPS formátumban.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Saving the presentation to XPS document
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instantiate the TiffOptions class
>      XpsOptions options = new XpsOptions();
>      // Save MetaFiles as PNG
>      options.setSaveMetafilesAsPng(true);
>      // Save the presentation to XPS document
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Alapértelmezett konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha a bemutatóban használt összes metafájl PNG képekké konvertálandó. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha a bemutatóban használt összes metafájl PNG képekké konvertálandó. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha fekete keretet kell rajzolni minden diára. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha fekete keretet kell rajzolni minden diára. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Alapértelmezett konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Az alapértelmezett érték **false**.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Az alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


Igaz, ha a bemutatóban használt összes metafájl PNG képekké konvertálandó. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**.

**Visszatérési érték:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


Igaz, ha a bemutatóban használt összes metafájl PNG képekké konvertálandó. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **true**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


Igaz, ha fekete keretet kell rajzolni minden diára. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Visszatérési érték:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


Igaz, ha fekete keretet kell rajzolni minden diára. Olvasás/írás boolean.

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |