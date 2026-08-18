---
title: Picture
second_title: Aspose.Slides Java API Referenciája
description: Egy prezentációban lévő képet képvisel.
type: docs
url: /hu/com.aspose.slides/picture/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Képet képvisel egy prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Visszaadja vagy beállítja a beágyazott képet. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Visszaadja vagy beállítja a beágyazott képet. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja a kapcsolt kép URL-címét. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja a kapcsolt kép URL-címét. |
| [getImageTransform()](#getImageTransform--) | Visszaadja a képtranszformációs hatások gyűjteményét. |
| [getPresentation()](#getPresentation--) | Visszaadja a prezentációt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Összehasonlítja a megadott objektummal. |
| [hashCode()](#hashCode--) | Visszaadja a hash értéket. |
| [getSlide()](#getSlide--) | Visszaadja a kép szülő diáját. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Visszaadja a szülő IPresentationComponent-et. Csak olvasható [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Visszaadja vagy beállítja a beágyazott képet. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

**Visszatér:**
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

Visszaadja vagy beállítja a kapcsolt kép URL-címét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Visszaadja vagy beállítja a kapcsolt kép URL-címét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Visszaadja a képtranszformációs hatások gyűjteményét. Csak olvasható [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Visszatér:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a prezentációt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Összehasonlítja a megadott objektummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az összehasonlítandó objektum. |

**Visszatér:**
boolean – Igaz, ha az objektumok egyenlőek, egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Visszaadja a hash értéket.

**Visszatér:**
int – Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a kép szülő diáját. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)