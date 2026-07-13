---
title: Picture
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/picture/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Representerar en bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Returnerar eller anger den inbäddade bilden. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returnerar eller anger den inbäddade bilden. |
| [getLinkPathLong()](#getLinkPathLong--) | Returnerar eller sätter den länkade bildens URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returnerar eller sätter den länkade bildens URL. |
| [getImageTransform()](#getImageTransform--) | Returnerar samlingen av bildtransformeringseffekter. |
| [getPresentation()](#getPresentation--) | Returnerar presentationen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Jämför med angivet objekt. |
| [hashCode()](#hashCode--) | Returnerar hash. |
| [getSlide()](#getSlide--) | Returnerar föräldrasliden för en bild. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returnerar förälder IPresentationComponent. Skrivskyddad [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


Returnerar eller anger den inbäddade bilden. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

**Returnerar:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


Returnerar eller anger den inbäddade bilden. Läs/skriv [IPPImage](../../com.aspose.slides/ippimage).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Returnerar eller sätter den länkade bildens URL. Läs/skriv String.

**Returnerar:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Returnerar eller sätter den länkade bildens URL. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


Returnerar samlingen av bildtransformeringseffekter. Skrivskyddad [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Returnerar:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returnerar presentationen. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Jämför med angivet objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objekt att jämföra. |

**Returnerar:**
boolean - Sant om objekten är lika, annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash.

**Returnerar:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Returnerar föräldrasliden för en bild. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)