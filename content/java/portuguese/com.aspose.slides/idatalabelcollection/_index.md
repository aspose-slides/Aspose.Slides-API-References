---
title: IDataLabelCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/idatalabelcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Representa rótulos de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o rótulo de dados para o ponto de dados com o índice especificado. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Retorna o formato padrão de todos os rótulos de dados na coleção. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa o formato das linhas de liderança dos rótulos de dados. |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas). |
| [hide()](#hide--) | Oculta o rótulo de dados por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado falso. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtém o número de rótulos de dados visíveis na coleção. |
| [getCount()](#getCount--) | Obtém o número de todos os rótulos de dados na coleção. |
| [getParentSeries()](#getParentSeries--) | Retorna a série de gráfico pai. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retorna um índice do DataLabel especificado na coleção. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Obtém ou define o tipo de forma padrão para rótulos de dados. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Obtém ou define o tipo de forma padrão para rótulos de dados. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Obtém o rótulo de dados para o ponto de dados com o índice especificado.

--------------------

Outra forma de acessar o rótulo de dados é: - getSeries().getDataPoints().get_Item(i).getLabel() - gerenciar as propriedades do rótulo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Retorna o formato padrão de todos os rótulos de dados na coleção. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorno:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Representa o formato das linhas de liderança dos rótulos de dados. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorno:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas). Somente leitura boolean.

--------------------

Se o rótulo de dados estiver visível por padrão, você pode ocultá-lo por padrão com o método Hide(). Mas se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" definindo as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado verdadeiro.

**Retorno:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Oculta o rótulo de dados por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado falso. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" definindo as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado verdadeiro.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Obtém o número de rótulos de dados visíveis na coleção. Somente leitura int.

**Retorno:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtém o número de todos os rótulos de dados na coleção. Somente leitura int.

**Retorno:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Retorna a série de gráfico pai. Somente leitura [IChartSeries](../../com.aspose.slides/ichartseries).

**Retorno:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Retorna um índice do DataLabel especificado na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a ser encontrado. |

**Retorno:**
int - Índice de um DataLabel ou -1 se o DataLabel não pertencer a esta coleção.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Obtém ou define o tipo de forma padrão para rótulos de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma estiver definida.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Defina o tipo de forma de todos os rótulos de dados na primeira série como Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Definir esta propriedade também define a propriedade IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) para todos os rótulos de dados na coleção com o mesmo valor.

**Retorno:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Obtém ou define o tipo de forma padrão para rótulos de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma estiver definida.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Defina o tipo de forma de todos os rótulos de dados na primeira série como Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Definir esta propriedade também define a propriedade IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) para todos os rótulos de dados na coleção com o mesmo valor.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |