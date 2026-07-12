---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Representa uma imagem em uma apresentação.
type: docs
url: /pt/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Representa uma imagem em uma apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Retorna a cópia dos dados de uma imagem. |
| [getImage()](#getImage--) | Retorna a cópia de uma imagem. |
| [getSvgImage()](#getSvgImage--) | Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Substitui os dados da imagem. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Substitui a imagem. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Substitui a imagem. |
| [getContentType()](#getContentType--) | Retorna um tipo MIME de uma imagem, codificado em \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Retorna a largura de uma imagem. |
| [getHeight()](#getHeight--) | Retorna a altura de uma imagem. |
| [getX()](#getX--) | Retorna o deslocamento X de uma imagem. |
| [getY()](#getY--) | Retorna o deslocamento Y de uma imagem. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retorna a cópia dos dados de uma imagem. Somente leitura byte[].

**Retorna:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Retorna a cópia de uma imagem. Somente leitura \#getImage.getImage.

**Retorna:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Retorna ou define o objeto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Este valor indica que esta imagem foi criada a partir de SVG.

**Retorna:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
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
public abstract void replaceImage(byte[] newImageData)
```


Substitui os dados da imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImageData | byte[] | Os dados da nova imagem. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Substitui a imagem. Atenção: quando a Image é metafile, ela será rasterizada. Use replaceImage(byte[]) em vez disso

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | A nova imagem. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Substitui a imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | O novo IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Retorna um tipo MIME de uma imagem, codificado em \#getBinaryData.getBinaryData. Somente leitura String.

**Retorna:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Retorna a largura de uma imagem. Somente leitura int.

**Retorna:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Retorna a altura de uma imagem. Somente leitura int.

**Retorna:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Retorna o deslocamento X de uma imagem. Somente leitura int.

**Retorna:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Retorna o deslocamento Y de uma imagem. Somente leitura int.

**Retorna:**
int