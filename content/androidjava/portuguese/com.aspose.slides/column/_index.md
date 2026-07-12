---
title: Column
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coluna em uma tabela.
type: docs
url: /pt/com.aspose.slides/column/
---
**Herança:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Representa uma coluna em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getWidth()](#getWidth--) | Retorna ou define a largura de uma coluna. |
| [setWidth(double value)](#setWidth-double-) | Retorna ou define a largura de uma coluna. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Define as propriedades de formato de porção definidas para todas as porções das células da coluna. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Define as propriedades de formato de parágrafo definidas para todos os parágrafos das células da coluna. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Define as propriedades de formato de quadro de texto definidas para todos os quadros de texto das células da coluna. |
| [getColumnFormat()](#getColumnFormat--) | Retorna o objeto ColumnFormat que contém propriedades de formatação para esta coluna. |

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Retorna ou define a largura de uma coluna. Leitura/gravação double.

**Retorna:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Retorna ou define a largura de uma coluna. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Define as propriedades de formato de porção definidas para todas as porções das células da coluna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objeto IPortionFormat com as propriedades necessárias definidas. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Define as propriedades de formato de parágrafo definidas para todos os parágrafos das células da coluna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objeto IParagraphFormat com as propriedades necessárias definidas. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Define as propriedades de formato de quadro de texto definidas para todos os quadros de texto das células da coluna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objeto ITextFrameFormat com as propriedades necessárias definidas. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Retorna o objeto ColumnFormat que contém propriedades de formatação para esta coluna. Somente leitura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retorna:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)