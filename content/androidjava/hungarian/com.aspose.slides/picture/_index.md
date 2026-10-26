---
title: Picture
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy képet képvisel egy prezentációban.
type: docs
url: /hu/com.aspose.slides/picture/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Egy képet képvisel egy prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Visszaadja vagy beállítja a beágyazott képet. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Visszaadja vagy beállítja a beágyazott képet. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja a kapcsolt kép URL-jét. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja a kapcsolt kép URL-jét. |
| [getImageTransform()](#getImageTransform--) | Visszaadja a kép transzformációs effektusok gyűjteményét. |
| [getPresentation()](#getPresentation--) | Visszaadja a prezentációt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Összehasonlítja a megadott objektummal. |
| [hashCode()](#hashCode--) | Visszaadja a hash értéket. |
| [getSlide()](#getSlide--) | Visszaadja a kép szülő diáját. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszaadja:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verzió. Csak olvasható long.

**Visszaadja:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Visszaadja az IPresentationComponent szülőjét. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszaadja:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Visszaadja vagy beállítja a beágyazott képet. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

**Visszaadja:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Visszaadja vagy beállítja a beágyazott képet. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Visszaadja vagy beállítja a kapcsolt kép URL-jét. Olvasás/írás String.

**Visszaadja:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja vagy beállítja a kapcsolt kép URL-jét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Visszaadja a kép transzformációs effektusok gyűjteményét. Csak olvasható [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Visszaadja:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a prezentációt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszaadja:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Összehasonlítja a megadott objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Összehasonlítandó objektum. |

**Visszaadja:**
boolean - Igaz, ha az objektumok egyenlőek, egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Visszaadja a hash értéket.

**Visszaadja:**
int - Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a kép szülő diáját. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszaadja:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)