---
title: IBaseChartValue
second_title: Aspose.Slides para Android via Referencia de API Java
description: Representa un valor de un gráfico.
type: docs
url: /es/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Representa un valor de un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble es actual. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble es actual. |
| [getData()](#getData--) | Lectura/escritura Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lectura/escritura Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble es actual. En otras palabras, especifica el tipo de valor de la propiedad Data. Esta propiedad es solo lectura. Para cambiar el valor de esta propiedad puede usar una de las propiedades ChartDataPointCollection.DataSourceTypeFor<...>. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Devuelve:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Especifica si la propiedad AsCell o AsLiteralString o AsLiteralDouble es actual. En otras palabras, especifica el tipo de valor de la propiedad Data. Esta propiedad es solo lectura. Para cambiar el valor de esta propiedad puede usar una de las propiedades ChartDataPointCollection.DataSourceTypeFor<...>. Lectura/escritura [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |