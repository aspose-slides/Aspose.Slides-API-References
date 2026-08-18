---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /hu/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Egy képet képvisel egy prezentációban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Visszaadja a kép adatainak egy másolatát. |
| [getImage()](#getImage--) | Visszaadja a kép egy másolatát. |
| [getSvgImage()](#getSvgImage--) | Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Lecseréli a kép adatait. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Lecseréli a képet. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Lecseréli a képet. |
| [getContentType()](#getContentType--) | Visszaad egy MIME típust a képről, amely a \#getBinaryData.getBinaryData-ban kódolt. |
| [getWidth()](#getWidth--) | Visszaadja a kép szélességét. |
| [getHeight()](#getHeight--) | Visszaadja a kép magasságát. |
| [getX()](#getX--) | Visszaadja a kép X-eltolását. |
| [getY()](#getY--) | Visszaadja a kép Y-eltolását. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Visszaadja a kép adatainak egy másolatát. Csak olvasható byte[].

**Visszatér:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Visszaadja a kép egy másolatát. Csak olvasható \#getImage.getImage.

**Visszatér:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték azt jelzi, hogy ez a kép SVG-ből készült.

**Visszatér:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Visszaad vagy beállít ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték azt jelzi, hogy ez a kép SVG-ből készült.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Lecseréli a kép adatait.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImageData | byte[] | Az új kép adatai. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Lecseréli a képet. Figyelem: ha a kép metafájl, akkor rasterizálva lesz. Használja a replaceImage(byte[]) metódust helyette

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Az új kép. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Lecseréli a képet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Az új IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Visszaad egy MIME típust a képről, amely a \#getBinaryData.getBinaryData-ban kódolt. Csak olvasható String.

**Visszatér:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Visszaadja a kép szélességét. Csak olvasható int.

**Visszatér:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Visszaadja a kép magasságát. Csak olvasható int.

**Visszatér:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Visszaadja a kép X-eltolását. Csak olvasható int.

**Visszatér:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Visszaadja a kép Y-eltolását. Csak olvasható int.

**Visszatér:**
int