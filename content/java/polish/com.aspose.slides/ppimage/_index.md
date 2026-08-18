---
title: PPImage
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje obraz w prezentacji.
type: docs
url: /pl/com.aspose.slides/ppimage/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Reprezentuje obraz w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Zwraca kopię danych obrazu. |
| [getImage()](#getImage--) | Zwraca kopię obrazu. |
| [getSvgImage()](#getSvgImage--) | Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Zastępuje dane obrazu. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Zastępuje dane obrazu. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Zastępuje dane obrazu. |
| [getContentType()](#getContentType--) | Zwraca typ MIME obrazu, zakodowany w  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Zwraca szerokość obrazu. |
| [getHeight()](#getHeight--) | Zwraca wysokość obrazu. |
| [getX()](#getX--) | Zwraca offset X obrazu. |
| [getY()](#getY--) | Zwraca offset Y obrazu. |
| [hashCode()](#hashCode--) | Zwraca kod skrótu obrazu. |
| [dispose()](#dispose--) | Zwalnia obiekt. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Zwraca kopię danych obrazu. tylko do odczytu  byte[] .

**Zwraca:**
byte[] - Tablica bajtów
### getImage() {#getImage--}
```
public final IImage getImage()
```


Zwraca kopię obrazu. tylko do odczytu [IImage](../../com.aspose.slides/iimage).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Ta wartość wskazuje, że ten obraz został utworzony z SVG.

**Zwraca:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
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
public final void replaceImage(byte[] newImageData)
```


Zastępuje dane obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImageData | byte[] | Dane nowego obrazu. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Zastępuje dane obrazu. Uwaga: gdy Image jest metafilem – zostanie rasteryzowany. Użyj ReplaceImage(byte[]) zamiast tego

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Nowy obraz. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Zastępuje dane obrazu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Nowy IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Zwraca typ MIME obrazu, zakodowany w  BinaryData (\#getBinaryData.getBinaryData). tylko do odczytu String.

**Zwraca:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Zwraca szerokość obrazu. tylko do odczytu  int .

**Zwraca:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Zwraca wysokość obrazu. tylko do odczytu  int .

**Zwraca:**
int
### getX() {#getX--}
```
public final int getX()
```


Zwraca offset X obrazu. tylko do odczytu  int .

**Zwraca:**
int
### getY() {#getY--}
```
public final int getY()
```


Zwraca offset Y obrazu. tylko do odczytu  int .

**Zwraca:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Zwraca kod skrótu obrazu.

**Zwraca:**
int - Kod skrótu.
### dispose() {#dispose--}
```
public final void dispose()
```


Zwalnia obiekt.