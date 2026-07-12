---
title: IRow
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma linha em uma tabela.
type: docs
url: /pt/com.aspose.slides/irow/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Representa uma linha em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeight()](#getHeight--) | Retorna a altura de uma linha. |
| [getMinimalHeight()](#getMinimalHeight--) | Retorna ou define a altura mínima possível de uma linha. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Retorna ou define a altura mínima possível de uma linha. |
| [getRowFormat()](#getRowFormat--) | Retorna o objeto RowFormat que contém propriedades de formatação para esta linha. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Retorna a altura de uma linha. Somente leitura double.

**Retorna:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Retorna ou define a altura mínima possível de uma linha. Leitura/gravação double.

**Retorna:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Retorna ou define a altura mínima possível de uma linha. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Retorna o objeto RowFormat que contém propriedades de formatação para esta linha. Somente leitura [IRowFormat](../../com.aspose.slides/irowformat).

**Retorna:**
[IRowFormat](../../com.aspose.slides/irowformat)