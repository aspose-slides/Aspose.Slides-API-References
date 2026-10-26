---
title: ISlidesPicture
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje obraz w prezentacji.
type: docs
url: /pl/com.aspose.slides/islidespicture/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Reprezentuje obraz w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getImage()](#getImage--) | Zwraca lub ustawia osadzony obraz. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Zwraca lub ustawia osadzony obraz. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia URL połączonego obrazu. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia URL połączonego obrazu. |
| [getImageTransform()](#getImageTransform--) | Zwraca kolekcję efektów transformacji obrazu. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Zwraca lub ustawia osadzony obraz. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Zwraca lub ustawia osadzony obraz. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Zwraca lub ustawia URL połączonego obrazu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Zwraca lub ustawia URL połączonego obrazu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Zwraca kolekcję efektów transformacji obrazu. Tylko do odczytu [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Zwraca:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)