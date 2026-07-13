---
title: ISlidesPicture
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een afbeelding in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/islidespicture/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Stelt een afbeelding in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getImage()](#getImage--) | Retourneert of stelt de ingebedde afbeelding in. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Retourneert of stelt de ingebedde afbeelding in. |
| [getLinkPathLong()](#getLinkPathLong--) | Retourneert of stelt de URL van de gekoppelde afbeelding in. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Retourneert of stelt de URL van de gekoppelde afbeelding in. |
| [getImageTransform()](#getImageTransform--) | Retourneert de collectie van afbeeldingstransformatie-effecten. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Retourneert of stelt de ingebedde afbeelding in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

**Retour:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Retourneert of stelt de ingebedde afbeelding in. Lezen/schrijven [IPPImage](../../com.aspose.slides/ippimage).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Retourneert of stelt de URL van de gekoppelde afbeelding in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Retourneert of stelt de URL van de gekoppelde afbeelding in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Retourneert de collectie van afbeeldingstransformatie-effecten. Alleen-lezen [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Retour:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)