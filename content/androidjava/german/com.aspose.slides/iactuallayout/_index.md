---
title: IActualLayout
second_title: Aspose.Slides für Android über Java API-Referenz
description: Gibt die tatsächliche Position eines chart-Elements an.
type: docs
url: /de/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Gibt die tatsächliche Position eines chart-Elements an.
## Methods

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Gibt die tatsächliche x-Position (links) des chart-Elements relativ zur linken oberen Ecke des chart an. |
| [getActualY()](#getActualY--) | Gibt die tatsächliche Oberkante des chart-Elements relativ zur linken oberen Ecke des chart an. |
| [getActualWidth()](#getActualWidth--) | Gibt die tatsächliche Breite des chart-Elements an. |
| [getActualHeight()](#getActualHeight--) | Gibt die tatsächliche Höhe des chart-Elements an. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Gibt die tatsächliche x-Position (links) des chart-Elements relativ zur linken oberen Ecke des chart an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lesen Sie float.

**Rückgabewert:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Gibt die tatsächliche Oberkante des chart-Elements relativ zur linken oberen Ecke des chart an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lesen Sie float.

**Rückgabewert:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Gibt die tatsächliche Breite des chart-Elements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lesen Sie float.

**Rückgabewert:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Gibt die tatsächliche Höhe des chart-Elements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lesen Sie float.

**Rückgabewert:**
float