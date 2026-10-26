---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: I grafici operano con un set limitato di proprietà di formato del testo.
type: docs
url: /it/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

I grafici operano con un set limitato di proprietà di formato del testo. Le interfacce IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat descrivono questo set limitato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Restituisce il formato per gli elementi di testo del grafico. |
| [getParagraphFormat()](#getParagraphFormat--) | Restituisce il formato del paragrafo. |
| [getPortionFormat()](#getPortionFormat--) | Restituisce il formato della porzione. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copia il formato del testo nel frame di testo specificato. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copia il formato del testo dal frame di testo specificato. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Restituisce il formato per gli elementi di testo del grafico. Solo lettura [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Restituisce:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Restituisce il formato del paragrafo. Solo lettura [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Restituisce:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Restituisce il formato della porzione. Solo lettura [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Restituisce:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Copia il formato del testo nel frame di testo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Frame di testo in cui copiare il formato del testo. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Copia il formato del testo dal frame di testo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Frame di testo da cui copiare il formato del testo. |