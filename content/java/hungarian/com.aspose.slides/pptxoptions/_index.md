---
title: PptxOptions
second_title: Aspose.Slides Java API referenciája
description: OpenXml prezentációk (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentéséhez használt beállításokat képviseli.
type: docs
url: /hu/com.aspose.slides/pptxoptions/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Minden megvalósított interfész:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Az OpenXml bemutatók (PPTX, PPSX, POTX, PPTM, PPSM, POTM) mentéséhez használt beállításokat képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Új PptxOptions példányt hoz létre |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getConformance()](#getConformance--) | Megadja azt a megfelelőségi osztályt, amelynek a Presentation dokumentum megfelel. |
| [setConformance(int value)](#setConformance-int-) | Megadja azt a megfelelőségi osztályt, amelynek a Presentation dokumentum megfelel. |
| [getZip64Mode()](#getZip64Mode--) | Megadja, hogy a ZIP64 formátumot használják-e a Presentation dokumentumhoz. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Megadja, hogy a ZIP64 formátumot használják-e a Presentation dokumentumhoz. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Megadja, hogy a bemutató miniatűrje frissítve lesz-e. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Megadja, hogy a bemutató miniatűrje frissítve lesz-e. |
| [getCompressionLevel()](#getCompressionLevel--) | Megadja a mentéskor használt tömörítési szintet a presentation dokumentumhoz. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Megadja a mentéskor használt tömörítési szintet a presentation dokumentumhoz. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Új PptxOptions példányt hoz létre

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Megadja azt a megfelelőségi osztályt, amelynek a Presentation dokumentum megfelel. Az alapértelmezett érték [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Visszatérési érték:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Megadja azt a megfelelőségi osztályt, amelynek a Presentation dokumentum megfelel. Az alapértelmezett érték [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Megadja, hogy a ZIP64 formátumot használják-e a Presentation dokumentumhoz. Az alapértelmezett érték [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

**Visszatérési érték:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Megadja, hogy a ZIP64 formátumot használják-e a Presentation dokumentumhoz. Az alapértelmezett érték [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public final boolean getRefreshThumbnail()
```

Megadja, hogy a bemutató miniatűrje frissítve lesz-e. Olvasás/írás boolean. Az alapértelmezett érték **true**.

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

Amikor az opció értéke **true**, az új miniatűr generálva lesz.

Amikor az opció értéke **false**, a jelenlegi miniatűr változatlanul mentésre kerül.

**Visszatérési érték:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Megadja, hogy a bemutató miniatűrje frissítve lesz-e. Olvasás/írás boolean. Az alapértelmezett érték **true**.

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

Amikor az opció értéke **true**, az új miniatűr generálva lesz.

Amikor az opció értéke **false**, a jelenlegi miniatűr változatlanul mentésre kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Megadja a mentéskor használt tömörítési szintet a presentation dokumentumhoz. Az alapértelmezett érték [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

A magasabb tömörítési szintek kisebb fájlokat eredményeznek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Visszatérési érték:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Megadja a mentéskor használt tömörítési szintet a presentation dokumentumhoz. Az alapértelmezett érték [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

A magasabb tömörítési szintek kisebb fájlokat eredményeznek, de több feldolgozási időt igényelnek. A tényleges tömörítési arány a prezentáció tartalmától függ.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |