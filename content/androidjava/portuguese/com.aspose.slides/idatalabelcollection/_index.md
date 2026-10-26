---
title: IDataLabelCollection
second_title: Aspose.Slides para Android via Referência da API Java
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
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Representa o formato das linhas de líder dos rótulos de dados. |
| [isVisible()](#isVisible--) | Falso significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas). |
| [hide()](#hide--) | Oculta o rótulo de dados por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado falso. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Obtém o número de rótulos de dados visíveis na coleção. |
| [getCount()](#getCount--) | Obtém o número de todos os rótulos de dados na coleção. |
| [getParentSeries()](#getParentSeries--) | Retorna a série de gráfico pai. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Retorna um índice do DataLabel especificado na coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Obtém o rótulo de dados para o ponto de dados com o índice especificado.

--------------------

Forma alternativa de acessar o rótulo de dados é: - getSeries().getDataPoints().get_Item(i).getLabel() - gerenciar propriedades do rótulo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Retorna o formato padrão de todos os rótulos de dados na coleção. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorna:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Representa o formato das linhas de líder dos rótulos de dados. Somente leitura [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

> ```
> Exemplo:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Falso significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat são falsas). Somente leitura boolean.

--------------------

Se o rótulo de dados estiver visível por padrão, você pode torná-lo oculto por padrão com o método Hide(). Mas se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" definindo as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado verdadeiro.

**Retorna:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Torna o rótulo de dados oculto por padrão definindo todas as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado falso. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível por padrão (IsVisible é false), você pode tornar o rótulo de dados "visível por padrão" definindo as flags Show* (ShowValue, ...) da propriedade DefaultDataLabelFormat para o estado verdadeiro.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Obtém o número de rótulos de dados visíveis na coleção. Somente leitura int.

**Retorna:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de todos os rótulos de dados na coleção. Somente leitura int.

**Retorna:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Retorna a série de gráfico pai. Somente leitura [IChartSeries](../../com.aspose.slides/ichartseries).

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Retorna o índice do DataLabel especificado na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel a ser encontrado. |

**Retorna:**
int - Índice de um DataLabel ou -1 se o DataLabel não for desta coleção.