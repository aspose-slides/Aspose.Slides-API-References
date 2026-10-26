---
title: ChartDataPoint
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o ponto de dados da série.
type: docs
url: /pt/com.aspose.slides/chartdatapoint/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Representa o ponto de dados da série.
## Métodos

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Retorna o valor de tamanho do ponto de dados do gráfico. |
| [getColorValue()](#getColorValue--) | Retorna o valor de cor do ponto de dados do gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa os valores das barras de erro da série no caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [getExplosion()](#getExplosion--) | Especifica a quantidade que o ponto de dados deve ser deslocado do centro do gráfico de pizza. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica a quantidade que o ponto de dados deve ser deslocado do centro do gráfico de pizza. |
| [getFormat()](#getFormat--) | Representa as propriedades de formatação. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa as propriedades de formatação. |
| [getMarker()](#getMarker--) | Especifica um marcador de dados. |
| [getSetAsTotal()](#getSetAsTotal--) | Define o ponto de dados como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Define o ponto de dados como total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico da lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Remove DataPoint da série de gráfico. |
| [getDataPointLevels()](#getDataPointLevels--) | Retorna o contêiner de níveis de ponto de dados. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retorna uma cor automática do ponto de dados com base no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [getActualX()](#getActualX--) | Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualY()](#getActualY--) | Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. |
| [getActualWidth()](#getActualWidth--) | Especifica a largura real do elemento do gráfico. |
| [getActualHeight()](#getActualHeight--) | Especifica a altura real do elemento do gráfico. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Somente leitura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retorna:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Retorna o valor de tamanho do ponto de dados do gráfico. Usado com gráficos Treemap e Sunburst. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Retorna o valor de cor do ponto de dados do gráfico. Usado com gráficos de mapa. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Representa os valores das barras de erro da série no caso de tipo de valor Custom. Somente leitura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retorna:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Somente leitura [IDataLabel](../../com.aspose.slides/idatalabel).

**Retorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Especifica que as bolhas têm um efeito 3D aplicado a elas. Leitura/Gravação boolean.

**Retorna:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Especifica que as bolhas têm um efeito 3D aplicado a elas. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. Leitura/Gravação int.

**Retorna:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Especifica a quantidade que o ponto de dados deve ser deslocado do centro da pizza. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Representa as propriedades de formatação. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Representa as propriedades de formatação. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Especifica um marcador de dados. Somente leitura [IMarker](../../com.aspose.slides/imarker).

**Retorna:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall.

**Retorna:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Define o ponto de dados como total. Aplicado apenas para o tipo de série Waterfall.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Propriedades da entrada de legenda correspondente no caso de tipo de gráfico da lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```


Remove DataPoint da série de gráfico.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Retorna o contêiner de níveis de ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis de ponto de dados começa em zero.

**Retorna:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Retorna:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```


Retorna uma cor automática do ponto de dados com base no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e estilo do gráfico. Esta cor é usada por padrão se FillType for igual a NotDefined.

**Retorna:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/Gravação boolean.

**Retorna:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Especifica a localização x real (esquerda) do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```


Especifica o topo real do elemento do gráfico em relação ao canto superior esquerdo do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Especifica a largura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Especifica a altura real do elemento do gráfico. Chame o método IChart.ValidateChartLayout() antes para obter valores reais. Leitura float.

**Retorna:**
float