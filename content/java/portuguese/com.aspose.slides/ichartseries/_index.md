---
title: IChartSeries
second_title: Referência da API Aspose.Slides para Java
description: Representa uma série de gráfico.
type: docs
url: /pt/com.aspose.slides/ichartseries/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Representa uma série de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getExplosion()](#getExplosion--) | A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. |
| [setExplosion(int value)](#setExplosion-int-) | A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. |
| [getSmooth()](#getSmooth--) | Representa alisamento de curva. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Representa alisamento de curva. |
| [getMarker()](#getMarker--) | Retorna o marcador da série. |
| [getBar3DShape()](#getBar3DShape--) | Especifica a forma de uma série de um gráfico de barra 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Especifica a forma de uma série de um gráfico de barra 3-D. |
| [getName()](#getName--) | Retorna o nome da série. |
| [getDataPoints()](#getDataPoints--) | Retorna a coleção de pontos de dados desta série. |
| [getType()](#getType--) | Retorna um tipo desta série. |
| [setType(int value)](#setType-int-) | Retorna um tipo desta série. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Retorna o grupo de séries pai. |
| [getFormat()](#getFormat--) | Retorna o formato de uma série. |
| [getOrder()](#getOrder--) | Retorna a ordem de uma série. |
| [setOrder(int value)](#setOrder-int-) | Retorna a ordem de uma série. |
| [getLabels()](#getLabels--) | Retorna os Rótulos de uma série. |
| [getTrendLines()](#getTrendLines--) | Coleção de linhas de tendência da série Somente leitura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Representa Barras de Erro da série com direção X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Representa Barras de Erro da série com direção Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se esta série é plotada no segundo eixo de valores. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Indica se esta série é plotada no segundo eixo de valores. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Retorna ou define o formato numérico para valores da série. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Retorna ou define o formato numérico para valores da série. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Retorna ou define o formato numérico para valores x da série. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Retorna ou define o formato numérico para valores x da série. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Retorna ou define o formato numérico para valores y da série. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Retorna ou define o formato numérico para valores y da série. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Retorna ou define o formato numérico para tamanhos de bolhas da série. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Retorna ou define o formato numérico para tamanhos de bolhas da série. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Especifica cor sólida invertida para a série. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa entrada da legenda relacionada a esta série Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Retorna uma cor automática da série baseada no índice da série e no estilo do gráfico. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Representa pontos internos. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Representa pontos internos. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Representa pontos atípicos. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Representa pontos atípicos. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Representa marcadores de média. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Representa marcadores de média. |
| [getShowMeanLine()](#getShowMeanLine--) | Representa marcadores de média. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Representa marcadores de média. |
| [getQuartileMethod()](#getQuartileMethod--) | Representa método de quartil. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Representa método de quartil. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Representa linhas de conexão. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Representa linhas de conexão. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Representa layout dos rótulos da categoria pai. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Representa layout dos rótulos da categoria pai. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). |
| [hasUpDownBars()](#hasUpDownBars--) | Determina se o gráfico de Linha ou de Ações tem barras altas/baixas. |
| [getGapWidth()](#getGapWidth--) | Especifica o espaço entre grupos de barras ou colunas, como uma porcentagem da largura da barra ou coluna. |
| [getGapDepth()](#getGapDepth--) | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Determina se há linhas de série para esta série e séries afins. |
| [getOverlap()](#getOverlap--) | Especifica o quanto as barras e colunas se sobrepõem em gráficos 2-D, como porcentagem (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica o tamanho da segunda pizza ou barra de um gráfico pizza-de-pizza ou barra-de-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico pizza-de-pizza ou barra-de-pizza. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10% e 90% do tamanho da área de plotagem). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Especifica o ângulo da primeira fatia do gráfico de pizza ou rosca, em graus (horário a partir de cima, de 0 a 360 graus). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | A informação de divisão personalizada para um gráfico pizza-de-pizza ou barra-de-pizza com divisão personalizada. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica como os valores de tamanho de bolha são representados no gráfico de bolhas. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. Leitura/Gravação int.

**Retorna:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

A distância de uma fatia de pizza aberta do centro do gráfico de pizza é expressa como uma porcentagem do diâmetro da pizza. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Representa alisamento de curva. True se o alisamento de curva estiver ativado para o gráfico de linhas ou de dispersão. Aplica-se apenas a gráficos de linha e dispersão conectados por linhas. Leitura/Gravação boolean.

**Retorna:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Representa alisamento de curva. True se o alisamento de curva estiver ativado para o gráfico de linhas ou de dispersão. Aplica-se apenas a gráficos de linha e dispersão conectados por linhas. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Retorna o marcador da série. Somente leitura [IMarker](../../com.aspose.slides/imarker).

**Retorna:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Especifica a forma de uma série de um gráfico de barra 3-D. Alterar o valor desta propriedade pode causar a mudança automática do Tipo da série. Leitura/Gravação [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Retorna:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Especifica a forma de uma série de um gráfico de barra 3-D. Alterar o valor desta propriedade pode causar a mudança automática do Tipo da série. Leitura/Gravação [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Retorna o nome da série. Somente leitura [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Retorna:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Retorna a coleção de pontos de dados desta série. Somente leitura [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Retorna:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Retorna um tipo desta série. Leitura/Gravação [ChartType](../../com.aspose.slides/charttype).

**Retorna:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Retorna um tipo desta série. Leitura/Gravação [ChartType](../../com.aspose.slides/charttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Retorna o grupo de séries pai. Somente leitura [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Retorna:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retorna o formato de uma série. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Retorna a ordem de uma série. Leitura/Gravação int.

**Retorna:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Retorna a ordem de uma série. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Retorna os Rótulos de uma série. Somente leitura [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Retorna:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Coleção de linhas de tendência da série Somente leitura [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Retorna:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Representa Barras de Erro da série com direção X. Somente leitura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars com direção X estão disponíveis para séries dos tipos área, barra, dispersão e bolha. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retorna:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Representa Barras de Erro da série com direção Y. Somente leitura [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars com direção Y estão disponíveis para séries dos tipos área, barra, linha, dispersão e bolha. Para quaisquer outros tipos de gráfico esta propriedade retorna null (incluindo gráficos 3D). No caso de valores personalizados use a coleção DataPoints para especificar o valor (com a propriedade ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Retorna:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica se esta série é plotada no segundo eixo de valores. Leitura/Gravação boolean.

**Retorna:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Indica se esta série é plotada no segundo eixo de valores. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Retorna ou define o formato numérico para valores da série. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Retorna ou define o formato numérico para valores da série. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Retorna ou define o formato numérico para valores x da série. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Retorna ou define o formato numérico para valores x da série. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Retorna ou define o formato numérico para valores y da série. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Retorna ou define o formato numérico para valores y da série. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Retorna ou define o formato numérico para tamanhos de bolhas da série. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Retorna ou define o formato numérico para tamanhos de bolhas da série. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. Leitura/Gravação boolean.

**Retorna:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Especifica que a série de barra, coluna ou bolha deve inverter suas cores se o valor for negativo. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Especifica cor sólida invertida para a série. Para aplicar a cor, defina FillType do formato da série para FillType.Solid. Leitura/Gravação [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representa entrada da legenda relacionada a esta série Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Retorna uma cor automática da série com base no índice da série e no estilo do gráfico. Esta cor é usada por padrão se FillType for igual a NotDefined.

**Retorna:**
java.awt.Color - Cor automática da série java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Representa pontos internos. Verdadeiro se os pontos internos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Retorna:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Representa pontos internos. Verdadeiro se os pontos internos forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Representa pontos outlier. Verdadeiro se os pontos outlier forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Retorna:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Representa pontos outlier. Verdadeiro se os pontos outlier forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Representa marcadores de média. Verdadeiro se os marcadores de média forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Retorna:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Representa marcadores de média. Verdadeiro se os marcadores de média forem mostrados no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Representa marcadores de média. Verdadeiro se a linha de média for mostrada no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Retorna:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Representa marcadores de média. Verdadeiro se a linha de média for mostrada no gráfico BoxAndWhisker. Aplica-se apenas a gráficos BoxAndWhisker. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Representa o método de quartil. Aplica-se apenas a gráficos BoxAndWhisker.

**Retorna:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Representa o método de quartil. Aplica-se apenas a gráficos BoxAndWhisker.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Representa linhas de conexão. Aplica-se apenas a gráficos Waterfall.

**Retorna:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Representa linhas de conexão. Aplica-se apenas a gráficos Waterfall.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Representa o layout dos rótulos de categorias pai. Aplica-se apenas a gráficos Treemap.

**Retorna:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Representa o layout dos rótulos de categorias pai. Aplica-se apenas a gráficos Treemap.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Especifica o fator de escala para o gráfico de bolhas (pode estar entre 0 e 300 por cento do tamanho padrão). Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.BubbleSizeScale leitura/gravação para alterar o valor.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.BubbleSizeScale.

**Retorna:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Determina se o gráfico Line ou Stock possui barras de alta/baixa. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.UpDownBars.HasUpDownBars leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.UpDownBars para formatar as barras de alta/baixa. Booleano somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Retorna:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Especifica o espaço entre grupos de barras ou colunas, como porcentagem da largura da barra ou coluna. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.GapWidth leitura/gravação para alterar o valor. Inteiro somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.GapWidth.

**Retorna:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.GapDepth leitura/gravação para alterar o valor. Inteiro somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.GapDepth.

**Retorna:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Especifica que cada marcador de dados na série tem uma cor diferente. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.IsColorVaried leitura/gravação para alterar o valor. Booleano somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.IsColorVaried.

**Retorna:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Determina se há linhas de série para esta série e séries afins. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.HasSeriesLines leitura/gravação para alterar o valor. Use a propriedade ParentSeriesGroup.SeriesLinesFormat para formatar as linhas de série. Booleano somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.HasSeriesLines.

**Retorna:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Especifica quanto as barras e colunas se sobrepõem em gráficos 2-D, como porcentagem (de -100 % a 100 %). Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai. É uma projeção da propriedade apropriada no grupo de séries pai, e portanto esta propriedade é somente leitura. Para alterar o valor, use a propriedade ParentSeriesGroup.Overlap leitura/gravação. Byte somente leitura.

--------------------

Sobreposição especifica o grau de sobreposição ou espaçamento entre barras e colunas como porcentagem da sua largura: -100 %: espaçamento máximo (barras totalmente separadas). 0 %: barras posicionadas lado a lado sem sobreposição ou espaçamento. 100 %: sobreposição máxima (barras totalmente sobrepostas). Esta é uma projeção da propriedade ParentSeriesGroup.Overlap.

**Retorna:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Especifica o tamanho da segunda fatia ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como porcentagem do tamanho da primeira pizza (pode estar entre 5 e 200 por cento). Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.SecondPieSize leitura/gravação para alterar o valor. Inteiro somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.SecondPieSize.

**Retorna:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Especifica um valor que será usado para determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. É usado juntamente com a propriedade PieSplitBy. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.PieSplitPosition leitura/gravação para alterar o valor. Double somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.PieSplitPosition.

**Retorna:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Especifica como determinar quais pontos de dados estão na segunda pizza ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.PieSplitBy leitura/gravação para alterar o valor. [PieSplitType](../../com.aspose.slides/piesplittype) somente leitura.

--------------------

1) Esta é a projeção da propriedade ParentSeriesGroup.PieSplitBy. 2) Se o valor da propriedade for PieSplitType.Custom, então você pode definir informações de divisão personalizada com a propriedade ParentSeriesGroup.PieSplitCustomPoints.

**Retorna:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Especifica o tamanho do buraco em um gráfico de rosca (pode estar entre 10 e 90 por cento do tamanho da área de plotagem). Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.DoughnutHoleSize leitura/gravação para alterar o valor. Byte somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.DoughnutHoleSize.

**Retorna:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Especifica o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.FirstSliceAngle leitura/gravação para alterar o valor. Inteiro somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.FirstSliceAngle.

**Retorna:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

As informações de divisão personalizada para um gráfico de pizza-de-pizza ou barra-de-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda pizza ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. Esta não é apenas a propriedade desta série, mas de todas as séries do grupo de séries pai – esta é a projeção da propriedade de grupo apropriada. [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection) somente leitura.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.PieSplitCustomPoints.

**Retorna:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Esta é a propriedade não apenas desta série, mas de todas as séries do grupo de séries pai - esta é a projeção da propriedade de grupo apropriada. Portanto, esta propriedade é somente leitura. Use a propriedade ParentSeriesGroup para acessar o grupo de séries pai. Use a propriedade ParentSeriesGroup.BubbleSizeRepresentation leitura/gravação para alterar o valor.

--------------------

Esta é a projeção da propriedade ParentSeriesGroup.BubbleSizeRepresentation.

**Retorna:**
int