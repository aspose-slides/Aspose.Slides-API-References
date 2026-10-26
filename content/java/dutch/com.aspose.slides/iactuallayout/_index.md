---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Specificeert de daadwerkelijke positie van een chart-element.
type: docs
url: /nl/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Specificeert de daadwerkelijke positie van een chart-element.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getActualX()](#getActualX--) | Specificeert de daadwerkelijke x-locatie (links) van het chart-element ten opzichte van de linkerbovenhoek van de chart. |
| [getActualY()](#getActualY--) | Specificeert de daadwerkelijke bovenkant van het chart-element ten opzichte van de linkerbovenhoek van de chart. |
| [getActualWidth()](#getActualWidth--) | Specificeert de daadwerkelijke breedte van het chart-element. |
| [getActualHeight()](#getActualHeight--) | Specificeert de daadwerkelijke hoogte van het chart-element. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Specificeert de daadwerkelijke x-locatie (links) van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode IChart.ValidateChartLayout() aan voordat de daadwerkelijke waarden worden opgehaald. Lees float.

**Retour:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Specificeert de daadwerkelijke bovenkant van het chart-element ten opzichte van de linkerbovenhoek van de chart. Roep methode IChart.ValidateChartLayout() aan voordat de daadwerkelijke waarden worden opgehaald. Lees float.

**Retour:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Specificeert de daadwerkelijke breedte van het chart-element. Roep methode IChart.ValidateChartLayout() aan voordat de daadwerkelijke waarden worden opgehaald. Lees float.

**Retour:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Specificeert de daadwerkelijke hoogte van het chart-element. Roep methode IChart.ValidateChartLayout() aan voordat de daadwerkelijke waarden worden opgehaald. Lees float.

**Retour:**
float