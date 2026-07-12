---
title: Chart
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um gráfico em um slide.
type: docs
url: /pt/com.aspose.slides/chart/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

Representa um gráfico em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | Calcula os valores reais dos elementos do gráfico. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina se somente as células visíveis são plotadas. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina se somente as células visíveis são plotadas. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Retorna ou define a forma de plotar células vazias em um gráfico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Retorna ou define a forma de plotar células vazias em um gráfico. |
| [getChartData()](#getChartData--) | Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. |
| [hasTitle()](#hasTitle--) | Determina se um gráfico tem um título visível. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se um gráfico tem um título visível. |
| [getChartTitle()](#getChartTitle--) | Retorna ou define o título do gráfico. |
| [hasDataTable()](#hasDataTable--) | Determina se um gráfico tem uma tabela de dados. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determina se um gráfico tem uma tabela de dados. |
| [hasLegend()](#hasLegend--) | Determina se um gráfico tem uma legenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determina se um gráfico tem uma legenda. |
| [getLegend()](#getLegend--) | Retorna ou define uma legenda para um gráfico. |
| [getChartDataTable()](#getChartDataTable--) | Retorna uma tabela de dados de um gráfico. |
| [getStyle()](#getStyle--) | Retorna ou define o estilo do gráfico. |
| [setStyle(int value)](#setStyle-int-) | Retorna ou define o estilo do gráfico. |
| [getType()](#getType--) | Retorna ou define o tipo do gráfico. |
| [setType(int value)](#setType-int-) | Retorna ou define o tipo do gráfico. |
| [getPlotArea()](#getPlotArea--) | Representa a área de plotagem de um gráfico. |
| [getRotation3D()](#getRotation3D--) | Retorna uma rotação 3D de um gráfico. |
| [getBackWall()](#getBackWall--) | Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. |
| [getSideWall()](#getSideWall--) | Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. |
| [getFloor()](#getFloor--) | Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato de texto do gráfico. |
| [createThemeEffective()](#createThemeEffective--) | Retorna um tema efetivo para este gráfico. |
| [getThemeManager()](#getThemeManager--) | Retorna o gerenciador de temas. |
| [getUserShapes()](#getUserShapes--) | Especifica as formas desenhadas sobre o gráfico. |
| [getAxes()](#getAxes--) | Fornece acesso aos eixos do gráfico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Especifica que a área do gráfico deve ter cantos arredondados. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Especifica que a área do gráfico deve ter cantos arredondados. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

Calcula os valores reais dos elementos do gráfico. Os valores reais incluem a posição dos elementos que implementam a interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e os valores reais dos eixos (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

Determina se somente as células visíveis são plotadas. False para plotar tanto células visíveis quanto ocultas. Leitura/gravação boolean.

**Retorna:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

Determina se somente as células visíveis são plotadas. False para plotar tanto células visíveis quanto ocultas. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

Retorna ou define a forma de plotar células vazias em um gráfico. Leitura/gravação [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Retorna:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

Retorna ou define a forma de plotar células vazias em um gráfico. Leitura/gravação [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. Somente leitura [IChartData](../../com.aspose.slides/ichartdata).

**Retorna:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Determina se um gráfico tem um título visível. Leitura/gravação boolean.

**Retorna:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Determina se um gráfico tem um título visível. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

Retorna ou define o título do gráfico. Somente leitura [IChartTitle](../../com.aspose.slides/icharttitle).

**Retorna:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

Determina se um gráfico tem uma tabela de dados. Leitura/gravação boolean.

**Retorna:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

Determina se um gráfico tem uma tabela de dados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

Determina se um gráfico tem uma legenda. Leitura/gravação boolean.

**Retorna:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

Determina se um gráfico tem uma legenda. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

Retorna ou define uma legenda para um gráfico. Somente leitura [ILegend](../../com.aspose.slides/ilegend).

**Retorna:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

Retorna uma tabela de dados de um gráfico. Somente leitura [IDataTable](../../com.aspose.slides/idatatable).

**Retorna:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

Retorna ou define o estilo do gráfico. Leitura/gravação [StyleType](../../com.aspose.slides/styletype).

**Retorna:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

Retorna ou define o estilo do gráfico. Leitura/gravação [StyleType](../../com.aspose.slides/styletype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

Retorna ou define o tipo do gráfico. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Retorna ou define o tipo do gráfico. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

Representa a área de plotagem de um gráfico. Somente leitura [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Retorna:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

Retorna uma rotação 3D de um gráfico. Somente leitura [IRotation3D](../../com.aspose.slides/irotation3d).

**Retorna:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retorna o formato de texto do gráfico. A propriedade não se aplica aos seguintes tipos: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retorna um tema efetivo para este gráfico.

**Retorna:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retorna o gerenciador de temas. Somente leitura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retorna:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

Especifica as formas desenhadas sobre o gráfico. Somente leitura [IGroupShape](../../com.aspose.slides/igroupshape).

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

Fornece acesso aos eixos do gráfico. Somente leitura [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Retorna:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Leitura/gravação boolean.

**Retorna:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

Especifica que a área do gráfico deve ter cantos arredondados. Leitura/gravação boolean.

**Retorna:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

Especifica que a área do gráfico deve ter cantos arredondados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)