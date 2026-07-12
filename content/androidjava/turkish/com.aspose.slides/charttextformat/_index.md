---
title: ChartTextFormat
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Grafik metin öğeleri için varsayılan metin biçimlendirmesini belirtir.
type: docs
url: /tr/com.aspose.slides/charttextformat/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Grafik metin öğeleri için varsayılan metin biçimlendirmesini belirtir.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Metin biçimini belirtilen metin çerçevesine kopyalar. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Metin biçimini belirtilen metin çerçevesinden kopyalar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Yalnızca okunur [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Döndürür:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Yalnızca okunur [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Döndürür:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Yalnızca okunur [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Döndürür:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Metin biçimini belirtilen metin çerçevesine kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metin biçiminin kopyalanacağı metin çerçevesi. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Metin biçimini belirtilen metin çerçevesinden kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metin biçiminin kopyalanacağı metin çerçevesi. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject