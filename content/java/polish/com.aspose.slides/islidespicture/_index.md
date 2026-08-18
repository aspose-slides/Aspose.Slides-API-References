---
title: ISlidesPicture
second_title: Aspose.Slides dla Java – referencja API
description: Reprezentuje obraz w prezentacji.
type: docs
url: /pl/com.aspose.slides/islidespicture/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Represents a picture in a presentation.
## Metody

| Metoda | Opis |
| --- | --- |
| [getImage()](#getImage--) | Returns or sets the embedded image. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Returns or sets the embedded image. |
| [getLinkPathLong()](#getLinkPathLong--) | Returns of sets linked image's URL. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Returns of sets linked image's URL. |
| [getImageTransform()](#getImageTransform--) | Returns the collection of image transform effects. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


Returns or sets the embedded image. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


Returns or sets the embedded image. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Returns of sets linked image's URL. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Returns of sets linked image's URL. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


Returns the collection of image transform effects. Tylko do odczytu [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Zwraca:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)