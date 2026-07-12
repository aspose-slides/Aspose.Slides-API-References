---
title: IChart
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um gráfico em um slide.
type: docs
url: /pt/com.aspose.slides/ichart/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

Representa um gráfico em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | Determina se apenas as células visíveis são plotadas. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | Determina se apenas as células visíveis são plotadas. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | Retorna ou define a forma de plotar células em branco em um gráfico. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | Retorna ou define a forma de plotar células em branco em um gráfico. |
| [getChartData()](#getChartData--) | Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. |
| [hasTitle()](#hasTitle--) | Determina se um gráfico tem um título visível. |
| [setTitle(boolean value)](#setTitle-boolean-) | Determina se um gráfico tem um título visível. |
| [getChartTitle()](#getChartTitle--) | Retorna ou define um título de gráfico Somente leitura [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | Determina se um gráfico tem uma tabela de dados. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | Determina se um gráfico tem uma tabela de dados. |
| [hasLegend()](#hasLegend--) | Determina se um gráfico tem uma legenda. |
| [setLegend(boolean value)](#setLegend-boolean-) | Determina se um gráfico tem uma legenda. |
| [getLegend()](#getLegend--) | Retorna ou define uma legenda para um gráfico. |
| [getChartDataTable()](#getChartDataTable--) | Retorna uma tabela de dados de um gráfico. |
| [getStyle()](#getStyle--) | Retorna ou define o estilo do gráfico. |
| [setStyle(int value)](#setStyle-int-) | Retorna ou define o estilo do gráfico. |
| [getType()](#getType--) | Retorna ou define o tipo de gráfico. |
| [setType(int value)](#setType-int-) | Retorna ou define o tipo de gráfico. |
| [getPlotArea()](#getPlotArea--) | Representa a área de plotagem de um gráfico. |
| [getRotation3D()](#getRotation3D--) | Retorna uma rotação 3D de um gráfico. |
| [getBackWall()](#getBackWall--) | Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. |
| [getSideWall()](#getSideWall--) | Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. |
| [getFloor()](#getFloor--) | Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. |
| [getUserShapes()](#getUserShapes--) | Especifica as formas desenhadas sobre o gráfico. |
| [getAxes()](#getAxes--) | Fornece acesso aos eixos do gráfico. |
| [validateChartLayout()](#validateChartLayout--) | Calcula os valores reais dos elementos do gráfico. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. |
| [hasRoundedCorners()](#hasRoundedCorners--) | Especifica que a área do gráfico deve ter cantos arredondados. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | Especifica que a área do gráfico deve ter cantos arredondados. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

Determina se apenas as células visíveis são plotadas. False para plotar tanto as células visíveis quanto as ocultas. Leitura/gravação boolean.

**Retorna:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

Determina se apenas as células visíveis são plotadas. False para plotar tanto as células visíveis quanto as ocultas. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

Retorna ou define a forma de plotar células em branco em um gráfico. Leitura/gravação [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Retorna:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

Retorna ou define a forma de plotar células em branco em um gráfico. Leitura/gravação [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. Somente leitura [IChartData](../../com.aspose.slides/ichartdata).

**Retorna:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Determina se um gráfico tem um título visível. Leitura/gravação boolean.

**Retorna:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Determina se um gráfico tem um título visível. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

Retorna ou define um título de gráfico Somente leitura [IChartTitle](../../com.aspose.slides/icharttitle).

**Retorna:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

Determina se um gráfico tem uma tabela de dados. Leitura/gravação boolean.

**Retorna:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

Determina se um gráfico tem uma tabela de dados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

Determina se um gráfico tem uma legenda. Leitura/gravação boolean.

**Retorna:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

Determina se um gráfico tem uma legenda. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

Retorna ou define uma legenda para um gráfico. Somente leitura [ILegend](../../com.aspose.slides/ilegend).

**Retorna:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

Retorna uma tabela de dados de um gráfico. Somente leitura [IDataTable](../../com.aspose.slides/idatatable).

**Retorna:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

Retorna ou define o estilo do gráfico. Leitura/gravação [StyleType](../../com.aspose.slides/styletype).

**Retorna:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

Retorna ou define o estilo do gráfico. Leitura/gravação [StyleType](../../com.aspose.slides/styletype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

Retorna ou define o tipo de gráfico. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Retorna:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Retorna ou define o tipo de gráfico. Leitura/gravação [ChartType](../../com.aspose.slides/charttype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

Representa a área de plotagem de um gráfico. Somente leitura [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**Retorna:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

Retorna uma rotação 3D de um gráfico. Somente leitura [IRotation3D](../../com.aspose.slides/irotation3d).

**Retorna:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. Somente leitura [IChartWall](../../com.aspose.slides/ichartwall).

**Retorna:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

Especifica as formas desenhadas sobre o gráfico. Somente leitura [IGroupShape](../../com.aspose.slides/igroupshape).

**Retorna:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

Fornece acesso aos eixos do gráfico. Somente leitura [IAxesManager](../../com.aspose.slides/iaxesmanager).

**Retorna:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

Calcula os valores reais dos elementos do gráfico. Valores reais incluem posição dos elementos que implementam a interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e valores reais dos eixos (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Leitura/gravação boolean.

**Retorna:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

Especifica que os rótulos de dados acima do máximo do gráfico devem ser mostrados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

Especifica que a área do gráfico deve ter cantos arredondados. Leitura/gravação boolean.

**Retorna:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

Especifica que a área do gráfico deve ter cantos arredondados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |