---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje obrázek v prezentaci.
type: docs
url: /cs/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Představuje obrázek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat obrázku. |
| [getImage()](#getImage--) | Vrací kopii obrázku. |
| [getSvgImage()](#getSvgImage--) | Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Nahrazuje data obrázku. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Nahrazuje obrázek. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Nahrazuje obrázek. |
| [getContentType()](#getContentType--) | Vrací MIME typ obrázku, zakódovaný v \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Vrací šířku obrázku. |
| [getHeight()](#getHeight--) | Vrací výšku obrázku. |
| [getX()](#getX--) | Vrací X-odchylku obrázku. |
| [getY()](#getY--) | Vrací Y-odchylku obrázku. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Vrací kopii dat obrázku. Jen pro čtení byte[].

**Vrací:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Vrací kopii obrázku. Jen pro čtení \#getImage.getImage.

**Vrací:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Tato hodnota naznačuje, že tento obrázek byl vytvořen ze SVG.

**Vrací:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Tato hodnota naznačuje, že tento obrázek byl vytvořen ze SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Nahrazuje data obrázku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImageData | byte[] | Data nového obrázku. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Nahrazuje obrázek. Pozor: když je Image metafile - bude rasterizován. Použijte místo toho replaceImage(byte[]).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Nový obrázek. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Nahrazuje obrázek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Nový IPPImage. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Vrací MIME typ obrázku, zakódovaný v \#getBinaryData.getBinaryData. Jen pro čtení String.

**Vrací:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Vrací šířku obrázku. Jen pro čtení int.

**Vrací:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Vrací výšku obrázku. Jen pro čtení int.

**Vrací:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Vrací X-odchylku obrázku. Jen pro čtení int.

**Vrací:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Vrací Y-odchylku obrázku. Jen pro čtení int.

**Vrací:**
int