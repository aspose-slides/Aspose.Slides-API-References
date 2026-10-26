---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /it/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Rappresenta un valore di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifica se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva. |
| [getData()](#getData--) | Lettura/Scrittura Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lettura/Scrittura Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Specifică se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva. In altre parole specifica il tipo di valore della proprietà Data. Questa proprietà è di sola lettura. Per cambiare il valore di questa proprietà è possibile utilizzare una delle proprietà ChartDataPointCollection.DataSourceTypeFor<...>. Lettura/Scrittura [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Restituisce:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Specifică se la proprietà AsCell o AsLiteralString o AsLiteralDouble è effettiva. In altre parole specifica il tipo di valore della proprietà Data. Questa proprietà è di sola lettura. Per cambiare il valore di questa proprietà è possibile utilizzare una delle proprietà ChartDataPointCollection.DataSourceTypeFor<...>. Lettura/Scrittura [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Lettura/Scrittura Object.

**Restituisce:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lettura/Scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |