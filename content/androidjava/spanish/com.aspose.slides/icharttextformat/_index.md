---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Los gráficos operan con un conjunto restringido de propiedades de formato de texto.
type: docs
url: /es/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Los gráficos operan con un conjunto restringido de propiedades de formato de texto. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describen este conjunto restringido.
## Métodos

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Devuelve el formato para los elementos de texto del gráfico. |
| [getParagraphFormat()](#getParagraphFormat--) | Devuelve el formato de párrafo. |
| [getPortionFormat()](#getPortionFormat--) | Devuelve el formato de porción. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copia el formato de texto al marco de texto especificado. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copia el formato de texto del marco de texto especificado. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Devuelve el formato para los elementos de texto del gráfico. Solo lectura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Devuelve:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Devuelve el formato de párrafo. Solo lectura [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Devuelve:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Devuelve el formato de porción. Solo lectura [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Devuelve:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Copia el formato de texto al marco de texto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Marco de texto al que copiar el formato de texto. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Copia el formato de texto del marco de texto especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Marco de texto del que copiar el formato de texto. |