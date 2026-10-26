---
title: IPptxOptions
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Az OpenXml prezentációk (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentésének beállításait képviseli.
type: docs
url: /hu/com.aspose.slides/ipptxoptions/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Az OpenXml prezentációk (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentésének beállításait képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getConformance()](#getConformance--) | Megadja a Presentation dokumentum által betartott megfelelőségi osztályt. |
| [setConformance(int value)](#setConformance-int-) | Megadja a Presentation dokumentum által betartott megfelelőségi osztályt. |
| [getZip64Mode()](#getZip64Mode--) | Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Megadja, hogy a prezentáció miniatűrje frissüljön-e. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Megadja, hogy a prezentáció miniatűrje frissüljön-e. |
| [getCompressionLevel()](#getCompressionLevel--) | Megadja a prezentáció dokumentum mentésekor használt tömörítési szintet. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Megadja a prezentáció dokumentum mentésekor használt tömörítési szintet. |

### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Megadja a Presentation dokumentum által betartott megfelelőségi osztályt. Az alapértelmezett érték [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Visszatér:**  
int

### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Megadja a Presentation dokumentum által betartott megfelelőségi osztályt. Az alapértelmezett érték [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. Az alapértelmezett érték [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

Megadja, hogy a Presentation dokumentum ZIP64 formátumot használ-e. Az alapértelmezett érték [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

Megadja, hogy a prezentáció miniatűrje frissüljön-e. Olvasás/írás boolean. Alapértelmezett érték **true**.

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

Ha a beállítás értéke **true**, az új miniatűr létrejön.

Ha a beállítás értéke **false**, a jelenlegi miniatűr változatlanul marad.

**Visszatér:**  
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Megadja, hogy a prezentáció miniatűrje frissüljön-e. Olvasás/írás boolean. Alapértelmezett érték **true**.

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

Ha a beállítás értéke **true**, az új miniatűr létrejön.

Ha a beállítás értéke **false**, a jelenlegi miniatűr változatlanul marad.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Megadja a prezentáció dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Magasabb tömörítési szintek kisebb fájlokat eredményeznek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Visszatér:**  
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Megadja a prezentáció dokumentum mentésekor használt tömörítési szintet. Az alapértelmezett érték [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

Magasabb tömörítési szintek kisebb fájlokat eredményeznek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |