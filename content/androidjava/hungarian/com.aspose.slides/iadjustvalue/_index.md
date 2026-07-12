---
title: IAdjustValue
second_title: Aspose.Slides for Android Java API Referenciája
description: Geometriai alakzatok módosítási értékét képviseli.
type: docs
url: /hu/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

A geometriai alakzat módosítási értékét képviseli. Ezek az értékek befolyásolják az alakzat formáját.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRawValue()](#getRawValue--) | Returns or sets adjustment value "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Returns or sets adjustment value "as is". |
| [getAngleValue()](#getAngleValue--) | Returns or sets value, interpreting it as angle in degrees. |
| [setAngleValue(float value)](#setAngleValue-float-) | Returns or sets value, interpreting it as angle in degrees. |
| [getName()](#getName--) | Returns a name of this adjustment value. |
| [getType()](#getType--) | Returns the type of the shape adjustment. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Visszaadja vagy beállítja a módosítási értéket "ahogy van". Olvasás/írás long.

**Visszatér:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Visszaadja vagy beállítja a módosítási értéket "ahogy van". Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Visszaadja vagy beállítja az értéket, fokban értelmezve. Olvasás/írás float.

**Visszatér:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Visszaadja vagy beállítja az értéket, fokban értelmezve. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja ennek a módosítási értéknek a nevét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Visszaadja az alakzat módosításának típusát. Csak olvasható [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Visszatér:**
int