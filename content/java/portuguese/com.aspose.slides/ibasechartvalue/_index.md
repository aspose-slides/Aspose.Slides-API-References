---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /pt/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Representa um valor de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está atual. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está atual. |
| [getData()](#getData--) | Leitura/gravação Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Leitura/gravação Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está atual. Em outras palavras, especifica o tipo de valor da propriedade Data. Esta propriedade é somente leitura. Para alterar o valor desta propriedade, você pode usar uma das propriedades ChartDataPointCollection.DataSourceTypeFor<...>. Leitura/gravação [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Retorna:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Especifica se a propriedade AsCell ou AsLiteralString ou AsLiteralDouble está atual. Em outras palavras, especifica o tipo de valor da propriedade Data. Esta propriedade é somente leitura. Para alterar o valor desta propriedade, você pode usar uma das propriedades ChartDataPointCollection.DataSourceTypeFor<...>. Leitura/gravação [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |