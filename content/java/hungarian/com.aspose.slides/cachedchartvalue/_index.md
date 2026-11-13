---
title: CachedChartValue
second_title: Aspose.Slides Java API hivatkozás
description: Egy gyorsítótárazott diagramértéket képvisel, pl. X, Y, buborékméret vagy a fő érték.
type: docs
url: /hu/com.aspose.slides/cachedchartvalue/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Egy gyorsítótárazott diagramértéket képvisel (például X, Y, buborékméret vagy a fő érték).

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [toString()](#toString--) | Visszaadja a gyorsítótárazott érték karakterlánc reprezentációját. |
| [toDouble()](#toDouble--) | Átalakítja a gyorsítótárazott értéket double típusúra. |
| [getData()](#getData--) | Lekéri a gyorsítótárazott adatobjektumot. |

### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```

### toString() {#toString--}
```
public String toString()
```

Visszaadja a gyorsítótárazott érték karakterlánc reprezentációját.

**Visszatér:**  
java.lang.String

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Átalakítja a gyorsítótárazott értéket double típusúra.

**Visszatér:**  
double - A numerikus reprezentáció, vagy Double.NaN, ha a Data (\#getData.getData/\#setData(Object).setData(Object)) null, vagy nem konvertálható double típusra.

### getData() {#getData--}
```
public final Object getData()
```

Lekéri a gyorsítótárazott adatobjektumot. Csak olvasható Object .

**Visszatér:**  
java.lang.Object