---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Meghatározza egy diagram elem tényleges pozícióját.
type: docs
url: /hu/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Meghatározza egy diagram elem tényleges pozícióját.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getActualX()](#getActualX--) | Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához viszonyítva. |
| [getActualY()](#getActualY--) | Meghatározza a diagram elem tényleges felső helyzetét a diagram bal felső sarkához viszonyítva. |
| [getActualWidth()](#getActualWidth--) | Meghatározza a diagram elem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Meghatározza a diagram elem tényleges magasságát. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Meghatározza a diagram elem tényleges felső helyzetét a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasható float.

**Visszatér:**
float