---
title: PPImage
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una imagen en una presentación.
type: docs
url: /es/com.aspose.slides/ppimage/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Representa una imagen en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Devuelve la copia de los datos de una imagen. |
| [getImage()](#getImage--) | Devuelve la copia de una imagen. |
| [getSvgImage()](#getSvgImage--) | Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Reemplaza los datos de la imagen. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Reemplaza los datos de la imagen. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Reemplaza los datos de la imagen. |
| [getContentType()](#getContentType--) | Devuelve un tipo MIME de una imagen, codificado en  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Devuelve el ancho de una imagen. |
| [getHeight()](#getHeight--) | Devuelve la altura de una imagen. |
| [getX()](#getX--) | Devuelve el desplazamiento X de una imagen. |
| [getY()](#getY--) | Devuelve el desplazamiento Y de una imagen. |
| [hashCode()](#hashCode--) | Devuelve el código hash de una imagen. |
| [dispose()](#dispose--) | Descarta el objeto. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Devuelve la copia de los datos de una imagen. Sólo lectura  byte[] .

**Devuelve:**
byte[] - Matriz de bytes
### getImage() {#getImage--}
```
public final IImage getImage()
```


Devuelve la copia de una imagen. Sólo lectura [IImage](../../com.aspose.slides/iimage).

**Devuelve:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Devuelve o establece el objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagen ha sido creada a partir de SVG.

**Devuelve:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
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
public final void replaceImage(byte[] newImageData)
```


Reemplaza los datos de la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImageData | byte[] | Los datos de la nueva imagen. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Reemplaza los datos de la imagen. Atención: cuando la Image es metafile, se rasterizará. Use ReplaceImage(byte[]) en su lugar

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nueva imagen. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Reemplaza los datos de la imagen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | El nuevo IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Devuelve un tipo MIME de una imagen, codificado en  BinaryData (\#getBinaryData.getBinaryData). Sólo lectura String.

**Devuelve:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Devuelve el ancho de una imagen. Sólo lectura  int .

**Devuelve:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Devuelve la altura de una imagen. Sólo lectura  int .

**Devuelve:**
int
### getX() {#getX--}
```
public final int getX()
```


Devuelve el desplazamiento X de una imagen. Sólo lectura  int .

**Devuelve:**
int
### getY() {#getY--}
```
public final int getY()
```


Devuelve el desplazamiento Y de una imagen. Sólo lectura  int .

**Devuelve:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash de una imagen.

**Devuelve:**
int - Código hash.
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta el objeto.