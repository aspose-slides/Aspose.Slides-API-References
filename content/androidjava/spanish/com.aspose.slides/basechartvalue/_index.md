---
title: BaseChartValue
second_title: Referencia de API de Java para Aspose.Slides en Android
description: Representa un valor de un gráfico.
type: docs
url: /es/com.aspose.slides/basechartvalue/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Representa un valor de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Especifica si la propiedad AsCell, AsCells, AsLiteralString o AsLiteralDouble es real en los descendientes. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Especifica si la propiedad AsCell, AsCells, AsLiteralString o AsLiteralDouble es real en los descendientes. |
| [getData()](#getData--) | Datos. |
| [setData(Object value)](#setData-java.lang.Object-) | Datos. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Especifica si la propiedad AsCell, AsCells, AsLiteralString o AsLiteralDouble es real en los descendientes. En otras palabras, especifica el tipo de valor de la propiedad Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Para los puntos en ChartDataPointCollection, esta propiedad es solo lectura. En este caso, para cambiar el valor de esta propiedad puede usar una de las propiedades ChartDataPointCollection.DataSourceTypeFor<...>.

**Devuelve:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Especifica si la propiedad AsCell, AsCells, AsLiteralString o AsLiteralDouble es real en los descendientes. En otras palabras, especifica el tipo de valor de la propiedad Data. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Para los puntos en ChartDataPointCollection, esta propiedad es solo lectura. En este caso, para cambiar el valor de esta propiedad puede usar una de las propiedades ChartDataPointCollection.DataSourceTypeFor<...>.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Datos. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Datos. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject