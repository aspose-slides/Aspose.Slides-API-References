---
title: IImageCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av PPImage.
type: docs
url: /sv/com.aspose.slides/iimagecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Representerar en samling av PPImage.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar bilden enligt dess index. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Lägg till en bild i en presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Lägg till en bild i en presentation från en ström. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Skapar och lägger till en bild i en presentation från en ström. |
| [addImage(byte[] buffer)](#addImage-byte---) | Lägger till en bild i en presentation från en specificerad buffer. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Lägger till en kopia av en bild från en annan presentation. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Lägg till en bild i en presentation från ett SVG-objekt. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Returnerar bilden enligt dess index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Bild.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Lägg till en bild i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Bild att lägga till.

--------------------

Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild innan de infogas i en presentation. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd bild.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Lägg till en bild i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till bilden från.

--------------------

Denna metod kan lägga till WMF/EMF-metafiler i en presentation utan att konvertera dem till raster-PNG-bild. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd bild.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Skapar och lägger till en bild i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till bildfilen från. |
| loadingStreamBehavior | int | Det beteende som kommer att tillämpas på strömmen. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Lägger till en bild i en presentation från en specificerad buffer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd bild.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Lägger till en kopia av en bild från en annan presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Källbild. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd bild.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Lägg till en bild i en presentation från ett SVG-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-bildobjekt [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Tillagd bild.