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

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Se true então a propriedade AsCell está efetiva. |
| [getAsCell()](#getAsCell--) | Retorna ou define o objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retorna ou define o objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Retorna ou define AsLiteral se UseCell for false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retorna ou define AsLiteral se UseCell for false. |
| [getValue()](#getValue--) | Se UseCell for true, esta propriedade representa a propriedade AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Se UseCell for true, esta propriedade representa a propriedade AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contêiner gerenciado dos valores dos níveis de agrupamento da categoria do gráfico. |
| [remove()](#remove--) | Remove a categoria do gráfico. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Se true então a propriedade AsCell está efetiva. Em outras palavras, a planilha é usada para armazenar a categoria (este caso suporta uma categoria de vários níveis). Se false então a propriedade AsLiteral está efetiva. Em outras palavras, a planilha NÃO é usada para armazenar a categoria (e este caso não suporta categorias de vários níveis). Boolean somente leitura.

--------------------

Para alterar o valor desta propriedade (para todas as categorias na coleção) defina um novo valor na propriedade [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Retorna:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Retorna ou define o objeto IChartDataCell. Se a categoria for de vários níveis, então usa o objeto IChartDataCell para o nível "0". Leitura/Gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Retorna ou define o objeto IChartDataCell. Se a categoria for de vários níveis, então usa o objeto IChartDataCell para o nível "0". Leitura/Gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Retorna ou define AsLiteral se UseCell for false. Leitura/Gravação Object.

**Retorna:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Retorna ou define AsLiteral se UseCell for false. Leitura/Gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Se UseCell for true, esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, esta propriedade representa a propriedade AsLiteral. Leitura/Gravação Object.

**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Se UseCell for true, esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, esta propriedade representa a propriedade AsLiteral. Leitura/Gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Contêiner gerenciado dos valores dos níveis de agrupamento da categoria do gráfico. Categorias de vários níveis contêm mais de um nível de agrupamento. A indexação dos níveis de agrupamento começa em zero. Apenas leitura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retorna:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Remove a categoria do gráfico.