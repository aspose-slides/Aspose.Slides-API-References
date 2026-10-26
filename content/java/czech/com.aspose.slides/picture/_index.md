---
title: Picture
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje obrázek v prezentaci.
type: docs
url: /cs/com.aspose.slides/picture/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Reprezentuje obrázek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Vrací nebo nastavuje vložený obrázek. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Vrací nebo nastavuje vložený obrázek. |
| [getLinkPathLong()](#getLinkPathLong--) | Vrací nebo nastavuje URL propojeného obrázku. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Vrací nebo nastavuje URL propojeného obrázku. |
| [getImageTransform()](#getImageTransform--) | Vrací kolekci efektů transformace obrazu. |
| [getPresentation()](#getPresentation--) | Vrací prezentaci. |
| [equals(Object obj)](#equals-java.lang.Object-) | Porovnává s určeným objektem. |
| [hashCode()](#hashCode--) | Vrací hash. |
| [getSlide()](#getSlide--) | Vrací rodičovský snímek obrázku. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Vrací rodičovský IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


Vrací nebo nastavuje vložený obrázek. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

**Vrací:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


Vrací nebo nastavuje vložený obrázek. Čtení/zápis [IPPImage](../../com.aspose.slides/ippimage).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Vrací nebo nastavuje URL propojeného obrázku. Čtení/zápis String.

**Vrací:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Vrací nebo nastavuje URL propojeného obrázku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


Vrací kolekci efektů transformace obrazu. Pouze pro čtení [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Vrací:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací prezentaci. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Porovnává s určeným objektem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt k porovnání. |

**Vrací:**
boolean - True pokud jsou objekty rovny, jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vrací hash.

**Vrací:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Vrací rodičovský snímek obrázku. Pouze pro čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)