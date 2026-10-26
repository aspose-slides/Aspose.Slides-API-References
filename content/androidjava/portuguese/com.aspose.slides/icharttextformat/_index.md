---
title: IChartTextFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: O gráfico opera com um conjunto restrito de propriedades de formato de texto.
type: docs
url: /pt/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

O gráfico opera com um conjunto restrito de propriedades de formato de texto. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces descrevem esse conjunto restrito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Retorna o formato para os elementos de texto do gráfico. |
| [getParagraphFormat()](#getParagraphFormat--) | Retorna o formato do parágrafo. |
| [getPortionFormat()](#getPortionFormat--) | Retorna o formato da porção. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copia o formato de texto para o quadro de texto especificado. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copia o formato de texto do quadro de texto especificado. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Retorna o formato para os elementos de texto do gráfico. Somente leitura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

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
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto para o qual copiar o formato de texto. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Copia o formato de texto do quadro de texto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto do qual copiar o formato de texto. |