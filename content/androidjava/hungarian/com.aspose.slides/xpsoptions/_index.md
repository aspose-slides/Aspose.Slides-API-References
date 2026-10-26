---
title: XpsOptions
second_title: Aspose.Slides Androidhoz a Java API hivatkozásával
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató XPS formátumban.
type: docs
url: /hu/com.aspose.slides/xpsoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató XPS formátumban.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // A prezentáció mentése XPS dokumentumba
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Példányosítja a TiffOptions osztályt
>      XpsOptions options = new XpsOptions();
>      // A MetaFiles mentése PNG formátumban
>      options.setSaveMetafilesAsPng(true);
>      // A prezentáció mentése XPS dokumentumba
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Igaz, ha a bemutatóban használt összes metafájlt PNG képekké kell konvertálni. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Igaz, ha a bemutatóban használt összes metafájlt PNG képekké kell konvertálni. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Igaz, ha minden diára fekete keretet kell rajzolni. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Igaz, ha minden diára fekete keretet kell rajzolni. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Alapértelmezett konstruktor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték **false**.

**Visszatérési érték:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Igaz, ha a bemutatóban használt összes metafájlt PNG képekké kell konvertálni. Olvasási/írási boolean.

--------------------

Alapértelmezett érték **true**.

**Visszatérési érték:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Igaz, ha a bemutatóban használt összes metafájlt PNG képekké kell konvertálni. Olvasási/írási boolean.

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

Igaz, ha minden diára fekete keretet kell rajzolni. Olvasási/írási boolean.

--------------------

Alapértelmezett érték **false**.

**Visszatérési érték:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Igaz, ha minden diára fekete keretet kell rajzolni. Olvasási/írási boolean.

--------------------

Alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |