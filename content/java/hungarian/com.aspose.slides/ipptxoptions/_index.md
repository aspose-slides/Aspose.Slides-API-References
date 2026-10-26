---
title: IPptxOptions
second_title: Aspose.Slides Java API referencia
description: Az OpenXml prezentációk (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentésének beállításait reprezentálja.
type: docs
url: /hu/com.aspose.slides/ipptxoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

A OpenXml prezentációk (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentésének beállításait reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getConformance()](#getConformance--) | Megadja, hogy a Presentation dokumentum melyik megfelelőségi osztályba tartozik. |
| [setConformance(int value)](#setConformance-int-) | Megadja, hogy a Presentation dokumentum melyik megfelelőségi osztályba tartozik. |
| [getZip64Mode()](#getZip64Mode--) | Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Megadja, hogy a prezentáció előnézeti képe frissítésre kerüljön-e. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Megadja, hogy a prezentáció előnézeti képe frissítésre kerüljön-e. |
| [getCompressionLevel()](#getCompressionLevel--) | Megadja a mentéskor használt tömörítési szintet. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Megadja a mentéskor használt tömörítési szintet. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Megadja, hogy a Presentation dokumentum melyik megfelelőségi osztályba tartozik. Alapértelmezett érték: [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Visszatér:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Megadja, hogy a Presentation dokumentum melyik megfelelőségi osztályba tartozik. Alapértelmezett érték: [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. Alapértelmezett érték: [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Visszatér:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```


Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. Alapértelmezett érték: [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


Megadja, hogy a prezentáció előnézeti képe frissítésre kerüljön-e. Olvasás/írás boolean. Alapértelmezett érték: **true**.

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

Ha a beállítás értéke **true**, az új előnézeti kép generálva lesz.

Ha a beállítás értéke **false**, a jelenlegi előnézeti kép változatlanul marad.

**Visszatér:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


Megadja, hogy a prezentáció előnézeti képe frissítésre kerüljön-e. Olvasás/írás boolean. Alapértelmezett érték: **true**.

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

Ha a beállítás értéke **true**, az új előnézeti kép generálva lesz.

Ha a beállítás értéke **false**, a jelenlegi előnézeti kép változatlanul marad.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


Megadja a mentéskor használt tömörítési szintet. Alapértelmezett érték: [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

A magasabb tömörítési szintek kisebb fájlokhoz vezetnek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Visszatér:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


Megadja a mentéskor használt tömörítési szintet. Alapértelmezett érték: [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

A magasabb tömörítési szintek kisebb fájlokhoz vezetnek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |