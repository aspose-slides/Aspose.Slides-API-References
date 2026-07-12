---
title: IChartSeriesGroup
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um grupo de séries.
type: docs
url: /pt/com.aspose.slides/ichartseriesgroup/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Representa um grupo de séries.

--------------------

1) Consulte o resumo e observações para a classe ChartSeriesGroupCollection e o enum CombinableSeriesTypesGroup. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo (“propriedades do grupo de séries”). “Propriedades do grupo de séries” na classe ChartSeriesGroup tem leitura/gravação. Cada uma das “propriedades do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna um tipo deste grupo de séries. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indica se as séries deste grupo são plotadas em eixo secundário. |
| [getSeries()](#getSeries--) | Retorna uma coleção somente leitura de séries de gráfico. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getUpDownBars()](#getUpDownBars--) | Fornece acesso às barras alta/baixa de gráfico de linha ou de ações. |
| [getGapWidth()](#getGapWidth--) | Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. |
| [setGapWidth(int value)](#setGapWidth-int-) | Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. |
| [getGapDepth()](#getGapDepth--) | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Obtém ou define o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Obtém ou define o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). |
| [isColorVaried()](#isColorVaried--) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Especifica que cada marcador de dados na série tem uma cor diferente. |
| [hasSeriesLines()](#hasSeriesLines--) | Verdadeiro se o gráfico tem linhas de série. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Verdadeiro se o gráfico tem linhas de série. |
| [getOverlap()](#getOverlap--) | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Especifica o tamanho do segundo pedaço ou barra de um gráfico pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Especifica o tamanho do segundo pedaço ou barra de um gráfico pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Especifica um valor que será usado para determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Especifica um valor que será usado para determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. |
| [getPieSplitBy()](#getPieSplitBy--) | Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | A informação de divisão personalizada para um gráfico pizza-em-pizza ou barra-em-pizza com divisão personalizada. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90% do tamanho da área de plotagem). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90% do tamanho da área de plotagem). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Especifica o formato HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. |

### getType() {#getType--}
```
public abstract int getType()
```

Retorna um tipo deste grupo de séries. Somente leitura [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Retorna:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Indica se as séries deste grupo são plotadas em eixo secundário. Somente leitura boolean.

**Retorna:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Retorna uma coleção somente leitura de séries de gráfico. Somente leitura [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Retorna:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Fornece acesso às barras alta/baixa de gráfico de linha ou de ações. Somente leitura [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Retorna:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. Leitura/Gravação int.

**Retorna:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Especifica o espaço entre clusters de barras ou colunas, como porcentagem da largura da barra ou coluna. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leitura/Gravação int.

**Retorna:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Retorna ou define a distância, como porcentagem da largura do marcador, entre as séries de dados em um gráfico 3D. Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Obtém ou define o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). Leitura/Gravação int.

**Retorna:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Obtém ou define o ângulo da primeira fatia de pizza ou rosca, em graus (no sentido horário a partir do topo, de 0 a 360 graus). Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/Gravação boolean.

**Retorna:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Especifica que cada marcador de dados na série tem uma cor diferente. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Verdadeiro se o gráfico tem linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leitura/Gravação boolean.

**Retorna:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Verdadeiro se o gráfico tem linhas de série. Aplicado a gráficos de barra empilhada e OfPie. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). -100%: espaçamento máximo (barras totalmente separadas). -0%: barras lado a lado sem sobreposição ou espaçamento. 100%: sobreposição máxima (barras totalmente sobrepostas). Esta propriedade é leitura/gravação byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como porcentagem (de -100% a 100%). -100%: espaçamento máximo (barras totalmente separadas). -0%: barras lado a lado sem sobreposição ou espaçamento. 100%: sobreposição máxima (barras totalmente sobrepostas). Esta propriedade é leitura/gravação byte.

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
public abstract int getSecondPieSize()
```

Especifica o tamanho do segundo pedaço ou barra de um gráfico pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200%). Leitura/Gravação int.

**Retorna:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Especifica o tamanho do segundo pedaço ou barra de um gráfico pizza-em-pizza ou barra-em-pizza, como porcentagem do tamanho da primeira pizza (pode ser entre 5 e 200%). Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Especifica um valor que será usado para determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. É usado juntamente com a propriedade PieSplitBy. Leitura/Gravação double.

**Retorna:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Especifica um valor que será usado para determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. É usado juntamente com a propriedade PieSplitBy. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. Leitura/Gravação [PieSplitType](../../com.aspose.slides/piesplittype).

**Retorna:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Especifica como determinar quais pontos de dados estão no segundo pedaço ou barra em um gráfico pizza-em-pizza ou barra-em-pizza. Leitura/Gravação [PieSplitType](../../com.aspose.slides/piesplittype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

A informação de divisão personalizada para um gráfico pizza-em-pizza ou barra-em-pizza com divisão personalizada. Contém pontos de dados que devem ser desenhados no segundo pedaço ou barra. Somente leitura [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Retorna:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90% do tamanho da área de plotagem). Leitura/Gravação byte.

**Retorna:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Especifica o tamanho do buraco em um gráfico de rosca (pode ser entre 10 e 90% do tamanho da área de plotagem). Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). Leitura/Gravação int.

**Retorna:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Especifica o fator de escala para o gráfico de bolhas (pode ser entre 0 e 300% do tamanho padrão). Leitura/Gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Especifica o formato HiLowLines. HiLowLines aplicado com os tipos de gráfico HiLowClose, OpenHiLowClose, VolumeHiLowClose e VolumeOpenHiLowClose.

**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leitura/Gravação [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Retorna:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Especifica como os valores de tamanho da bolha são representados no gráfico de bolhas. Leitura/Gravação [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |