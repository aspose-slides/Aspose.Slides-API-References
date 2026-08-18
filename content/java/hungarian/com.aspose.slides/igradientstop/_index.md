---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Egy színátmenet formátumot reprezentál.
type: docs
url: /hu/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Egy színátmenet formátumot reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). |
| [setPosition(float value)](#setPosition-float-) | Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). |
| [getColor()](#getColor--) | Visszaadja egy gradient stop színét. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). Olvasás/írás float.

**Visszatér:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Visszaadja egy gradient stop színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)