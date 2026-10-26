---
title: IBlur
second_title: Aspose.Slides Java API referencia
description: Egy Blur effektust reprezentál, amely az egész alakzatra, beleértve a kitöltést, alkalmazódik.
type: docs
url: /hu/com.aspose.slides/iblur/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Egy Blur effektust reprezentál, amely az egész alakzatra, beleértve a kitöltését, alkalmazódik. Minden színcsatorna, az alfa csatorna is, érintett.
## Metódusok

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Visszatér vagy beállítja az elmosási sugárát. |
| [setRadius(double value)](#setRadius-double-) | Visszatér vagy beállítja az elmosási sugárát. |
| [getGrow()](#getGrow--) | Meghatározza, hogy az objektum határait az elmosás következtében növelni kell-e. |
| [setGrow(boolean value)](#setGrow-boolean-) | Meghatározza, hogy az objektum határait az elmosás következtében növelni kell-e. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Visszatér vagy beállítja az elmosási sugárát. Olvasás/írás double.

**Visszatérési érték:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Visszatér vagy beállítja az elmosási sugárát. Olvasás/írás double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Meghatározza, hogy az objektum határait az elmosás következtében növelni kell-e. Az igaz érték jelzi, hogy a határok növekednek, míg a hamis érték jelzi, hogy nem növekednek. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Meghatározza, hogy az objektum határait az elmosás következtében növelni kell-e. Az igaz érték jelzi, hogy a határok növekednek, míg a hamis érték jelzi, hogy nem növekednek. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |