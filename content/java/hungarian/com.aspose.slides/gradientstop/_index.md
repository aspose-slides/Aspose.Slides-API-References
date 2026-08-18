---
title: GradientStop
second_title: Aspose.Slides Java API-referencia
description: Képviseli a gradient formátumot.
type: docs
url: /hu/com.aspose.slides/gradientstop/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Az összes megvalósított interfész:**  
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)  
```
public final class GradientStop extends PVIObject implements IGradientStop
```

Képviseli a gradient formátumot.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). |
| [setPosition(float value)](#setPosition-float-) | Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). |
| [getColor()](#getColor--) | Visszaadja egy gradient stop színét. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**  
long

### getPosition() {#getPosition--}
```
public final float getPosition()
```

Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). Olvasás/írás float.

**Visszatér:**  
float

### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

Visszaadja vagy beállítja egy gradient stop pozícióját (0..1). Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Visszaadja egy gradient stop színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)