---
title: Picture
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Bild in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/picture/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Stellt ein Bild in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Gibt das eingebettete Bild zurück oder setzt es. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Gibt das eingebettete Bild zurück oder setzt es. |
| [getLinkPathLong()](#getLinkPathLong--) | Gibt die URL des verknüpften Bildes zurück oder setzt sie. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Gibt die URL des verknüpften Bildes zurück oder setzt sie. |
| [getImageTransform()](#getImageTransform--) | Gibt die Sammlung von Bildtransformations-Effekten zurück. |
| [getPresentation()](#getPresentation--) | Gibt die Präsentation zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vergleicht mit dem angegebenen Objekt. |
| [hashCode()](#hashCode--) | Gibt den Hash zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Bildes zurück. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Nur lesbar long.

**Rückgabe:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Gibt das übergeordnete IPresentationComponent zurück. Nur lesbar [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabe:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```

Gibt das eingebettete Bild zurück oder setzt es. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

**Rückgabe:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

Gibt das eingebettete Bild zurück oder setzt es. Lesen/Schreiben [IPPImage](../../com.aspose.slides/ippimage).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Gibt die URL des verknüpften Bildes zurück oder setzt sie. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Gibt die URL des verknüpften Bildes zurück oder setzt sie. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

Gibt die Sammlung von Bildtransformations-Effekten zurück. Nur lesbar [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Rückgabe:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die Präsentation zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vergleicht mit dem angegebenen Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Zu vergleichendes Objekt. |

**Rückgabe:**
boolean – Wahr, wenn Objekte gleich sind, sonst falsch.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Gibt den Hash zurück.

**Rückgabe:**
int – Hash.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines Bildes zurück. Nur lesbar [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)