---
title: IColorChange
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Farbwechsel-Effekt dar.
type: docs
url: /de/com.aspose.slides/icolorchange/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Stellt einen Farbwechsel-Effekt dar. Instanzen von FromColor werden durch Instanzen von ToColor ersetzt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFromColor()](#getFromColor--) | Farbe, die ersetzt wird. |
| [getToColor()](#getToColor--) | Farbe, die als Ersatz dient. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

Farbe, die ersetzt wird. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

Farbe, die als Ersatz dient. Nur lesbar [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)