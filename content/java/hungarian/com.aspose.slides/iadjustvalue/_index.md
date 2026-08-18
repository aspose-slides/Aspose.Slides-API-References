---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: A geometriai alakzat beállítási értékét képviseli.
type: docs
url: /hu/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

A geometriai alakzat beállítási értékét képviseli. Ezek az értékek befolyásolják az alakzat formáját.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRawValue()](#getRawValue--) | Visszaadja vagy beállítja a módosítási értéket "ahogy van". |
| [setRawValue(long value)](#setRawValue-long-) | Visszaadja vagy beállítja a módosítási értéket "ahogy van". |
| [getAngleValue()](#getAngleValue--) | Visszaadja vagy beállítja az értéket, fokban kifejezett szögeknek értelmezve. |
| [setAngleValue(float value)](#setAngleValue-float-) | Visszaadja vagy beállítja az értéket, fokban kifejezett szögeknek értelmezve. |
| [getName()](#getName--) | Visszaadja ennek a beállítási értéknek a nevét. |
| [getType()](#getType--) | Visszaadja a forma beállításának típusát. |
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


Visszaadja vagy beállítja az értéket, fokban kifejezett szögeknek értelmezve. Olvasás/írás float.

**Visszatér:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Visszaadja vagy beállítja az értéket, fokban kifejezett szögeknek értelmezve. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja ennek a beállítási értéknek a nevét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Visszaadja a forma beállításának típusát. Csak olvasható [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Visszatér:**
int