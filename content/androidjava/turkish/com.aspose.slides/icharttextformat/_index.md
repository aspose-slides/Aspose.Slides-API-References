---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Grafik, sınırlı bir metin biçim özelliği kümesiyle çalışır.
type: docs
url: /tr/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Grafik, sınırlı bir metin biçim özelliği kümesiyle çalışır. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat arabirimleri bu sınırlı seti açıklar.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Grafik metin öğeleri için biçimi döndürür. |
| [getParagraphFormat()](#getParagraphFormat--) | Paragraf biçimini döndürür. |
| [getPortionFormat()](#getPortionFormat--) | Parça biçimini döndürür. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Belirtilen metin çerçevesine metin biçimini kopyalar. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Belirtilen metin çerçevesinden metin biçimini kopyalar. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Grafik metin öğeleri için biçimi döndürür. Salt-okunur [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Döndürür:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Paragraf biçimini döndürür. Salt-okunur [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Döndürür:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Parça biçimini döndürür. Salt-okunur [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Döndürür:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Belirtilen metin çerçevesine metin biçimini kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metin biçimini kopyalamak için metin çerçevesi. |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Belirtilen metin çerçevesinden metin biçimini kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metin biçimini kopyalamak için metin çerçevesi. |