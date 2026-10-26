---
title: Row
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa uma linha em uma tabela.
type: docs
url: /pt/com.aspose.slides/row/
---
**Herança:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Representa uma linha em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHeight()](#getHeight--) | Retorna a altura de uma linha. |
| [getMinimalHeight()](#getMinimalHeight--) | Retorna ou define a altura mínima possível de uma linha. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Retorna ou define a altura mínima possível de uma linha. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Define propriedades de formato de porção definidas para todas as porções das células da linha. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Define propriedades de formato de parágrafo definidas para todos os parágrafos das células da linha. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Define propriedades de formato de quadro de texto definidas para todos os quadros de texto das células da linha. |
| [getRowFormat()](#getRowFormat--) | Retorna o objeto RowFormat que contém propriedades de formatação para esta linha. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Retorna a altura de uma linha. Somente leitura double.

**Retorna:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Retorna ou define a altura mínima possível de uma linha. Leitura/gravação double.

**Retorna:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Retorna ou define a altura mínima possível de uma linha. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Define propriedades de formato de porção definidas para todas as porções das células da linha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | objeto IPortionFormat com as propriedades necessárias definidas. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Define propriedades de formato de parágrafo definidas para todos os parágrafos das células da linha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | objeto IParagraphFormat com as propriedades necessárias definidas. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Define propriedades de formato de quadro de texto definidas para todos os quadros de texto das células da linha.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | objeto ITextFrameFormat com as propriedades necessárias definidas. |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Retorna o objeto RowFormat que contém propriedades de formatação para esta linha. Somente leitura [IRowFormat](../../com.aspose.slides/irowformat).

**Retorna:**
[IRowFormat](../../com.aspose.slides/irowformat)