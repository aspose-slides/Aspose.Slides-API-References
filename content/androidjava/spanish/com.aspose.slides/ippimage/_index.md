---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /es/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Representa una imagen en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Devuelve una copia de los datos de una imagen. |
| [getImage()](#getImage--) | Devuelve una copia de una imagen. |
| [getSvgImage()](#getSvgImage--) | Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Reemplaza los datos de la imagen. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Reemplaza la imagen. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Reemplaza la imagen. |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de una imagen, codificado en \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Devuelve el ancho de una imagen. |
| [getHeight()](#getHeight--) | Devuelve la altura de una imagen. |
| [getX()](#getX--) | Devuelve el desplazamiento X de una imagen. |
| [getY()](#getY--) | Devuelve el desplazamiento Y de una imagen. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Devuelve una copia de los datos de una imagen. Read-only byte[].

**Devuelve:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Devuelve una copia de una imagen. Read-only \#getImage.getImage.

**Devuelve:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagen ha sido creada a partir de SVG.

**Devuelve:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagen ha sido creada a partir de SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Reemplaza los datos de la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImageData | byte[] | Los datos de la nueva imagen. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Reemplaza la imagen. Atención: cuando la Imagen es metafile, se rasterizará. Use replaceImage(byte[]) en su lugar

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nueva imagen. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Reemplaza la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | El nuevo IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Devuelve un tipo MIME de una imagen, codificado en \#getBinaryData.getBinaryData. Read-only String.

**Devuelve:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Devuelve el ancho de una imagen. Read-only int.

**Devuelve:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Devuelve la altura de una imagen. Read-only int.

**Devuelve:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Devuelve el desplazamiento X de una imagen. Read-only int.

**Devuelve:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Devuelve el desplazamiento Y de una imagen. Read-only int.

**Devuelve:**
int