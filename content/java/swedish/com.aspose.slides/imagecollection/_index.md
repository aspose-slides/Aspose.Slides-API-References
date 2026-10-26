---
title: ImageCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av PPImage.
type: docs
url: /sv/com.aspose.slides/imagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Representerar samling av PPImage.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet bilder i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Lägger till en kopia av en bild från en annan presentation. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Lägger till en bild i en presentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Lägger till en bild i en presentation från en ström. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Skapar och lägger till en bild i en presentation från en ström. |
| [addImage(byte[] buffer)](#addImage-byte---) | Lägger till en bild i en presentation från en specificerad buffert. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Lägger till en bild i en presentation från ett Svg-objekt. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```


Returnerar antalet bilder i samlingen. Skrivskyddad int .

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [IPPImage](../../com.aspose.slides/ippimage).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Lägger till en kopia av en bild från en annan presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Källbild. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Lägg till en bild i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Bild att lägga till.

--------------------

Denna metod konverterar WMF/EMF-metafiler till raster-PNG-bild innan den infogas i en presentation. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Lägg till en bild i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till bild från.

--------------------

Denna metod kan lägga till WMF/EMF-metafiler i en presentation utan att konvertera dem till raster-PNG-bild. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Skapar och lägger till en bild i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till bildfil från. |
| loadingStreamBehavior | int | Beteendet som ska tillämpas på strömmen. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Lägger till en bild i en presentation från en specificerad buffert.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | byte[] | Buffert. |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Lägg till en bild i en presentation från Svg-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg-bildobjekt [ISvgImage](../../com.aspose.slides/isvgimage) |

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage) - Added image.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarry. |
| index | int | Startindex i målarrayen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean .

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar en synkroniseringsrot. Skrivskyddad Object .

**Returnerar:**
java.lang.Object