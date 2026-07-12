---
title: Axis
second_title: Referência da API Java do Aspose.Slides para Android
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
url: /pt/com.aspose.slides/axis/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsula o objeto que representa o eixo de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representa se o eixo de valores cruza o eixo de categorias entre as categorias. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representa se o eixo de valores cruza o eixo de categorias entre as categorias. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Especifica o tipo do eixo de categorias. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Especifica o tipo do eixo de categorias. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |
| [getCrossAt()](#getCrossAt--) | Representa o ponto no eixo onde o eixo perpendicular o cruza. |
| [setCrossAt(float value)](#setCrossAt-float-) | Representa o ponto no eixo onde o eixo perpendicular o cruza. |
| [getDisplayUnit()](#getDisplayUnit--) | Especifica o valor de escala das unidades de exibição para o eixo de valores. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Especifica o valor de escala das unidades de exibição para o eixo de valores. |
| [getActualMaxValue()](#getActualMaxValue--) | Especifica o valor máximo real no eixo. |
| [getActualMinValue()](#getActualMinValue--) | Especifica o valor mínimo real no eixo. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Especifica a unidade principal real do eixo. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Especifica a unidade secundária real do eixo. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Especifica a escala da unidade principal real do eixo. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Especifica a escala da unidade secundária real do eixo. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indica se o valor máximo é atribuído automaticamente. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indica se o valor máximo é atribuído automaticamente. |
| [getMaxValue()](#getMaxValue--) | Representa o valor máximo no eixo de valores. |
| [setMaxValue(double value)](#setMaxValue-double-) | Representa o valor máximo no eixo de valores. |
| [getMinorUnit()](#getMinorUnit--) | Representa as unidades secundárias para o eixo de data ou de valores. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representa as unidades secundárias para o eixo de data ou de valores. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica se a unidade secundária do eixo é atribuída automaticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica se a unidade secundária do eixo é atribuída automaticamente. |
| [getMajorUnit()](#getMajorUnit--) | Representa as unidades principais para o eixo de data ou de valores. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representa as unidades principais para o eixo de data ou de valores. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indica se a unidade principal do eixo é atribuída automaticamente. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indica se a unidade principal do eixo é atribuída automaticamente. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indica se o valor mínimo é atribuído automaticamente. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indica se o valor mínimo é atribuído automaticamente. |
| [getMinValue()](#getMinValue--) | Representa o valor mínimo no eixo de valores. |
| [setMinValue(double value)](#setMinValue-double-) | Representa o valor mínimo no eixo de valores. |
| [isLogarithmic()](#isLogarithmic--) | Representa se o tipo de escala do eixo de valores é logarítmico ou não. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Representa se o tipo de escala do eixo de valores é logarítmico ou não. |
| [getLogBase()](#getLogBase--) | Representa a base logarítmica. |
| [setLogBase(double value)](#setLogBase-double-) | Representa a base logarítmica. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representa se o MS PowerPoint plota os pontos de dados do último ao primeiro. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representa se o MS PowerPoint plota os pontos de dados do último ao primeiro. |
| [isVisible()](#isVisible--) | Representa se o eixo está visível. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representa se o eixo está visível. |
| [getMajorTickMark()](#getMajorTickMark--) | Representa o tipo de marcação principal para o eixo especificado. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representa o tipo de marcação principal para o eixo especificado. |
| [getMinorTickMark()](#getMinorTickMark--) | Representa o tipo de marcação secundária para o eixo especificado. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representa o tipo de marcação secundária para o eixo especificado. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representa a posição dos rótulos de marcação no eixo especificado. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representa a posição dos rótulos de marcação no eixo especificado. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representa a escala da unidade principal para o eixo de data. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representa a escala da unidade principal para o eixo de data. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representa a escala da unidade principal para o eixo de data. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representa a escala da unidade principal para o eixo de data. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Especifica a menor unidade de tempo representada no eixo de data. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Especifica a menor unidade de tempo representada no eixo de data. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representa o formato das linhas de grade secundárias em um eixo de gráfico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representa o formato das linhas de grade principais em um eixo de gráfico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Para ocultar a linha de grade secundária, defina MinorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Para ocultar a linha de grade principal, defina MajorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. |
| [getFormat()](#getFormat--) | Representa o formato do eixo. |
| [getTextFormat()](#getTextFormat--) | Representa o formato do texto. |
| [getTitle()](#getTitle--) | Obtém o título do eixo. |
| [getCrossType()](#getCrossType--) | Representa o CrossType no eixo especificado onde o outro eixo o cruza. |
| [setCrossType(int value)](#setCrossType-int-) | Representa o CrossType no eixo especificado onde o outro eixo o cruza. |
| [getPosition()](#getPosition--) | Representa a posição do eixo. |
| [setPosition(int value)](#setPosition-int-) | Representa a posição do eixo. |
| [hasTitle()](#hasTitle--) | Determina se um eixo tem um título visível. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se um eixo tem um título visível. |
| [getNumberFormat()](#getNumberFormat--) | Representa a string de formato para os rótulos do eixo. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa a string de formato para os rótulos do eixo. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indica se o formato está vinculado aos dados de origem. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indica se o formato está vinculado aos dados de origem. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representa o ângulo de rotação dos rótulos das marcações. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representa o ângulo de rotação dos rótulos das marcações. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Especifica o valor de espaçamento automático das marcas de escala. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Especifica o valor de espaçamento automático das marcas de escala. |
| [getLabelOffset()](#getLabelOffset--) | Especifica a distância dos rótulos ao eixo. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Especifica a distância dos rótulos ao eixo. |
| [getAggregationType()](#getAggregationType--) | Representa o tipo de agregação do eixo de categorias (agrupamento). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representa o tipo de agregação do eixo de categorias (agrupamento). |
| [getBinWidth()](#getBinWidth--) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Especifica se o bin de transbordamento é aplicado. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Especifica se o bin de transbordamento é aplicado. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Especifica o valor automático do bin de transbordamento. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Especifica o valor automático do bin de transbordamento. |
| [getOverflowBin()](#getOverflowBin--) | Especifica o valor personalizado do bin de transbordamento. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Especifica o valor personalizado do bin de transbordamento. |
| [isUnderflowBin()](#isUnderflowBin--) | Especifica se o bin de subfluxo é aplicado. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Especifica se o bin de subfluxo é aplicado. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Especifica o valor automático do bin de subfluxo. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Especifica o valor automático do bin de subfluxo. |
| [getUnderflowBin()](#getUnderflowBin--) | Especifica o valor personalizado do bin de subfluxo. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Especifica o valor personalizado do bin de subfluxo. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Representa se o eixo de valores cruza o eixo de categorias entre as categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Representa se o eixo de valores cruza o eixo de categorias entre as categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Especifica o tipo do eixo de categorias. Leitura/Gravação [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Retorna:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Especifica o tipo do eixo de categorias. Leitura/Gravação [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/Gravação float.

**Retorna:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Leitura/Gravação [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retorna:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Leitura/Gravação [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorna:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indica se o valor máximo é atribuído automaticamente. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indica se o valor máximo é atribuído automaticamente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Representa o valor máximo no eixo de valores. Leitura/Gravação double.

**Retorna:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Representa o valor máximo no eixo de valores. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Representa as unidades secundárias para o eixo de data ou de valores. Leitura/Gravação double.

**Retorna:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Representa as unidades secundárias para o eixo de data ou de valores. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Representa as unidades principais para o eixo de data ou de valores. Leitura/Gravação double.

**Retorna:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Representa as unidades principais para o eixo de data ou de valores. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Indica se o valor mínimo é atribuído automaticamente. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Indica se o valor mínimo é atribuído automaticamente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Representa o valor mínimo no eixo de valores. Leitura/Gravação double.

**Retorna:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Representa o valor mínimo no eixo de valores. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Leitura/Gravação boolean.

**Retorna:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Representa a base logarítmica. Valor padrão é 10. Leitura/Gravação double.

**Retorna:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Representa a base logarítmica. Valor padrão é 10. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Representa se o MS PowerPoint plota os pontos de dados do último ao primeiro. Leitura/Gravação boolean.

**Retorna:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Representa se o MS PowerPoint plota os pontos de dados do último ao primeiro. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Representa se o eixo está visível. Leitura/Gravação boolean.

**Retorna:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Representa se o eixo está visível. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Representa o tipo de marcação principal para o eixo especificado. Leitura/Gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorna:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Representa o tipo de marcação principal para o eixo especificado. Leitura/Gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Representa o tipo de marcação secundária para o eixo especificado. Leitura/Gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorna:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Representa o tipo de marcação secundária para o eixo especificado. Leitura/Gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Representa a posição dos rótulos de marcação no eixo especificado. Leitura/Gravação [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retorna:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Representa a posição dos rótulos de marcação no eixo especificado. Leitura/Gravação [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Representa a escala da unidade principal para o eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Especifica a menor unidade de tempo representada no eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Especifica a menor unidade de tempo representada no eixo de data. Leitura/Gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Representa o formato das linhas de grade secundárias em um eixo de gráfico. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Representa o formato das linhas de grade principais em um eixo de gráfico. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Para ocultar a linha de grade secundária, defina MinorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. Somente leitura boolean.

**Retorna:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Para ocultar a linha de grade principal, defina MajorGridLinesFormat.Line.FillFormat.FillType como FillType.NoFill. Somente leitura boolean.

**Retorna:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Representa o formato do eixo. Somente leitura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retorna:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Representa o formato do texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Obtém o título do eixo. Somente leitura [IChartTitle](../../com.aspose.slides/icharttitle).

**Retorna:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Representa o CrossType no eixo especificado onde o outro eixo o cruza. Leitura/Gravação [CrossesType](../../com.aspose.slides/crossestype).

**Retorna:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Representa o CrossType no eixo especificado onde o outro eixo o cruza. Leitura/Gravação [CrossesType](../../com.aspose.slides/crossestype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representa a posição do eixo. Leitura/Gravação [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retorna:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representa a posição do eixo. Leitura/Gravação [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determina se um eixo tem um título visível. Leitura/Gravação boolean.

**Retorna:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determina se um eixo tem um título visível. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representa a string de formato para os rótulos do eixo. Leitura/Gravação String.

**Retorna:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representa a string de formato para os rótulos do eixo. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Indica se o formato está vinculado aos dados de origem. Leitura/Gravação boolean.

**Retorna:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Indica se o formato está vinculado aos dados de origem. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Representa o ângulo de rotação dos rótulos das marcações. Leitura/Gravação float.

**Retorna:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Representa o ângulo de rotação dos rótulos das marcações. Leitura/Gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Aplicado a eixo de categoria ou de série. Leitura/Gravação long.

**Retorna:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Aplicado a eixo de categoria ou de série. Leitura/Gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Especifica o valor de espaçamento automático dos rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Especifica o valor de espaçamento automático dos rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado a eixo de categoria ou de série. Leitura/Gravação int.

**Retorna:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado a eixo de categoria ou de série. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Especifica o valor de espaçamento automático das marcas de escala. Se false: use a propriedade TickMarksSpacing. Leitura/Gravação boolean.

**Retorna:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Especifica o valor de espaçamento automático das marcas de escala. Se false: use a propriedade TickMarksSpacing. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Especifica a distância dos rótulos ao eixo. Aplicado a eixo de categoria ou de data. O valor deve estar entre 0% e 1000%. Leitura/Gravação int.

**Retorna:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Especifica a distância dos rótulos ao eixo. Aplicado a eixo de categoria ou de data. O valor deve estar entre 0% e 1000%. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Representa o tipo de agregação do eixo de categorias (agrupamento). Aplicado a categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Retorna:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Representa o tipo de agregação do eixo de categorias (agrupamento). Aplicado a categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Retorna:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Retorna:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Especifica se o bin de transbordamento é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de transbordamento.

**Retorna:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Especifica se o bin de transbordamento é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de transbordamento.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Especifica o valor automático do bin de transbordamento. Se false: use a propriedade OverflowBin.

**Retorna:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Especifica o valor automático do bin de transbordamento. Se false: use a propriedade OverflowBin.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Especifica o valor personalizado do bin de transbordamento. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin é true.

**Retorna:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Especifica o valor personalizado do bin de transbordamento. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Especifica se o bin de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de subfluxo.

**Retorna:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Especifica se o bin de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de subfluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Especifica o valor automático do bin de subfluxo. Se false: use a propriedade UnderflowBin.

**Retorna:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Especifica o valor automático do bin de subfluxo. Se false: use a propriedade UnderflowBin.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Especifica o valor personalizado do bin de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin é true.

**Retorna:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Especifica o valor personalizado do bin de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

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