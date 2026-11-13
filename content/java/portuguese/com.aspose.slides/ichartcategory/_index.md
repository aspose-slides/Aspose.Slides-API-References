---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Representa categorias de gráfico.
type: docs
url: /pt/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Representa categorias de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getUseCell()](#getUseCell--) | Se true, então a propriedade AsCell está atual. |
| [getAsCell()](#getAsCell--) | Retorna ou define o objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retorna ou define o objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Retorna ou define AsLiteral se UseCell for false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retorna ou define AsLiteral se UseCell for false. |
| [getValue()](#getValue--) | Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Obtém o valor em cache de uma categoria de gráfico. |
| [getGroupingLevels()](#getGroupingLevels--) | Contêiner gerenciado dos valores dos níveis de agrupamento da categoria de gráfico. |
| [remove()](#remove--) | Remove a categoria do gráfico. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Se true, então a propriedade AsCell está atual. Em outras palavras, a planilha é usada para armazenar a categoria (este caso suporta uma categoria de múltiplos níveis). Se false, então a propriedade AsLiteral está atual. Em outras palavras, a planilha NÃO é usada para armazenar a categoria (e este caso não suporta categorias de múltiplos níveis). Somente leitura boolean.

--------------------

Para alterar o valor desta propriedade (para todas as categorias na coleção) defina um novo valor na propriedade [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Retorna:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Retorna ou define o objeto IChartDataCell. Se a categoria for de múltiplos níveis, então o objeto IChartDataCell usado é o nível "0". Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Retorna ou define o objeto IChartDataCell. Se a categoria for de múltiplos níveis, então o objeto IChartDataCell usado é o nível "0". Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Retorna ou define AsLiteral se UseCell for false. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Retorna ou define AsLiteral se UseCell for false. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, então esta propriedade representa a propriedade AsLiteral. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, então esta propriedade representa a propriedade AsLiteral. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Obtém o valor em cache de uma categoria de gráfico. Somente leitura [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Imprime todos os valores em cache das categorias do gráfico.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Contêiner gerenciado dos valores dos níveis de agrupamento da categoria de gráfico. Categoria de múltiplos níveis contém mais de um nível de agrupamento. A indexação dos níveis de agrupamento inicia em zero. Somente leitura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retorna:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Remove a categoria do gráfico.