---
title: IAxis
second_title: Referência da API Aspose.Slides para Java
description: Encapsula o objeto que representa o eixo de um gráfico.
type: docs
url: /pt/com.aspose.slides/iaxis/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsula o objeto que representa o eixo de um gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representa se o eixo de valores cruza o eixo de categorias entre as categorias. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representa se o eixo de valores cruza o eixo de categorias entre as categorias. |
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
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro. |
| [isVisible()](#isVisible--) | Representa se o eixo está visível. |
| [setVisible(boolean value)](#setVisible-boolean-) | Representa se o eixo está visível. |
| [getMajorTickMark()](#getMajorTickMark--) | Representa o tipo de marca de graduação principal para o eixo especificado. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Representa o tipo de marca de graduação principal para o eixo especificado. |
| [getMinorTickMark()](#getMinorTickMark--) | Representa o tipo de marca de graduação secundária para o eixo especificado. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Representa o tipo de marca de graduação secundária para o eixo especificado. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Representa a posição dos rótulos das marcas de graduação no eixo especificado. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Representa a posição dos rótulos das marcas de graduação no eixo especificado. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Representa a escala da unidade principal para o eixo de datas. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representa a escala da unidade principal para o eixo de datas. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representa a escala da unidade principal para o eixo de datas. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representa a escala da unidade principal para o eixo de datas. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Especifica a menor unidade de tempo representada no eixo de datas. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Especifica a menor unidade de tempo representada no eixo de datas. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representa o formato das linhas de grade secundárias em um eixo de gráfico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representa o formato das linhas de grade principais em um eixo de gráfico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Representa se as linhas de grade secundárias são exibidas. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Representa se as linhas de grade principais são exibidas. |
| [getFormat()](#getFormat--) | Representa o formato do eixo. |
| [getTitle()](#getTitle--) | Obtém o título do eixo. |
| [getCrossType()](#getCrossType--) | Representa o CrossType no eixo especificado onde o outro eixo cruza. |
| [setCrossType(int value)](#setCrossType-int-) | Representa o CrossType no eixo especificado onde o outro eixo cruza. |
| [getPosition()](#getPosition--) | Representa a posição do eixo. |
| [setPosition(int value)](#setPosition-int-) | Representa a posição do eixo. |
| [hasTitle()](#hasTitle--) | Determina se um eixo tem um título visível. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se um eixo tem um título visível. |
| [getNumberFormat()](#getNumberFormat--) | Representa a string de formato para os rótulos do eixo. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa a string de formato para os rótulos do eixo. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indica se o formato está vinculado aos dados de origem. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indica se o formato está vinculado aos dados de origem. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representa o ângulo de rotação dos rótulos das marcas de graduação. Leitura/gravação float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representa o ângulo de rotação dos rótulos das marcas de graduação. Leitura/gravação float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Especifica quantas marcas de graduação devem ser puladas antes que a próxima seja desenhada. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Especifica quantas marcas de graduação devem ser puladas antes que a próxima seja desenhada. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Especifica o valor de espaçamento automático das marcas de graduação. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Especifica o valor de espaçamento automático das marcas de graduação. |
| [getLabelOffset()](#getLabelOffset--) | Especifica a distância dos rótulos ao eixo. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Especifica a distância dos rótulos ao eixo. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Especifica o tipo do eixo de categoria. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Especifica o tipo do eixo de categoria. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |
| [getAggregationType()](#getAggregationType--) | Representa o tipo de agregação do eixo de categoria (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representa o tipo de agregação do eixo de categoria (binning). |
| [getBinWidth()](#getBinWidth--) | Especifica a largura do intervalo quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Especifica a largura do intervalo quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Especifica o número de intervalos quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Especifica o número de intervalos quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Especifica se o intervalo de overflow é aplicado. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Especifica se o intervalo de overflow é aplicado. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Especifica o valor automático do intervalo de overflow. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Especifica o valor automático do intervalo de overflow. |
| [getOverflowBin()](#getOverflowBin--) | Especifica o valor personalizado do intervalo de overflow. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Especifica o valor personalizado do intervalo de overflow. |
| [isUnderflowBin()](#isUnderflowBin--) | Especifica se o intervalo de underflow é aplicado. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Especifica se o intervalo de underflow é aplicado. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Especifica o valor automático do intervalo de underflow. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Especifica o valor automático do intervalo de underflow. |
| [getUnderflowBin()](#getUnderflowBin--) | Especifica o valor personalizado do intervalo de underflow. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Especifica o valor personalizado do intervalo de underflow. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Representa se o eixo de valores cruza o eixo de categorias entre as categorias. Esta propriedade se aplica somente a eixos de categoria e não se aplica a gráficos 3-D. Leitura/gravação boolean.

**Retorna:**
boolean

### setAxisBetweenCategories(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Representa se o eixo de valores cruza o eixo de categorias entre as categorias. Esta propriedade se aplica somente a eixos de categoria e não se aplica a gráficos 3-D. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/gravação float.

**Retorna:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Leitura/gravação [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retorna:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Leitura/gravação [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() previamente para obter o valor real.

**Retorna:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indica se o valor máximo é atribuído automaticamente. Leitura/gravação boolean.

**Retorna:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indica se o valor máximo é atribuído automaticamente. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Representa o valor máximo no eixo de valores. Leitura/gravação double.

**Retorna:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Representa o valor máximo no eixo de valores. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Representa as unidades secundárias para o eixo de data ou de valores. Leitura/gravação double.

**Retorna:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Representa as unidades secundárias para o eixo de data ou de valores. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/gravação boolean.

**Retorna:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Representa as unidades principais para o eixo de data ou de valores. Leitura/gravação double.

**Retorna:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Representa as unidades principais para o eixo de data ou de valores. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/gravação boolean.

**Retorna:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indica se a unidade principal do eixo é atribuída automaticamente. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indica se o valor mínimo é atribuído automaticamente. Leitura/gravação boolean.

**Retorna:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indica se o valor mínimo é atribuído automaticamente. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Representa o valor mínimo no eixo de valores. Leitura/gravação double.

**Retorna:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Representa o valor mínimo no eixo de valores. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Leitura/gravação boolean.

**Retorna:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Representa a base logarítmica. O valor padrão é 10. Leitura/gravação double.

**Retorna:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Representa a base logarítmica. O valor padrão é 10. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Representa se o PowerPoint plota pontos de dados do último para o primeiro. Leitura/gravação boolean.

**Retorna:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Representa se o PowerPoint plota pontos de dados do último para o primeiro. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Representa se o eixo está visível. Leitura/gravação boolean.

**Retorna:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Representa se o eixo está visível. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Representa o tipo de marcação maior para o eixo especificado. Leitura/gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorna:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Representa o tipo de marcação maior para o eixo especificado. Leitura/gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Representa o tipo de marcação menor para o eixo especificado. Leitura/gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorna:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Representa o tipo de marcação menor para o eixo especificado. Leitura/gravação [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Representa a posição dos rótulos das marcas de escala no eixo especificado. Leitura/gravação [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retorna:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Representa a posição dos rótulos das marcas de escala no eixo especificado. Leitura/gravação [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Representa a escala da unidade maior para o eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Representa a escala da unidade maior para o eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Representa a escala da unidade maior para o eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Representa a escala da unidade maior para o eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Especifica a menor unidade de tempo representada no eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorna:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Especifica a menor unidade de tempo representada no eixo de data. Leitura/gravação [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Representa o formato das linhas de grade menores em um eixo de gráfico. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Representa o formato das linhas de grade maiores em um eixo de gráfico. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Representa se as linhas de grade menores são exibidas. Somente leitura boolean.

**Retorna:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Representa se as linhas de grade maiores são exibidas. Somente leitura boolean.

**Retorna:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Representa o formato do eixo. Somente leitura [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retorna:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Obtém o título do eixo. Somente leitura [IChartTitle](../../com.aspose.slides/icharttitle).

**Retorna:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Representa o CrossType no eixo especificado onde o outro eixo cruza. Leitura/gravação [CrossesType](../../com.aspose.slides/crossestype).

**Retorna:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Representa o CrossType no eixo especificado onde o outro eixo cruza. Leitura/gravação [CrossesType](../../com.aspose.slides/crossestype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representa a posição do eixo. Leitura/gravação [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retorna:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representa a posição do eixo. Leitura/gravação [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina se um eixo possui título visível. Leitura/gravação boolean.

**Retorna:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina se um eixo possui título visível. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representa a cadeia de formato para os rótulos do eixo. Leitura/gravação String.

**Retorna:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representa a cadeia de formato para os rótulos do eixo. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indica se o formato está vinculado aos dados de origem. Leitura/gravação boolean.

**Retorna:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indica se o formato está vinculado aos dados de origem. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Representa o ângulo de rotação dos rótulos das marcas. Leitura/gravação float.

**Retorna:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Representa o ângulo de rotação dos rótulos das marcas. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Especifica quantos rótulos de marcação pular entre os que são desenhados. Leitura/gravação long.

**Retorna:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Especifica quantos rótulos de marcação pular entre os que são desenhados. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Especifica o valor automático de espaçamento dos rótulos de marcação. Se false: usa a propriedade TickLabelSpacing. Leitura/gravação boolean.

**Retorna:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Especifica o valor automático de espaçamento dos rótulos de marcação. Se false: usa a propriedade TickLabelSpacing. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado ao eixo de categoria ou série. Leitura/gravação int.

**Retorna:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Especifica quantas marcas de escala devem ser puladas antes da próxima ser desenhada. Aplicado ao eixo de categoria ou série. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Especifica o valor automático de espaçamento das marcas de escala. Se false: usa a propriedade TickMarksSpacing. Leitura/gravação boolean.

**Retorna:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Especifica o valor automático de espaçamento das marcas de escala. Se false: usa a propriedade TickMarksSpacing. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Especifica a distância dos rótulos do eixo. Aplicado ao eixo de categoria ou data. O valor deve estar entre 0 % e 1000 %. Leitura/gravação int.

**Retorna:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Especifica a distância dos rótulos do eixo. Aplicado ao eixo de categoria ou data. O valor deve estar entre 0 % e 1000 %. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Especifica o tipo do eixo de categoria. Leitura/gravação [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Retorna:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Especifica o tipo do eixo de categoria. Leitura/gravação [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado à categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Retorna:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado à categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Especifica a largura do intervalo quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Returns:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Especifica a largura do intervalo quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Especifica o número de intervalos quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Returns:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Especifica o número de intervalos quando o valor da propriedade AggregationType é definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado apenas com séries Histogram ou HistogramPareto.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Especifica se o intervalo de estouro é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do intervalo de estouro.

**Returns:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Especifica se o intervalo de estouro é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do intervalo de estouro.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Especifica o valor automático do intervalo de estouro. Se false: use a propriedade OverflowBin.

**Returns:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Especifica o valor automático do intervalo de estouro. Se false: use a propriedade OverflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Especifica o valor personalizado do intervalo de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e a propriedade IsOverflowBin é true.

**Returns:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Especifica o valor personalizado do intervalo de estouro. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e a propriedade IsOverflowBin é true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Especifica se o intervalo de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do intervalo de subfluxo.

**Returns:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Especifica se o intervalo de subfluxo é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do intervalo de subfluxo.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Especifica o valor automático do intervalo de subfluxo. Se false: use a propriedade UnderflowBin.

**Returns:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Especifica o valor automático do intervalo de subfluxo. Se false: use a propriedade UnderflowBin.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Especifica o valor personalizado do intervalo de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e a propriedade IsUnderflowBin é true.

**Returns:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Especifica o valor personalizado do intervalo de subfluxo. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e a propriedade IsUnderflowBin é true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |