---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Anger den faktiska positionen för ett diagramobjekt.
type: docs
url: /sv/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Anger den faktiska positionen för ett diagramobjekt.
## Metoder

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Anger den faktiska x-positionen (vänster) för diagramobjektet i förhållande till diagrammets vänstra övre hörn. |
| [getActualY()](#getActualY--) | Anger den faktiska övre kanten för diagramobjektet i förhållande till diagrammets vänstra övre hörn. |
| [getActualWidth()](#getActualWidth--) | Anger den faktiska bredden på diagramobjektet. |
| [getActualHeight()](#getActualHeight--) | Anger den faktiska höjden på diagramobjektet. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Anger den faktiska x-positionen (vänster) för diagramobjektet i förhållande till diagrammets vänstra övre hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Anger den faktiska övre kanten för diagramobjektet i förhållande till diagrammets vänstra övre hörn. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Anger den faktiska bredden på diagramobjektet. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Anger den faktiska höjden på diagramobjektet. Anropa metoden IChart.ValidateChartLayout() innan för att få de faktiska värdena. Läs float.

**Returnerar:**
float