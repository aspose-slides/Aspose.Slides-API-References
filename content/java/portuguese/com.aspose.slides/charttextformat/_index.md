---
title: ChartTextFormat
second_title: Referência da API Aspose.Slides para Java
description: Especifica a formatação de texto padrão para elementos de texto de gráfico.
type: docs
url: /pt/com.aspose.slides/charttextformat/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Especifica a formatação de texto padrão para elementos de texto de gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copia a formatação de texto para o quadro de texto especificado. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copia a formatação de texto do quadro de texto especificado. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. Somente leitura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retorna:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. Somente leitura [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retorna:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. Somente leitura [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retorna:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

Copia a formatação de texto para o quadro de texto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto para o qual copiar a formatação de texto. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

Copia a formatação de texto do quadro de texto especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Quadro de texto para copiar a formatação de texto. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject