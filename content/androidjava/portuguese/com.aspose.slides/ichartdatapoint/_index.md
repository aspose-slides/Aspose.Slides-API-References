---
title: IChartDataPoint
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o ponto de dados da série.
type: docs
url: /pt/com.aspose.slides/ichartdatapoint/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Representa o ponto de dados da série.
## Métodos

| Método | Descrição |
| --- | --- |
| [getXValue()](#getXValue--) | Retorna o valor x do ponto de dados do gráfico. |
| [getYValue()](#getYValue--) | Retorna o valor y do ponto de dados do gráfico. |
| [getBubbleSize()](#getBubbleSize--) | Retorna o tamanho da bolha do ponto de dados do gráfico. |
| [getValue()](#getValue--) | Retorna o valor do ponto de dados do gráfico. |
| [getSizeValue()](#getSizeValue--) | Retorna o valor de tamanho do ponto de dados do gráfico. |
| [getColorValue()](#getColorValue--) | Retorna o valor de cor do ponto de dados do gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa os valores das barras de erro da série no caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Representa o rótulo do ponto de dados do gráfico. |
| [isBubble3D()](#isBubble3D--) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [getExplosion()](#getExplosion--) | Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. |
| [getFormat()](#getFormat--) | Representa as propriedades de formatação. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa as propriedades de formatação. |
| [getMarker()](#getMarker--) | Especifica um marcador de dados. |
| [remove()](#remove--) | Remove o DataPoint da série de gráficos. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Define o ponto de dados como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Define o ponto de dados como total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [getDataPointLevels()](#getDataPointLevels--) | Retorna o contêiner dos níveis do ponto de dados. |
| [getIndex()](#getIndex--) | Determina a qual coleção de filhos do pai este ponto de dados se aplica. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Retorna o valor x do ponto de dados do gráfico. Somente leitura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retorna:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Retorna o valor y do ponto de dados do gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Retorna o tamanho da bolha do ponto de dados do gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Retorna o valor do ponto de dados do gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Retorna o valor de tamanho do ponto de dados do gráfico. Usado com gráficos Treemap e Sunburst. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Retorna o valor de cor do ponto de dados do gráfico. Usado com gráficos de Mapa. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representa os valores das barras de erro da série no caso de tipo de valor Custom. Somente leitura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retorna:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representa o rótulo do ponto de dados do gráfico. Somente leitura [IDataLabel](../../com.aspose.slides/idatalabel).

**Retorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

Especifica que as bolhas têm um efeito 3D aplicado a elas. Leitura/gravação boolean.

**Retorna:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

Especifica que as bolhas têm um efeito 3D aplicado a elas. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. Leitura/gravação int.

**Retorna:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa as propriedades de formatação. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa as propriedades de formatação. Leitura/gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Especifica um marcador de dados. Somente leitura [IMarker](../../com.aspose.slides/imarker).

**Retorna:**
[IMarker](../../com.aspose.slides/imarker)

### remove() {#remove--}
```
public abstract void remove()
```

Remove o DataPoint da série de gráficos.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. Essa cor é usada por padrão se FillType for NotDefined.

**Retorna:**
java.lang.Integer - Cor automática do ponto de dados java.lang.Integer

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall.

**Retorna:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/gravação boolean.

**Retorna:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Retorna o contêiner dos níveis do ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis do ponto de dados inicia em zero.

**Retorna:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Determina a qual coleção de filhos do pai este ponto de dados se aplica. Leitura long.

**Retorna:**
long