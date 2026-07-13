---
title: Picture
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een afbeelding in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/picture/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Stelt een afbeelding in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Retourneert of stelt de ingesloten afbeelding in. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Retourneert of stelt de ingesloten afbeelding in. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert of stelt de URL van de gekoppelde afbeelding in. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retourneert of stelt de URL van de gekoppelde afbeelding in. |
| [getImageTransform()](#getImageTransform--) | Retourneert de verzameling van afbeeldingstransformeffecten. |
| [getPresentation()](#getPresentation--) | Retourneert de presentatie. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vergelijkt met opgegeven object. |
| [hashCode()](#hashCode--) | Retourneert hash. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een afbeelding. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versie. Alleen-lezen long.

**Retourneert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Retourneert bovenliggend IPresentationComponent. Alleen-lezen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retourneert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


Retourneert of stelt de ingesloten afbeelding in. Lezen/Schrijven [IPPImage](../../com.aspose.slides/ippimage).

**Retourneert:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


Retourneert of stelt de ingesloten afbeelding in. Lezen/Schrijven [IPPImage](../../com.aspose.slides/ippimage).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Retourneert of stelt de URL van de gekoppelde afbeelding in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Retourneert of stelt de URL van de gekoppelde afbeelding in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


Retourneert de verzameling van afbeeldingstransformeffecten. Alleen-lezen [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Retourneert:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert de presentatie. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vergelijkt met opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Object om te vergelijken. |

**Retourneert:**
boolean - true als objecten gelijk zijn, anders false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert hash.

**Retourneert:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retourneert de bovenliggende dia van een afbeelding. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)