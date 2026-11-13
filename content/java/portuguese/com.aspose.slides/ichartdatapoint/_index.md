---
title: IChartDataPoint
second_title: Referência da API Aspose.Slides para Java
description: Representa ponto de dados da série.
type: docs
url: /pt/com.aspose.slides/ichartdatapoint/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Representa ponto de dados da série.
## Métodos

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | Obtém o valor x de um ponto de dados de gráfico. |
| [getYValue()](#getYValue--) | Obtém o valor y de um ponto de dados de gráfico. |
| [getBubbleSize()](#getBubbleSize--) | Obtém o tamanho da bolha de um ponto de dados de gráfico. |
| [getValue()](#getValue--) | Obtém o valor de um ponto de dados de gráfico. |
| [getCachedXValue()](#getCachedXValue--) | Obtém o valor X em cache de um ponto de dados de gráfico. |
| [getCachedYValue()](#getCachedYValue--) | Obtém o valor Y em cache de um ponto de dados de gráfico. |
| [getCachedValue()](#getCachedValue--) | Obtém o valor em cache de um ponto de dados de gráfico. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Obtém o tamanho da bolha em cache de um ponto de dados de gráfico. |
| [getSizeValue()](#getSizeValue--) | Obtém o valor de tamanho de um ponto de dados de gráfico. |
| [getColorValue()](#getColorValue--) | Obtém o valor de cor de um ponto de dados de gráfico. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Representa valores de barras de erro da série no caso de tipo de valor Custom. |
| [getLabel()](#getLabel--) | Representa o rótulo do ponto de dados de gráfico. |
| [isBubble3D()](#isBubble3D--) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Especifica que as bolhas têm um efeito 3D aplicado a elas. |
| [getExplosion()](#getExplosion--) | Especifica a quantidade que o ponto de dados deve ser movido do centro do gráfico de pizza. |
| [setExplosion(int value)](#setExplosion-int-) | Especifica a quantidade que o ponto de dados deve ser movido do centro do gráfico de pizza. |
| [getFormat()](#getFormat--) | Representa as propriedades de formatação. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa as propriedades de formatação. |
| [getMarker()](#getMarker--) | Especifica um marcador de dados. |
| [remove()](#remove--) | Remove DataPoint da série de gráfico. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e no estilo do gráfico. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Propriedades da entrada de legenda correspondente no caso de tipo de gráfico desta lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Define o ponto de dados como total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Define o ponto de dados como total. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que o ponto de dados deve inverter suas cores se o valor for negativo. |
| [getDataPointLevels()](#getDataPointLevels--) | Retorna o contêiner de níveis do ponto de dados. |
| [getIndex()](#getIndex--) | Determina a qual coleção de filhos do pai este ponto de dados se aplica. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

Obtém o valor x de um ponto de dados de gráfico. Somente leitura [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Retorna:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

Obtém o valor y de um ponto de dados de gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

Obtém o tamanho da bolha de um ponto de dados de gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

Obtém o valor de um ponto de dados de gráfico. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

Obtém o valor X em cache de um ponto de dados de gráfico. Somente leitura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprima todos os valores X em cache da série do gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

Obtém o valor Y em cache de um ponto de dados de gráfico. Somente leitura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprima todos os valores Y em cache da série do gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Obtém o valor em cache de um ponto de dados de gráfico. Somente leitura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprima todos os valores em cache da série do gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

Obtém o tamanho da bolha em cache de um ponto de dados de gráfico. Somente leitura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // Imprima todos os valores de tamanho da bolha em cache da série do gráfico.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

Obtém o valor de tamanho de um ponto de dados de gráfico. Usado com gráficos Treemap e Sunburst. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

Obtém o valor de cor de um ponto de dados de gráfico. Usado com gráficos de mapa. Somente leitura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Retorna:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

Representa valores de barras de erro da série no caso de tipo de valor Custom. Somente leitura [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Retorna:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

Representa o rótulo do ponto de dados de gráfico. Somente leitura [IDataLabel](../../com.aspose.slides/idatalabel).

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

**Parâmetro:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Especifica a quantidade que o ponto de dados deve ser movido do centro do gráfico de pizza. Leitura/gravação int.

**Retorna:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Especifica a quantidade que o ponto de dados deve ser movido do centro do gráfico de pizza. Leitura/gravação int.

**Parâmetro:**
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

**Parâmetro:**
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

Remove DataPoint da série de gráfico.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

Retorna uma cor automática do ponto de dados baseada no índice da série, índice do ponto de dados, propriedade ParentSeriesGroup.IsColorVaried e no estilo do gráfico. Esta cor é usada por padrão se FillType for igual a NotDefined.

**Retorna:**
java.awt.Color - Cor automática do ponto de dados java.awt.Color
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

Define o ponto de dados como total. Aplicado apenas ao tipo de série Waterfall.

**Retorna:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

Define o ponto de dados como total. Aplicado apenas ao tipo de série Waterfall.

**Parâmetro:**
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

**Parâmetro:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

Retorna o contêiner de níveis do ponto de dados. Aplicado para séries Treeamp e Sunburst. A indexação dos níveis do ponto de dados começa em zero.

**Retorna:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

Determina a qual coleção de filhos do pai este ponto de dados se aplica. Leitura long.

**Retorna:**
long