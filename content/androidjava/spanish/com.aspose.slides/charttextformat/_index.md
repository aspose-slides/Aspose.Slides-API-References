---
title: ChartTextFormat
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Especifica el formato de texto predeterminado para los elementos de texto del gráfico.
type: docs
url: /es/com.aspose.slides/charttextformat/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Especifica el formato de texto predeterminado para los elementos de texto del gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Solo lectura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Devuelve:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Solo lectura [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Devuelve:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Solo lectura [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Devuelve:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Copia el formato de texto al marco de texto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Marco de texto al que se copiará el formato de texto. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Copia el formato de texto del marco de texto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Marco de texto del cual se copiará el formato de texto. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve Parent_Immediate object. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject