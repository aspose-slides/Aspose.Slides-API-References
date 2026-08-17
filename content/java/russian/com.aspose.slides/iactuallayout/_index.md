---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Указывает фактическое положение элемента диаграммы.
type: docs
url: /ru/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Указывает фактическое положение элемента диаграммы.
## Методы

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Указывает фактическое положение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. |
| [getActualY()](#getActualY--) | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. |
| [getActualWidth()](#getActualWidth--) | Указывает фактическую ширину элемента диаграммы. |
| [getActualHeight()](#getActualHeight--) | Указывает фактическую высоту элемента диаграммы. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Указывает фактическое положение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() прежде, чтобы получить фактические значения. Читать float.

**Returns:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() прежде, чтобы получить фактические значения. Читать float.

**Returns:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() прежде, чтобы получить фактические значения. Читать float.

**Returns:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() прежде, чтобы получить фактические значения. Читать float.

**Returns:**
float