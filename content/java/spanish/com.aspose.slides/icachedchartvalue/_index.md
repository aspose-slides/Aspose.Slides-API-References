---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /es/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Representa un valor de gráfico almacenado en caché (p. ej., X, Y, tamaño de burbuja o el valor principal).
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Obtiene el objeto de datos almacenado en caché. |
| [toDouble()](#toDouble--) | Convierte el valor almacenado en caché a un double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Obtiene el objeto de datos almacenado en caché. Solo lectura  Object .

**Returns:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Convierte el valor almacenado en caché a un double.

**Returns:**
double - La representación numérica, o Double.NaN si Data (\#getData.getData) es nulo o no puede convertirse a un double.