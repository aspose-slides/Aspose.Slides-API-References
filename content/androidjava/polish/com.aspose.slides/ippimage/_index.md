---
title: IPPImage
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Reprezentuje obraz w prezentacji.
type: docs
url: /pl/com.aspose.slides/ippimage/
---```
public interface IPPImage
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
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Zastępuje obraz. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Zastępuje obraz. |
| [getContentType()](#getContentType--) | Zwraca typ MIME obrazu, zakodowany w \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Zwraca szerokość obrazu. |
| [getHeight()](#getHeight--) | Zwraca wysokość obrazu. |
| [getX()](#getX--) | Zwraca offset X obrazu. |
| [getY()](#getY--) | Zwraca offset Y obrazu. |
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

Wartość ta wskazuje, że ten obraz został utworzony z SVG.

**Zwraca:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Zwraca lub ustawia obiekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Wartość ta wskazuje, że ten obraz został utworzony z SVG.

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

Zastępuje obraz. Uwaga: gdy Image jest metafilem - zostanie zrastryzowany. Zamiast tego użyj replaceImage(byte[]).

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

Zwraca offset X obrazu. Tylko do odczytu int.

**Zwraca:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Zwraca offset Y obrazu. Tylko do odczytu int.

**Zwraca:**
int