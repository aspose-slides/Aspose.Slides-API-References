---
title: IBlur
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltést is, alkalmazva van.
type: docs
url: /hu/com.aspose.slides/iblur/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltést is, alkalmazva van. Minden színcsatorna, beleértve az alfát is, érintett.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Visszatér vagy beállítja a blur sugarát. |
| [setRadius(double value)](#setRadius-double-) | Visszatér vagy beállítja a blur sugarát. |
| [getGrow()](#getGrow--) | Meghatározza, hogy az objektum határait a elmosódás eredményeként növelni kell-e. |
| [setGrow(boolean value)](#setGrow-boolean-) | Meghatározza, hogy az objektum határait a elmosódás eredményeként növelni kell-e. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Visszatér vagy beállítja a blur sugarát. Olvasás/írás double.

**Visszatér:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Visszatér vagy beállítja a blur sugarát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Meghatározza, hogy az objektum határait a elmosódás eredményeként növelni kell-e. True azt jelzi, hogy a határok megnövekednek, false azt jelzi, hogy nem. Olvasás/írás boolean.

**Visszatér:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Meghatározza, hogy az objektum határait a elmosódás eredményeként növelni kell-e. True azt jelzi, hogy a határok megnövekednek, false azt jelzi, hogy nem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |