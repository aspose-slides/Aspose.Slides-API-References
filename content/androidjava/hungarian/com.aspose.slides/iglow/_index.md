---
title: IGlow
second_title: Aspose.Slides Androidra a Java API-referencia segítségével
description: A Glow effektust ábrázolja, amelyben egy színes elmosódott körvonal kerül az objektum széleihez kívül.
type: docs
url: /hu/com.aspose.slides/iglow/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Egy Glow effektust ábrázol, amelynél egy színes elmosott körvonal kerül az objektum széleihez kívül.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Sugár. |
| [setRadius(double value)](#setRadius-double-) | Sugár. |
| [getColor()](#getColor--) | Színformátum. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Sugár. Olvasás/írás double.

**Visszatérési érték:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Sugár. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Színformátum. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)