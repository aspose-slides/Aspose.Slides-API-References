---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies actual position of a chart element.
type: docs
url: /sv/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Anger den faktiska positionen för ett diagram-element.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagram-elementet i förhållande till diagrammets vänstra övre hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska överkanten för diagram-elementet i förhållande till diagrammets vänstra övre hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden på diagram-elementet. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden på diagram-elementet. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Anger den faktiska x-positionen (vänster) för diagram-elementet i förhållande till diagrammets vänstra övre hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Anger den faktiska överkanten för diagram-elementet i förhållande till diagrammets vänstra övre hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Anger den faktiska bredden på diagram-elementet. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Anger den faktiska höjden på diagram-elementet. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float