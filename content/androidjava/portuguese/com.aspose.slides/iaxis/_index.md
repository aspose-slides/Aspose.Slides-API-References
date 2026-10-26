---
title: IAxis
second_title: Referência da API Java para Aspose.Slides para Android
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
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Representa se o eixo de valores cruza o eixo de categorias entre categorias. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Representa se o eixo de valores cruza o eixo de categorias entre categorias. |
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
| [getMinorUnit()](#getMinorUnit--) | Representa as unidades secundárias para o eixo de data ou valor. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Representa as unidades secundárias para o eixo de data ou valor. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indica se a unidade secundária do eixo é atribuída automaticamente. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indica se a unidade secundária do eixo é atribuída automaticamente. |
| [getMajorUnit()](#getMajorUnit--) | Representa as unidades principais para o eixo de data ou valor. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Representa as unidades principais para o eixo de data ou valor. |
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
| [getMajorUnitScale()](#getMajorUnitScale--) | Representa a escala da unidade principal para o eixo de data. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Representa a escala da unidade principal para o eixo de data. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Representa a escala da unidade principal para o eixo de data. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Representa a escala da unidade principal para o eixo de data. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Especifica a menor unidade de tempo representada no eixo de data. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Especifica a menor unidade de tempo representada no eixo de data. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Representa o formato das linhas de grade secundárias em um eixo de gráfico. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Representa o formato das linhas de grade principais em um eixo de gráfico. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Representa se as linhas de grade secundárias são exibidas. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Representa se as linhas de grade principais são exibidas. |
| [getFormat()](#getFormat--) | Representa o formato do eixo. |
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
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Representa o ângulo de rotação dos rótulos das marcações. Read/write float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Representa o ângulo de rotação dos rótulos das marcações. Read/write float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Especifica o valor de espaçamento automático dos rótulos de marcação. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Especifica quantas marcas de graduação devem ser puladas antes da próxima ser desenhada. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Especifica quantas marcas de graduação devem ser puladas antes da próxima ser desenhada. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Especifica o valor de espaçamento automático das marcas de graduação. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Especifica o valor de espaçamento automático das marcas de graduação. |
| [getLabelOffset()](#getLabelOffset--) | Especifica a distância dos rótulos ao eixo. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Especifica a distância dos rótulos ao eixo. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Especifica o tipo do eixo de categoria. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Especifica o tipo do eixo de categoria. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Define a propriedade IAxis.CategoryAxisType com um valor determinado automaticamente com base nos dados do eixo. |
| [getAggregationType()](#getAggregationType--) | Representa o tipo de agregação do eixo de categoria (agrupamento). |
| [setAggregationType(int value)](#setAggregationType-int-) | Representa o tipo de agregação do eixo de categoria (agrupamento). |
| [getBinWidth()](#getBinWidth--) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Especifica se o bin de overflow é aplicado. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Especifica se o bin de overflow é aplicado. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Especifica o valor automático do bin de overflow. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Especifica o valor automático do bin de overflow. |
| [getOverflowBin()](#getOverflowBin--) | Especifica o valor customizado do bin de overflow. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Especifica o valor customizado do bin de overflow. |
| [isUnderflowBin()](#isUnderflowBin--) | Especifica se o bin de underflow é aplicado. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Especifica se o bin de underflow é aplicado. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Especifica o valor automático do bin de underflow. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Especifica o valor automático do bin de underflow. |
| [getUnderflowBin()](#getUnderflowBin--) | Especifica o valor customizado do bin de underflow. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Especifica o valor customizado do bin de underflow. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Representa se o eixo de valores cruza o eixo de categorias entre categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Read/write boolean.

**Retorno:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Representa se o eixo de valores cruza o eixo de categorias entre categorias. Esta propriedade se aplica apenas a eixos de categoria e não se aplica a gráficos 3-D. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Read/write float.

**Retorno:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Representa o ponto no eixo onde o eixo perpendicular o cruza. Read/write float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Retorno:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Especifica o valor de escala das unidades de exibição para o eixo de valores. Read/write [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Especifica o valor máximo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Especifica o valor mínimo real no eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Especifica a unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Especifica a unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Especifica a escala da unidade principal real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Especifica a escala da unidade secundária real do eixo. Chame o método IChart.ValidateChartLayout() anteriormente para obter o valor real.

**Retorno:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indica se o valor máximo é atribuído automaticamente. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indica se o valor máximo é atribuído automaticamente. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Representa o valor máximo no eixo de valores. Read/write double.

**Retorno:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Representa o valor máximo no eixo de valores. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Representa as unidades secundárias para o eixo de data ou valor. Read/write double.

**Retorno:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Representa as unidades secundárias para o eixo de data ou valor. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indica se a unidade secundária do eixo é atribuída automaticamente. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Representa as unidades principais para o eixo de data ou valor. Read/write double.

**Retorno:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Representa as unidades principais para o eixo de data ou valor. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indica se a unidade principal do eixo é atribuída automaticamente. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indica se a unidade principal do eixo é atribuída automaticamente. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indica se o valor mínimo é atribuído automaticamente. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indica se o valor mínimo é atribuído automaticamente. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Representa o valor mínimo no eixo de valores. Read/write double.

**Retorno:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Representa o valor mínimo no eixo de valores. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Read/write boolean.

**Retorno:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Representa se o tipo de escala do eixo de valores é logarítmico ou não. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Representa a base logarítmica. O valor padrão é 10. Read/write double.

**Retorno:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Representa a base logarítmica. O valor padrão é 10. Read/write double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro. Read/write boolean.

**Retorno:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Representa se o MS PowerPoint plota os pontos de dados do último para o primeiro. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Representa se o eixo está visível. Read/write boolean.

**Retorno:**  
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Representa se o eixo está visível. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Representa o tipo de marca de graduação principal para o eixo especificado. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorno:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Representa o tipo de marca de graduação principal para o eixo especificado. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Representa o tipo de marca de graduação secundária para o eixo especificado. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Retorno:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Representa o tipo de marca de graduação secundária para o eixo especificado. Read/write [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Representa a posição dos rótulos das marcas de graduação no eixo especificado. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Retorno:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Representa a posição dos rótulos das marcas de graduação no eixo especificado. Read/write [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Representa a escala da unidade principal para o eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorno:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Representa a escala da unidade principal para o eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Representa a escala da unidade principal para o eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorno:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Representa a escala da unidade principal para o eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Especifica a menor unidade de tempo representada no eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Retorno:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Especifica a menor unidade de tempo representada no eixo de data. Read/write [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Representa o formato das linhas de grade secundárias em um eixo de gráfico. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorno:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Representa o formato das linhas de grade principais em um eixo de gráfico. Read-only [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Retorno:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Representa se as linhas de grade secundárias são exibidas. Read-only boolean.

**Retorno:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Representa se as linhas de grade principais são exibidas. Read-only boolean.

**Retorno:**  
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Representa o formato do eixo. Read-only [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Retorno:**  
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Obtém o título do eixo. Read-only [IChartTitle](../../com.aspose.slides/icharttitle).

**Retorno:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Representa o CrossType no eixo especificado onde o outro eixo o cruza. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Retorno:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Representa o CrossType no eixo especificado onde o outro eixo o cruza. Read/write [CrossesType](../../com.aspose.slides/crossestype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representa a posição do eixo. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Retorno:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representa a posição do eixo. Read/write [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina se um eixo tem um título visível. Read/write boolean.

**Retorno:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina se um eixo tem um título visível. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representa a string de formato para os rótulos do eixo. Read/write String.

**Retorno:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representa a string de formato para os rótulos do eixo. Read/write String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indica se o formato está vinculado aos dados de origem. Read/write boolean.

**Retorno:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indica se o formato está vinculado aos dados de origem. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Representa o ângulo de rotação dos rótulos das marcações. Read/write float.

**Retorno:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Representa o ângulo de rotação dos rótulos das marcações. Read/write float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Read/write long.

**Retorno:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public ... etc......



```

Especifica quantos rótulos de marcação pular entre os rótulos que são desenhados. Read/write long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Especifica o valor de espaçamento automático dos rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Especifica o valor de espaçamento automático dos rótulos de marcação. Se false: use a propriedade TickLabelSpacing. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Especifica quantas marcas de graduação devem ser puladas antes da próxima ser desenhada. Aplicado ao eixo de categoria ou série. Read/write int.

**Retorno:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Especifica quantas marcas de graduação devem ser puladas antes da próxima ser desenhada. Aplicado ao eixo de categoria ou série. Read/write int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Especifica o valor de espaçamento automático das marcas de graduação. Se false: use a propriedade TickMarksSpacing. Read/write boolean.

**Retorno:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Especifica o valor de espaçamento automático das marcas de graduação. Se false: use a propriedade TickMarksSpacing. Read/write boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Especifica a distância dos rótulos ao eixo. Aplicado ao eixo de categoria ou data. O valor deve estar entre 0% e 1000%. Read/write int.

**Retorno:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Especifica a distância dos rótulos ao eixo. Aplicado ao eixo de categoria ou data. O valor deve estar entre 0% e 1000%. Read/write int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Especifica o tipo do eixo de categoria. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Retorno:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Especifica o tipo do eixo de categoria. Read/write [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

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

Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categoria. Usado somente com séries Histogram ou HistogramPareto.

**Retorno:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Representa o tipo de agregação do eixo de categoria (agrupamento). Aplicado a categoria. Usado somente com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto.

**Retorno:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Especifica a largura do bin quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByBinWidth. Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto.

**Retorno:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Especifica o número de bins quando o valor da propriedade AggregationType está definido como AxisAggregationType.ByNumberOfBins. Aplicado a eixos de categoria. Usado somente com séries Histogram ou HistogramPareto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Especifica se o bin de overflow é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de overflow.

**Retorno:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Especifica se o bin de overflow é aplicado. Use IsAutomaticOverflowBin e OverflowBin para ajustar o valor do bin de overflow.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Especifica o valor automático do bin de overflow. Se false: use a propriedade OverflowBin.

**Retorno:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Especifica o valor automático do bin de overflow. Se false: use a propriedade OverflowBin.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Especifica o valor customizado do bin de overflow. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin for true.

**Retorno:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Especifica o valor customizado do bin de overflow. Aplicado quando a propriedade IsAutomaticOverflowBin está definida como false e IsOverflowBin for true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Especifica se o bin de underflow é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de underflow.

**Retorno:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Especifica se o bin de underflow é aplicado. Use IsAutomaticUnderflowBin e UnderflowBin para ajustar o valor do bin de underflow.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Especifica o valor automático do bin de underflow. Se false: use a propriedade UnderflowBin.

**Retorno:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Especifica o valor automático do bin de underflow. Se false: use a propriedade UnderflowBin.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Especifica o valor customizado do bin de underflow. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin for true.

**Retorno:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Especifica o valor customizado do bin de underflow. Aplicado quando a propriedade IsAutomaticUnderflowBin está definida como false e IsUnderflowBin for true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |