---
title: ISlidesPicture
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: Egy képet ábrázol egy prezentációban.
type: docs
url: /hu/com.aspose.slides/islidespicture/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Egy képet képvisel a prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getImage()](#getImage--) | Visszaadja vagy beállítja a beágyazott képet. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Visszaadja vagy beállítja a beágyazott képet. |
| [getLinkPathLong()](#getLinkPathLong--) | Visszaadja vagy beállítja a kapcsolt kép URL-jét. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Visszaadja vagy beállítja a kapcsolt kép URL-jét. |
| [getImageTransform()](#getImageTransform--) | Visszaadja a kép transzformációs effektusok gyűjteményét. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Visszaadja vagy beállítja a beágyazott képet. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

**Visszatérési érték:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Visszaadja vagy beállítja a beágyazott képet. Olvasás/írás [IPPImage](../../com.aspose.slides/ippimage).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Visszaadja vagy beállítja a kapcsolt kép URL-jét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Visszaadja vagy beállítja a kapcsolt kép URL-jét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Visszaadja a kép transzformációs effektusok gyűjteményét. Csak olvasható [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Visszatérési érték:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)