---
title: PPImage
second_title: Aspose.Slides for Java API referencia
description: Kép egy prezentációban.
type: docs
url: /hu/com.aspose.slides/ppimage/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Kép egy prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Visszaadja a kép adatainak másolatát. |
| [getImage()](#getImage--) | Visszaadja a kép másolatát. |
| [getSvgImage()](#getSvgImage--) | Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Lecseréli a kép adatát. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Lecseréli a kép adatát. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Lecseréli a kép adatát. |
| [getContentType()](#getContentType--) | Visszaad egy kép MIME típusát, amely a BinaryData (\#getBinaryData.getBinaryData) kódolásával van eltárolva. |
| [getWidth()](#getWidth--) | Visszaadja a kép szélességét. |
| [getHeight()](#getHeight--) | Visszaadja a kép magasságát. |
| [getX()](#getX--) | Visszaadja a kép X-eltolását. |
| [getY()](#getY--) | Visszaadja a kép Y-eltolását. |
| [hashCode()](#hashCode--) | Visszaadja a kép hash kódját. |
| [dispose()](#dispose--) | Felszabadítja az objektumot. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Visszaadja egy kép adatainak másolatát. Csak-olvasású byte[] .

**Visszatér:**
byte[] - Bájttömb
### getImage() {#getImage--}
```
public final IImage getImage()
```

Visszaadja egy kép másolatát. Csak-olvasású [IImage](../../com.aspose.slides/iimage).

**Visszatér:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték azt jelzi, hogy ez a kép SVG-ből lett létrehozva.

**Visszatér:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték azt jelzi, hogy ez a kép SVG-ből lett létrehozva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

Lecseréli a kép adatát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImageData | byte[] | Az új kép adatai. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Lecseréli a kép adatát. Figyelem: ha a kép metafájl, akkor rasterizálva lesz. Használja a ReplaceImage(byte[]) metódust helyette.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Az új kép. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Lecseréli a kép adatát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Az új IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Visszaadja egy kép MIME típusát, amely a BinaryData (\#getBinaryData.getBinaryData) kódolásában tárolódik. Csak-olvasású String.

**Visszatér:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

Visszaadja a kép szélességét. Csak-olvasású int.

**Visszatér:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

Visszaadja a kép magasságát. Csak-olvasású int.

**Visszatér:**
int
### getX() {#getX--}
```
public final int getX()
```

Visszaadja a kép X-eltolását. Csak-olvasású int.

**Visszatér:**
int
### getY() {#getY--}
```
public final int getY()
```

Visszaadja a kép Y-eltolását. Csak-olvasású int.

**Visszatér:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

Visszaadja a kép hash kódját.

**Visszatér:**
int - Hash kód.
### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja az objektumot.