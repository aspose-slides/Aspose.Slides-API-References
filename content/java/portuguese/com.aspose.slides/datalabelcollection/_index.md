---
title: DataLabelCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/datalabelcollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Representa rótulos de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são false). |
| [hide()](#hide--) | Faça o rótulo de dados oculto por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat como false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtém o número de rótulos de dados visíveis na coleção. |
| [getCount()](#getCount--) | Obtém o número de todos os rótulos de dados na coleção. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Obtém o formato padrão do rótulo de dados. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa o formato das linhas líderes dos rótulos de dados. |
| [getParentSeries()](#getParentSeries--) | Obtém a série pai. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retorna um índice do DataLabel especificado na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o rótulo de dados para o ponto de dados com o índice especificado. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Obtém ou define o tipo de forma padrão para rótulos de dados. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Obtém ou define o tipo de forma padrão para rótulos de dados. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```


Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Um java.util.Iterator para a coleção inteira.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são false). Booleano somente leitura.

--------------------

Se o rótulo de dados estiver visível por padrão, você pode torná-lo oculto por padrão com o método Hide(). Mas se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" configurando as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado true.

**Retorna:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Faça o rótulo de dados oculto por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat como false. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" configurando as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Obtém o número de rótulos de dados visíveis na coleção. Inteiro somente leitura.

**Retorna:**
int
### getCount() {#getCount--}
```
public final int getCount()
```


Obtém o número de todos os rótulos de dados na coleção. Inteiro somente leitura.

**Retorna:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```


Obtém o formato padrão do rótulo de dados. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorna:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```


Representa o formato das linhas líderes dos rótulos de dados. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```


Obtém a série pai. Somente leitura [IChartSeries](../../com.aspose.slides/ichartseries).

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```


Retorna um índice do DataLabel especificado na coleção.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a ser encontrado. |

**Retorna:**
int - Índice de um DataLabel ou -1 se o DataLabel não for desta coleção.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Obtém o rótulo de dados para o ponto de dados com o índice especificado.

--------------------

Outra forma de acessar o rótulo de dados é: - series.getDataPoints().get_Item(i).getLabel() - gerenciar propriedades do rótulo.

**Parâmetros:**
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```


Obtém ou define o tipo de forma padrão para rótulos de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma for definida.

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

**Retorna:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```


Obtém ou define o tipo de forma padrão para rótulos de dados. Retorna [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) se nenhuma forma for definida.

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
| Parámetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

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