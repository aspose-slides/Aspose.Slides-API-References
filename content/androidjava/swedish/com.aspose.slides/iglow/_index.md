---
title: IGlow
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Glow-effekt där en färgfördimmad kontur läggs till utanför objektets kanter.
type: docs
url: /sv/com.aspose.slides/iglow/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Representerar en Glow-effekt, där en färgfördimmad kontur läggs till utanför objektets kanter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Radie. |
| [setRadius(double value)](#setRadius-double-) | Radie. |
| [getColor()](#getColor--) | Färgformat. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Radie. Läs/skriv double.

**Returnerar:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Radie. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Färgformat. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)