---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /de/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Gibt die tatsächliche Position eines Diagrammelements an.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getActualX()](#getActualX--) | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualY()](#getActualY--) | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. |
| [getActualWidth()](#getActualWidth--) | Gibt die tatsächliche Breite des Diagrammelements an. |
| [getActualHeight()](#getActualHeight--) | Gibt die tatsächliche Höhe des Diagrammelements an. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lese float.

**Rückgabe:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lese float.

**Rückgabe:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lese float.

**Rückgabe:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, bevor Sie die tatsächlichen Werte erhalten. Lese float.

**Rückgabe:**
float