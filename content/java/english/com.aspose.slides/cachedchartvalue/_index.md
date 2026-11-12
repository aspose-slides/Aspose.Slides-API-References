---
title: CachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /com.aspose.slides/cachedchartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Represents a cached chart value (e.g., X, Y, bubble size, or the main value).
## Constructors

| Constructor | Description |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Returns a string representation of the cached value. |
| [toDouble()](#toDouble--) | Converts the cached value to a double. |
| [getData()](#getData--) | Gets the cached data object. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Returns a string representation of the cached value.

**Returns:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converts the cached value to a double.

**Returns:**
double - The numeric representation, or Double.NaN if Data (\#getData.getData/\#setData(Object).setData(Object)) is null or cannot be converted to a double.
### getData() {#getData--}
```
public final Object getData()
```


Gets the cached data object. Read-only  Object .

**Returns:**
java.lang.Object
