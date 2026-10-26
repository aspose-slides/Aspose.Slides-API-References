---
title: ISlidesPicture
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/islidespicture/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Representerar en bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getImage()](#getImage--) | Returnerar eller anger den inbäddade bilden. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returnerar eller anger den inbäddade bilden. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller anger den länkade bildens URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller anger den länkade bildens URL. |
| [getImageTransform()](#getImageTransform--) | Returnerar samlingen av bildtransformeringseffekter. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Returnerar eller anger den inbäddade bilden. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Returnerar eller anger den inbäddade bilden. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returnerar eller anger den länkade bildens URL. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returnerar eller anger den länkade bildens URL. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Returnerar samlingen av bildtransformeringseffekter. Skrivskyddad [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Returnerar:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)