---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Represents a cached chart value (e.g., X, Y, bubble size, or the main value).
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Gets the cached data object. |
| [toDouble()](#toDouble--) | Converts the cached value to a double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Gets the cached data object. Read-only  Object .

**Returns:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converts the cached value to a double.

**Returns:**
double - The numeric representation, or Double.NaN if Data (\#getData.getData) is null or cannot be converted to a double.
