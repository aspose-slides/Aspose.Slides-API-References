---
title: Picture
second_title: Aspose.Slides dla Androida poprzez Referencję API Java
description: Reprezentuje obraz w prezentacji.
type: docs
url: /pl/com.aspose.slides/picture/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Reprezentuje obraz w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Zwraca lub ustawia osadzony obraz. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Zwraca lub ustawia osadzony obraz. |
| [getLinkPathLong()](#getLinkPathLong--) | Zwraca lub ustawia adres URL powiązanego obrazu. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Zwraca lub ustawia adres URL powiązanego obrazu. |
| [getImageTransform()](#getImageTransform--) | Zwraca kolekcję efektów transformacji obrazu. |
| [getPresentation()](#getPresentation--) | Zwraca prezentację. |
| [equals(Object obj)](#equals-java.lang.Object-) | Porównuje z określonym obiektem. |
| [hashCode()](#hashCode--) | Zwraca hash. |
| [getSlide()](#getSlide--) | Zwraca slajd-rodzic obrazu. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Zwraca rodzica IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Zwraca lub ustawia osadzony obraz. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Zwraca:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Zwraca lub ustawia osadzony obraz. Odczyt/zapis [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Zwraca lub ustawia adres URL powiązanego obrazu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Zwraca lub ustawia adres URL powiązanego obrazu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Zwraca kolekcję efektów transformacji obrazu. Tylko do odczytu [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Zwraca:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Zwraca prezentację. Tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Porównuje z określonym obiektem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt do porównania. |

**Zwraca:**
boolean - Prawda, jeśli obiekty są równe, w przeciwnym razie fałsz.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Zwraca hash.

**Zwraca:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Zwraca slajd-rodzic obrazu. Tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)