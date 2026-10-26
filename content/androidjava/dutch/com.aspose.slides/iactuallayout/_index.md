---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specificeert de werkelijke positie van een chart-element.
type: docs
url: /nl/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Specificeert de werkelijke positie van een chart-element.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getActualX()](#getActualX--) | Specificeert de werkelijke x-locatie (links) van het chart-element ten opzichte van de linkerbovenhoek van de chart. |
| [getActualY()](#getActualY--) | Specificeert de werkelijke bovenkant van het chart-element ten opzichte van de linkerbovenhoek van de chart. |
| [getActualWidth()](#getActualWidth--) | Specificeert de werkelijke breedte van het chart-element. |
| [getActualHeight()](#getActualHeight--) | Specificeert de werkelijke hoogte van het chart-element. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Specificeert de werkelijke x-locatie (links) van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Retourwaarde:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Specificeert de werkelijke bovenkant van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Retourwaarde:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Specificeert de werkelijke breedte van het chart-element. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Retourwaarde:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Specificeert de werkelijke hoogte van het chart-element. Roep methode IChart.ValidateChartLayout() aan voordat u de werkelijke waarden krijgt. Lezen float.

**Retourwaarde:**
float