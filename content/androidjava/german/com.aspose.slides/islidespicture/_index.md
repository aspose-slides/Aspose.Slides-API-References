---
title: ISlidesPicture
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein Bild in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/islidespicture/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

Stellt ein Bild in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getImage()](#getImage--) | Gibt das eingebettete Bild zurück oder legt es fest. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Gibt das eingebettete Bild zurück oder legt es fest. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt die URL des verknüpften Bildes zurück oder legt sie fest. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt die URL des verknüpften Bildes zurück oder legt sie fest. |
| [getImageTransform()](#getImageTransform--) | Gibt die Sammlung der Bildtransformations-Effekte zurück. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Gibt das eingebettete Bild zurück oder legt es fest. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

**Rückgabe:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Gibt das eingebettete Bild zurück oder legt es fest. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Gibt die URL des verknüpften Bildes zurück oder legt sie fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Gibt die URL des verknüpften Bildes zurück oder legt sie fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Gibt die Sammlung der Bildtransformations-Effekte zurück. Nur lesen [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Rückgabe:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)