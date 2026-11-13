---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Representerar ett cachat diagramvärde t.ex. X Y bubbelformat eller huvudvärdet.
type: docs
url: /sv/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Representerar ett cachat diagramvärde (t.ex. X, Y, bubbelformat eller huvudvärdet).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getData()](#getData--) | Hämtar det cachade dataobjektet. |
| [toDouble()](#toDouble--) | Konverterar det cachade värdet till en double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Hämtar det cachade dataobjektet. skrivskyddad  Object .

**Returnerar:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Konverterar det cachade värdet till en double.

**Returnerar:**
double - Den numeriska representationen, eller Double.NaN om Data (\#getData.getData) är null eller inte kan konverteras till en double.