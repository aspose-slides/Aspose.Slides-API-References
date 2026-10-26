---
title: ChartCategory
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa categorias de gráfico.
type: docs
url: /pt/com.aspose.slides/chartcategory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Representa categorias de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getUseCell()](#getUseCell--) | Se true então a propriedade AsCell está atual. |
| [getAsCell()](#getAsCell--) | Retorna ou define o objeto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retorna ou define o objeto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Retorna ou define o objeto AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retorna ou define o objeto AsLiteral. |
| [getValue()](#getValue--) | Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contêiner gerenciado dos valores dos níveis de agrupamento de categorias do gráfico. |
| [remove()](#remove--) | Remove a categoria do gráfico. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Se true então a propriedade AsCell está atual. Em outras palavras, a planilha é usada para armazenar a categoria (este caso suporta uma categoria de múltiplos níveis). Se false então a propriedade AsLiteral está atual. Em outras palavras, a planilha NÃO é usada para armazenar a categoria (e este caso não suporta categorias de múltiplos níveis). Boolean somente leitura.

--------------------

Para alterar o valor desta propriedade (para todas as categorias na coleção) defina o novo valor na propriedade ChartCategoryCollection.UseCells.

**Retorna:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retorna ou define o objeto IChartDataCell. Se a categoria for de múltiplos níveis, então o objeto IChartDataCell usado é o de nível "0". Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retorna ou define o objeto IChartDataCell. Se a categoria for de múltiplos níveis, então o objeto IChartDataCell usado é o de nível "0". Leitura/gravação [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Retorna ou define o objeto AsLiteral. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Retorna ou define o objeto AsLiteral. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, então esta propriedade representa a propriedade AsLiteral. Leitura/gravação Object.

**Retorna:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Se UseCell for true, então esta propriedade representa a propriedade AsCell.Value. Se UseCell for false, então esta propriedade representa a propriedade AsLiteral. Leitura/gravação Object.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Contêiner gerenciado dos valores dos níveis de agrupamento de categorias do gráfico. Categoria de múltiplos níveis contém mais de um nível de agrupamento. A indexação dos níveis de agrupamento começa em zero. Somente leitura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retorna:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Remove a categoria do gráfico.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. IDOMObject somente leitura.

**Retorna:**
com.aspose.slides.IDOMObject