---
title: CachedChartValue
second_title: Aspose.Slides för Java API-referens
description: Representerar ett cachat diagramvärde, t.ex. X, Y, bubblestorlek eller huvudvärdet.
type: docs
url: /sv/com.aspose.slides/cachedchartvalue/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Representerar ett cachat diagramvärde (t.ex. X, Y, bubbla storlek eller huvudvärdet).
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [toString()](#toString--) | Returnerar en strängrepresentation av det cachade värdet. |
| [toDouble()](#toDouble--) | Konverterar det cachade värdet till en double. |
| [getData()](#getData--) | Hämtar det cachade dataobjektet. |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

Returnerar en strängrepresentation av det cachade värdet.

**Returnerar:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konverterar det cachade värdet till en double.

**Returnerar:**
double - Den numeriska representationen, eller Double.NaN om Data (\#getData.getData/\#setData(Object).setData(Object)) är null eller inte kan konverteras till en double.
### getData() {#getData--}
```
public final Object getData()
```

Hämtar det cachade dataobjektet. Skrivskyddad  Object .

**Returnerar:**
java.lang.Object