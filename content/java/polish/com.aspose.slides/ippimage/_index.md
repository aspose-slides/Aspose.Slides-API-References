---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /pl/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Reprezentuje obraz w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returns the copy of an image's data. |
| [getImage()](#getImage--) | Returns the copy of an image. |
| [getSvgImage()](#getSvgImage--) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returns or sets ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Replaces image data. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Replaces image. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Replaces image. |
| [getContentType()](#getContentType--) | Returns a MIME type of an image, encoded in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Returns a width of an image. |
| [getHeight()](#getHeight--) | Returns a height of an image. |
| [getX()](#getX--) | Returns a X-offset of an image. |
| [getY()](#getY--) | Returns a Y-offset of an image. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Zwraca kopię danych obrazu. Tylko do odczytu byte[].

**Zwraca:**  
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Zwraca kopię obrazu. Tylko do odczytu \#getImage.getImage.

**Zwraca:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ta wartość wskazuje, że ten obraz został utworzony z SVG.

**Zwraca:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ta wartość wskazuje, że ten obraz został utworzony z SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Zastępuje dane obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImageData | byte[] | Nowe dane obrazu. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Zastępuje obraz. Uwaga: gdy Image jest metafilem – zostanie zrastrowany. Użyj replaceImage(byte[]) zamiast

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Nowy obraz. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Zastępuje obraz.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Nowy IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Zwraca typ MIME obrazu, zakodowany w \#getBinaryData.getBinaryData. Tylko do odczytu String.

**Zwraca:**  
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Zwraca szerokość obrazu. Tylko do odczytu int.

**Zwraca:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Zwraca wysokość obrazu. Tylko do odczytu int.

**Zwraca:**  
int
### getX() {#getX--}
```
public abstract int getX()
```


Zwraca przesunięcie w osi X obrazu. Tylko do odczytu int.

**Zwraca:**  
int
### getY() {#getY--}
```
public abstract int getY()
```


Zwraca przesunięcie w osi Y obrazu. Tylko do odczytu int.

**Zwraca:**  
int