---
title: ChartSeriesGroup
second_title: Referência da API Aspose.Slides para Java
description: Representa um grupo de séries.
type: docs
url: /pt/com.aspose.slides/chartseriesgroup/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Representa um grupo de séries.

--------------------

1) Consulte o resumo e as observações da classe ChartSeriesGroupCollection e do enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo (“propriedades do grupo de séries”). “Propriedades do grupo de séries” na classe ChartSeriesGroup é leitura/gravação. Cada “propriedades do grupo de séries” pode ter uma projeção somente-leitura na classe ChartSeries.
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna um tipo deste grupo de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se as séries deste grupo são plotadas no eixo secundário. |
| [getSeries()](#getSeries--) | Retorna uma coleção de séries. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getUpDownBars()](#getUpDownBars--) | Fornece acesso às barras de alta/baixa de um gráfico de Linha ou de Ações. |
| [getGapWidth()](#getGapWidth--) | Obtém ou define o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Obtém ou define o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. |
| [getGapDepth()](#getGapDepth--) | Obtém ou define a distância entre séries de dados em um gráfico 3D, como uma porcentagem da largura do marcador. |
| [setGapDepth(int value)](#setGapDepth-int-) | Obtém ou define a distância entre séries de dados em um gráfico 3D, como uma porcentagem da largura do marcador. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtém ou define o ângulo da primeira fatia de um gráfico de pizza ou rosca, em graus (sentido horário a partir de cima, de 0 a 360 graus). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtém ou define o ângulo da primeira fatia de um gráfico de pizza ou rosca, em graus (sentido horário a partir de cima, de 0 a 360 graus). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 0 e 90% do tamanho da área de plotagem). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 0 e 90% do tamanho da área de plotagem). |
| [getOverlap()](#getOverlap--) | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica o tamanho da segunda fatia ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como uma porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Especifica o tamanho da segunda fatia ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como uma porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica como os valores de tamanho das bolhas são representados no gráfico de bolhas. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Especifica como os valores de tamanho das bolhas são representados no gráfico de bolhas. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Especifica um valor que será usado para determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica como determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Especifica como determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Verdadeiro se o gráfico possui linhas de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Verdadeiro se o gráfico possui linhas de série. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Especifica o formato HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | As informações de divisão personalizada para um gráfico de pizza-de-pizza ou barra-de-pizza com divisão personalizada. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Retorna um tipo deste grupo de séries. Somente-leitura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retorna:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Indica se as séries deste grupo são plotadas no eixo secundário. Somente-leitura boolean.

**Retorna:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Retorna uma coleção de séries. Somente-leitura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retorna:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Fornece acesso às barras de alta/baixa de um gráfico de Linha ou de Ações. Somente-leitura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retorna:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Obtém ou define o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. O valor deve estar entre 0 e 500. Leitura/gravação int.

--------------------

Esta propriedade se aplica a séries dos seguintes tipos: subtipos Bar (consulte também o método [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), subtipos Column (consulte também o método [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Retorna:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Define o espaço entre agrupamentos de barra ou coluna, como uma porcentagem da largura da barra ou coluna. O valor deve estar entre 0 e 500. Leitura/gravação int.

--------------------

Esta propriedade se aplica a séries dos seguintes tipos: subtipos Bar (consulte também o método [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), subtipos Column (consulte também o método [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Obtém ou define a distância entre séries de dados em um gráfico 3D, como uma porcentagem da largura do marcador. O valor deve estar entre 0 e 500. Leitura/gravação int.

--------------------

Esta propriedade se aplica a séries dos seguintes tipos: subtipos de barra e coluna 3D (consulte também o método [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Retorna:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Define a distância entre séries de dados em um gráfico 3D, como uma porcentagem da largura do marcador. O valor deve estar entre 0 e 500. Leitura/gravação int.

--------------------

Esta propriedade se aplica a séries dos seguintes tipos: subtipos de barra e coluna 3D (consulte também o método [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Obtém ou define o ângulo da primeira fatia de um gráfico de pizza ou rosca, em graus (sentido horário a partir de cima, de 0 a 360 graus). Leitura/gravação int.

**Retorna:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Define o ângulo da primeira fatia de um gráfico de pizza ou rosca, em graus (sentido horário a partir de cima, de 0 a 360 graus). Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 0 e 90% do tamanho da área de plotagem). Leitura/gravação byte.

**Retorna:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Define o tamanho do buraco em um gráfico de rosca (pode ser entre 0 e 90% do tamanho da área de plotagem). Leitura/gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%). -100%: espaçamento máximo (barras completamente separadas). 0%: barras lado a lado sem sobreposição ou espaçamento. 100%: sobreposição máxima (barras completamente sobrepostas). Esta propriedade é leitura/gravação byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Define quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%). -100%: espaçamento máximo (barras completamente separadas). 0%: barras lado a lado sem sobreposição ou espaçamento. 100%: sobreposição máxima (barras completamente sobrepostas). Esta propriedade é leitura/gravação byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Definir sobreposição para 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Especifica o tamanho da segunda fatia ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como uma porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). Leitura/gravação int.

**Retorna:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Define o tamanho da segunda fatia ou barra de um gráfico de pizza-de-pizza ou barra-de-pizza, como uma porcentagem do tamanho da primeira pizza (pode ser entre 5% e 200%). Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Especifica como os valores de tamanho das bolhas são representados no gráfico de bolhas. Leitura/gravação [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retorna:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Define como os valores de tamanho das bolhas são representados no gráfico de bolhas. Leitura/gravação [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Especifica um valor que será usado para determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. É usado juntamente com a propriedade PieSplitBy. Leitura/gravação double.

**Retorna:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Define um valor que será usado para determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. É usado juntamente com a propriedade PieSplitBy. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Especifica como determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. Leitura/gravação [PieSplitType](../../com.aspose.slides/piesplittype).

**Retorna:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Define como determinar quais pontos de dados estão na segunda fatia ou barra em um gráfico de pizza-de-pizza ou barra-de-pizza. Leitura/gravação [PieSplitType](../../com.aspose.slides/piesplittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/gravação boolean.

**Retorna:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Define que cada marcador de dados na série tem uma cor diferente. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Verdadeiro se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leitura/gravação boolean.

**Retorna:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Define se o gráfico possui linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose.

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). Leitura/gravação int.

**Retorna:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Define o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

As informações de divisão personalizada para um gráfico de pizza-de-pizza ou barra-de-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados na segunda fatia ou barra. Somente-leitura [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Retorna:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente-leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico pai. Somente-leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um FillFormat. Somente-leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um FillFormat. Somente-leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)