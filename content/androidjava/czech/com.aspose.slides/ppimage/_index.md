---
title: PPImage
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje obrázek v prezentaci.
type: docs
url: /cs/com.aspose.slides/ppimage/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Reprezentuje obrázek v prezentaci.
## Metody

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Vrací kopii dat obrázku. |
| [getImage()](#getImage--) | Vrací kopii obrázku. |
| [getSvgImage()](#getSvgImage--) | Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Nahrazuje data obrázku. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Nahrazuje data obrázku. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Nahrazuje data obrázku. |
| [getContentType()](#getContentType--) | Vrací MIME typ obrázku, zakódovaný v  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Vrací šířku obrázku. |
| [getHeight()](#getHeight--) | Vrací výšku obrázku. |
| [getX()](#getX--) | Vrací X-odchylku obrázku. |
| [getY()](#getY--) | Vrací Y-odchylku obrázku. |
| [hashCode()](#hashCode--) | Vrací hash kód obrázku. |
| [dispose()](#dispose--) | Uvolňuje objekt. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Vrací kopii dat obrázku. **Pouze pro čtení** byte[] .

**Vrací:**
byte[] - Pole bajtů
### getImage() {#getImage--}
```
public final IImage getImage()
```

Vrací kopii obrázku. **Pouze pro čtení** [IImage](../../com.aspose.slides/iimage).

**Vrací:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Vrací nebo nastavuje objekt ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Tato hodnota naznačuje, že tento obrázek byl vytvořen ze SVG.

**Vrací:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
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
public final void replaceImage(byte[] newImageData)
```

Nahrazuje data obrázku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImageData | byte[] | Data nového obrázku. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Nahrazuje data obrázku. Pozor: když je Image metafile - bude rasterizován. Použijte ReplaceImage(byte[]) místo toho

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Nový obrázek. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Nahrazuje data obrázku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Nový IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Vrací MIME typ obrázku, zakódovaný v  BinaryData (\#getBinaryData.getBinaryData). **Pouze pro čtení** String.

**Vrací:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

Vrací šířku obrázku. **Pouze pro čtení** int .

**Vrací:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

Vrací výšku obrázku. **Pouze pro čtení** int .

**Vrací:**
int
### getX() {#getX--}
```
public final int getX()
```

Vrací X-odchylku obrázku. **Pouze pro čtení** int .

**Vrací:**
int
### getY() {#getY--}
```
public final int getY()
```

Vrací Y-odchylku obrázku. **Pouze pro čtení** int .

**Vrací:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

Vrací hash kód obrázku.

**Vrací:**
int - Hash kód.
### dispose() {#dispose--}
```
public final void dispose()
```

Uvolňuje objekt.