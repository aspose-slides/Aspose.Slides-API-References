---
title: ChartSeries
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma série de gráfico.
type: docs
url: /pt/com.aspose.slides/chartseries/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Representa uma série de chart.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retorna o chart pai. |
| [getExplosion()](#getExplosion--) | A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. |
| [setExplosion(int value)](#setExplosion-int-) | A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. |
| [getSmooth()](#getSmooth--) | Representa a suavização de curva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representa a suavização de curva. |
| [getName()](#getName--) | Retorna o nome da série. |
| [getDataPoints()](#getDataPoints--) | Retorna a coleção de pontos de dados desta série. |
| [getType()](#getType--) | Retorna um tipo desta série. |
| [setType(int value)](#setType-int-) | Retorna um tipo desta série. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se esta série é plotada no eixo secundário. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica se esta série é plotada no eixo secundário. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Retorna o formato de uma série. |
| [getOrder()](#getOrder--) | Retorna a ordem de uma série. |
| [setOrder(int value)](#setOrder-int-) | Retorna a ordem de uma série. |
| [getLabels()](#getLabels--) | Retorna os Labels de uma série. |
| [getTrendLines()](#getTrendLines--) | Coleção de linhas de tendência de séries. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representa ErrorBars de séries com direção X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representa ErrorBars de séries com direção Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa a entrada da legenda relacionada a esta série Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Especifica a forma de uma série de um gráfico de barras 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Especifica a forma de uma série de um gráfico de barras 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Especifica inversão da cor sólida para a série. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retorna uma cor automática da série baseada no índice da série e no estilo do gráfico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representa pontos internos. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representa pontos internos. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representa pontos atípicos. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representa pontos atípicos. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representa marcadores de média. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representa marcadores de média. |
| [getShowMeanLine()](#getShowMeanLine--) | Representa linha de média. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representa linha de média. |
| [getQuartileMethod()](#getQuartileMethod--) | Representa método de quartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representa método de quartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representa linhas de conexão. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representa linhas de conexão. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representa o layout dos rótulos de categoria pai. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representa o layout dos rótulos de categoria pai. |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se o gráfico de Linha ou Stock tem barras de alta/baixa. |
| [getGapWidth()](#getGapWidth--) | Especifica o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. |
| [getGapDepth()](#getGapDepth--) | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Especifica o ângulo da primeira fatia de pizza ou rosca, em graus (horário a partir de cima, de 0 a 360 graus). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica o tamanho do furo em um gráfico de rosca (pode ser entre 10% e 90% do tamanho da área do gráfico). |
| [getOverlap()](#getOverlap--) | Especifica quanto as barras e colunas se sobrepõem em gráficos 2-D, como porcentagem (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica o tamanho da segunda pizza ou barra de um gráfico pizza-de-pizza ou barra-de-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Determina se há linhas de série para esta série e séries afins. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica como os valores de tamanho de bolha são representados no gráfico de bolhas. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | A informação de divisão personalizada para um gráfico pizza-de-pizza ou barra-de-pizza com divisão personalizada. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0% e 300% do tamanho padrão). |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o chart pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. Leitura/gravação int.

**Retorna:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Representa a suavização de curva. Verdadeiro se a suavização de curva estiver ativada para o gráfico de linha ou de dispersão. Aplica-se apenas a gráficos de linha e dispersão conectados por linhas. Leitura/gravação boolean.

**Retorna:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Representa a suavização de curva. Verdadeiro se a suavização de curva estiver ativada para o gráfico de linha ou de dispersão. Aplica-se apenas a gráficos de linha e dispersão conectados por linhas. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Retorna o nome da série. Somente leitura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retorna:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Retorna a coleção de pontos de dados desta série. Somente leitura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retorna:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Retorna um tipo desta série. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Retorna:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Retorna um tipo desta série. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica se esta série é plotada no eixo secundário. Leitura/gravação boolean.

**Retorna:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Indica se esta série é plotada no eixo secundário. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Somente leitura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Retorna:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Retorna o formato de uma série. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

Retorna a ordem de uma série. Leitura/gravação int.

**Retorna:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Retorna a ordem de uma série. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Retorna os Labels de uma série. Somente leitura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Retorna:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Coleção de linhas de tendência de séries. Somente leitura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines estão disponíveis (não nulos) para séries de dados em gráficos de área, barra, coluna, linha, stock, xy (dispersão) e bolhas 2-D não empilhados. Uma linha de tendência não está disponível para séries de dados em qualquer tipo de gráfico que seja empilhado ou 3-D. TrendLines também não estão disponíveis para gráficos de radar, pizza, superfície ou rosca.

**Retorna:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Representa ErrorBars de séries com direção X. Somente leitura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars com direção X estão disponíveis para séries dos tipos área, barra, dispersão e bolha. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retorna:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Representa ErrorBars de séries com direção Y. Somente leitura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars com direção Y estão disponíveis para séries dos tipos área, barra, linha, dispersão e bolha. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retorna:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representa a entrada da legenda relacionada a esta série Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Leitura/gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Leitura/gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Leitura/gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Leitura/gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Somente leitura [IMarker](../../com.aspose.slides/imarker).

**Retorna:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Especifica a forma de uma série de um gráfico de barras 3-D. Alterar o valor desta propriedade pode causar a mudança automática do Tipo da série. Leitura/gravação [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retorna:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Especifica a forma de uma série de um gráfico de barras 3-D. Alterar o valor desta propriedade pode causar a mudança automática do Tipo da série. Leitura/gravação [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. Leitura/gravação boolean.

**Retorna:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Especifica inversão da cor sólida para a série. Para aplicar a configuração de cor defina o FillType da série como FillType.Solid. Leitura/gravação [ColorFormat](../../com.aspose.slides/colorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Retorna uma cor automática da série baseada no índice da série e no estilo do gráfico. Esta cor é usada por padrão se FillType for NotDefined.

**Retorna:**
java.lang.Integer - O objeto java.lang.Integer.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Representa pontos internos. Verdadeiro se pontos internos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Retorna:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Representa pontos internos. Verdadeiro se pontos internos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Representa pontos atípicos. Verdadeiro se pontos atípicos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Retorna:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Representa pontos atípicos. Verdadeiro se pontos atípicos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Representa marcadores de média. Verdadeiro se marcadores de média forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Retorna:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Representa marcadores de média. Verdadeiro se marcadores de média forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Representa linha de média. Verdadeiro se linha de média for mostrada no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Retorna:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Representa linha de média. Verdadeiro se linha de média for mostrada no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Representa método de quartil. Aplica-se apenas a gráficos BoxAndWhisker.

**Retorna:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Representa método de quartil. Aplica-se apenas a gráficos BoxAndWhisker.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Representa linhas de conexão. Aplica-se apenas a gráficos Waterfall.

**Retorna:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Representa linhas de conexão. Aplica-se apenas a gráficos Waterfall.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Representa layout dos rótulos de categoria pai. Aplica-se apenas a gráficos Treemap.

**Retorna:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Representa layout dos rótulos de categoria pai. Aplica-se apenas a gráficos Treemap.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Determina se o gráfico de Linha ou Stock tem barras de alta/baixa. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.UpDownBars.HasUpDownBars leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.UpDownBars para formatar barras de alta/baixa. Somente leitura boolean.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retorna:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Especifica o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.GapWidth leitura/gravação para alterar o valor. Somente leitura int.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.GapWidth.

**Retorna:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.GapDepth leitura/gravação para alterar o valor. Somente leitura int.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.GapDepth.

**Retorna:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Especifica o ângulo da primeira fatia de pizza ou rosca, em graus (horário a partir de cima, de 0 a 360 graus). Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.FirstSliceAngle leitura/gravação para alterar o valor. Somente leitura int.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.FirstSliceAngle.

**Retorna:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Especifica o tamanho do furo em um gráfico de rosca (pode ser entre 10% e 90% do tamanho da área do gráfico). Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.DoughnutHoleSize leitura/gravação para alterar o valor. Somente leitura byte.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.DoughnutHoleSize.

**Retorna:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Especifica quanto as barras e colunas se sobrepõem em gráficos 2-D, como porcentagem (de -100% a 100%). Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai. É a projeção da propriedade apropriada no grupo de séries pai, portanto esta propriedade é Somente leitura. Para alterar o valor, use a propriedade ParentSeriesGroup.Overlap leitura/gravação. Somente leitura byte.

--------------------

Overlap especifica o grau de sobreposição ou espaçamento entre barras e colunas como porcentagem de sua largura:
- -100%: Espaçamento máximo (barras completamente separadas).
- 0%: Barras colocadas lado a lado sem sobreposição ou espaçamento.
- 100%: Sobreposição máxima (barras completamente sobrepostas). Esta é a projeção da propriedade ParentSeriesGroup.Overlap.

**Retorna:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Especifica o tamanho da segunda pizza ou barra de um gráfico pizza-de-pizza ou barra-de-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.SecondPieSize leitura/gravação para alterar o valor. Somente leitura int.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.SecondPieSize.

**Retorna:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Determina se há linhas de série para esta série e séries afins. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.HasSeriesLines leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.SeriesLinesFormat para formatar linhas de série. Somente leitura boolean.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.HasSeriesLines.

**Retorna:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Especifica como os valores de tamanho de bolha são representados no gráfico de bolhas. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.BubbleSizeRepresentation leitura/gravação para alterar o valor.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.BubbleSizeRepresentation.

**Retorna:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Especifica um valor que deve ser usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. É usado em conjunto com a propriedade PieSplitBy. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.PieSplitPosition leitura/gravação para alterar o valor. Somente leitura double.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.PieSplitPosition.

**Retorna:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.PieSplitBy leitura/gravação para alterar o valor. Somente leitura [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Esta é a projeção da propriedade ParentSeriesGroup.PieSplitBy. 2) Se o valor da propriedade for PieSplitType.Custom, então você pode definir informações de divisão personalizada com a propriedade ParentSeriesGroup.PieSplitCustomPoints.

**Retorna:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

A informação de divisão personalizada para um gráfico pizza-de-pizza ou barra-de-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo Somente leitura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.PieSplitCustomPoints.

**Retorna:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Especifica que cada marcador de dados na série tem uma cor diferente. Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.IsColorVaried leitura/gravação para alterar o valor. Somente leitura boolean.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.IsColorVaried.

**Retorna:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0% e 300% do tamanho padrão). Esta é a propriedade não apenas desta série mas de todas as séries do grupo de séries pai – é a projeção da propriedade apropriada do grupo. Portanto esta propriedade é Somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.BubbleSizeScale leitura/gravação para alterar o valor.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.BubbleSizeScale.

**Retorna:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um FillFormat. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um FillFormat. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)