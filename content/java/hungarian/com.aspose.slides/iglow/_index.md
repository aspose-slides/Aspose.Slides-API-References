---
title: IGlow
second_title: Aspose.Slides for Java API referencia
description: Egy Glow effektust reprezentál, amelyben egy színes, elmosott kontúr kerül az objektum széleihez kívülre.
type: docs
url: /hu/com.aspose.slides/iglow/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Egy Glow effektust reprezentál, amelyben egy színes, elmosott kontúr kerül az objektum széleihez kívülre.
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

**Visszatér:**
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

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)