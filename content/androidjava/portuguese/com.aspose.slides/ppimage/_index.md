---
title: PPImage
second_title: Referência da API Java para Aspose.Slides no Android
description: Representa uma imagem em uma apresentação.
type: docs
url: /pt/com.aspose.slides/ppimage/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Representa uma imagem em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Retorna uma cópia dos dados da imagem. |
| [getImage()](#getImage--) | Retorna uma cópia da imagem. |
| [getSvgImage()](#getSvgImage--) | Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Substitui os dados da imagem. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Substitui os dados da imagem. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Substitui os dados da imagem. |
| [getContentType()](#getContentType--) | Retorna o tipo MIME de uma imagem, codificado em BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Retorna a largura de uma imagem. |
| [getHeight()](#getHeight--) | Retorna a altura de uma imagem. |
| [getX()](#getX--) | Retorna o deslocamento X de uma imagem. |
| [getY()](#getY--) | Retorna o deslocamento Y de uma imagem. |
| [hashCode()](#hashCode--) | Retorna o código hash de uma imagem. |
| [dispose()](#dispose--) | Descarta o objeto. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Retorna uma cópia dos dados da imagem. Somente leitura  byte[] .

**Retorna:**
byte[] - Array of bytes
### getImage() {#getImage--}
```
public final IImage getImage()
```


Retorna uma cópia da imagem. Somente leitura [IImage](../../com.aspose.slides/iimage).

**Retorna:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagem foi criada a partir de SVG.

**Retorna:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagem foi criada a partir de SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Substitui os dados da imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImageData | byte[] | Os dados da nova imagem. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Substitui os dados da imagem. Atenção: quando Image é metafile - será rasterizada. Use ReplaceImage(byte[]) instead

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | A nova imagem. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Substitui os dados da imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | O novo IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Retorna o tipo MIME de uma imagem, codificado em BinaryData (\#getBinaryData.getBinaryData). Somente leitura String.

**Retorna:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Retorna a largura de uma imagem. Somente leitura  int .

**Retorna:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Retorna a altura de uma imagem. Somente leitura  int .

**Retorna:**
int
### getX() {#getX--}
```
public final int getX()
```


Retorna o deslocamento X de uma imagem. Somente leitura  int .

**Retorna:**
int
### getY() {#getY--}
```
public final int getY()
```


Retorna o deslocamento Y de uma imagem. Somente leitura  int .

**Retorna:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retorna o código hash de uma imagem.

**Retorna:**
int - Código hash.
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta o objeto.