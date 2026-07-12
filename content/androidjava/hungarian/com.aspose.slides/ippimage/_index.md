---
title: IPPImage
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy képet képvisel egy prezentációban.
type: docs
url: /hu/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Egy képet képvisel egy prezentációban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Visszaadja a kép adatainak másolatát. |
| [getImage()](#getImage--) | Visszaadja a kép másolatát. |
| [getSvgImage()](#getSvgImage--) | Visszaadja vagy beállítja az ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Visszaadja vagy beállítja az ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Lecseréli a kép adatait. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Lecseréli a képet. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Lecseréli a képet. |
| [getContentType()](#getContentType--) | Visszaadja egy kép MIME típusát, amely a \#getBinaryData.getBinaryData-ban van kódolva. |
| [getWidth()](#getWidth--) | Visszaadja egy kép szélességét. |
| [getHeight()](#getHeight--) | Visszaadja egy kép magasságát. |
| [getX()](#getX--) | Visszaadja egy kép X-eltolását. |
| [getY()](#getY--) | Visszaadja egy kép Y-eltolását. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Visszaadja egy kép adatainak másolatát. Csak olvasható byte[].

**Visszatér:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Visszaadja egy kép másolatát. Csak olvasható \#getImage.getImage.

**Visszatér:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Visszaadja vagy beállítja az ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték jelzi, hogy a kép SVG-ből készült.

**Visszatér:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Visszaadja vagy beállítja az ISvgImage objektumot [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ez az érték jelzi, hogy a kép SVG-ből készült.

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


Lecseréli a képet. Figyelem: amikor a Image metafájl, akkor raszterizálva lesz. Használja a replaceImage(byte[]) metódust helyette.

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


Visszaad egy kép MIME típusát, amely a \#getBinaryData.getBinaryData-ban van kódolva. Csak olvasható String.

**Visszatér:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Visszaadja egy kép szélességét. Csak olvasható int.

**Visszatér:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Visszaadja egy kép magasságát. Csak olvasható int.

**Visszatér:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Visszaadja egy kép X-eltolását. Csak olvasható int.

**Visszatér:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Visszaadja egy kép Y-eltolását. Csak olvasható int.

**Visszatér:**
int