---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /hu/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Megadja a diagram elem tényleges pozícióját.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getActualX()](#getActualX--) | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához képest. |
| [getActualY()](#getActualY--) | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. |
| [getActualWidth()](#getActualWidth--) | Megadja a diagram elem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Megadja a diagram elem tényleges magasságát. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előbb a tényleges értékek lekéréséhez. Olvas float.

**Visszatér:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust előbb a tényleges értékek lekéréséhez. Olvas float.

**Visszatér:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előbb a tényleges értékek lekéréséhez. Olvas float.

**Visszatér:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előbb a tényleges értékek lekéréséhez. Olvas float.

**Visszatér:**
float