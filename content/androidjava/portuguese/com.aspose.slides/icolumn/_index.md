---
title: IColumn
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coluna em uma tabela.
type: docs
url: /pt/com.aspose.slides/icolumn/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Representa uma coluna em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getWidth()](#getWidth--) | Retorna ou define a largura de uma coluna. |
| [setWidth(double value)](#setWidth-double-) | Retorna ou define a largura de uma coluna. |
| [getColumnFormat()](#getColumnFormat--) | Retorna o objeto ColumnFormat que contém propriedades de formatação para esta coluna. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retorna ou define a largura de uma coluna. Leitura/Gravação double.

**Retorna:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Retorna ou define a largura de uma coluna. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

Retorna o objeto ColumnFormat que contém propriedades de formatação para esta coluna. Somente leitura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retorna:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)