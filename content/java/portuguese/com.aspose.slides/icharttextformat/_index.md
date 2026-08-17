---
title: IChartTextFormat
second_title: Referência da API Aspose.Slides para Java
description: Gráficos operam com um conjunto restrito de propriedades de formato de texto.
type: docs
url: /pt/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Gráficos operam com um conjunto restrito de propriedades de formato de texto. As interfaces IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat descrevem esse conjunto restrito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Retorna o formato dos elementos de texto do gráfico. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o formato do parágrafo. |
| [getPortionFormat()](#getPortionFormat--) | Retorna o formato da porção. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copia o formato de texto para o quadro de texto especificado. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copia o formato de texto do quadro de texto especificado. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Retorna o formato dos elementos de texto do gráfico. Somente leitura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retorna:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Retorna o formato do parágrafo. Somente leitura [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retorna:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Retorna o formato da porção. Somente leitura [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retorna:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Copia o formato de texto para o quadro de texto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto para o qual o formato de texto será copiado. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Copia o formato de texto do quadro de texto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto do qual o formato de texto será copiado. |