---
title: BaseChartValue
second_title: Referência da API Aspose.Slides para Java
description: Representa um valor de um gráfico.
type: docs
url: /pt/com.aspose.slides/basechartvalue/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Representa um valor de um gráfico.
## Métodos

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Especifica se a propriedade AsCell, AsCells, AsLiteralString ou AsLiteralDouble está presente nos descendentes. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Especifica se a propriedade AsCell, AsCells, AsLiteralString ou AsLiteralDouble está presente nos descendentes. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Especifica se a propriedade AsCell, AsCells, AsLiteralString ou AsLiteralDouble está presente nos descendentes. Em outras palavras, especifica o tipo de valor da propriedade Data. Leitura/gravação [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Para pontos em ChartDataPointCollection esta propriedade é somente leitura. Nesse caso, para alterar o valor desta propriedade, você pode usar uma das propriedades ChartDataPointCollection.DataSourceTypeFor<...>.

**Retorna:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Especifica se a propriedade AsCell, AsCells, AsLiteralString ou AsLiteralDouble está presente nos descendentes. Em outras palavras, especifica o tipo de valor da propriedade Data. Leitura/gravação [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Para pontos em ChartDataPointCollection esta propriedade é somente leitura. Nesse caso, para alterar o valor desta propriedade, você pode usar uma das propriedades ChartDataPointCollection.DataSourceTypeFor<...>.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. Leitura/gravação Object.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject