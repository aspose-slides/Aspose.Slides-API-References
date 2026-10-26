---
title: IChartTextFormat
second_title: Aspose.Slides for Java API リファレンス
description: チャートは制限されたテキスト書式プロパティのセットで操作されます。
type: docs
url: /ja/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

チャートは制限されたテキスト書式プロパティのセットで操作されます。IChartTextFormat、IChartTextBlockFormat、IChartParagraphFormat、IChartPortionFormat インターフェイスはこの制限されたセットを記述します。
## Methods

| メソッド | 説明 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | チャートテキスト要素の書式を返します。 |
| [getParagraphFormat()](#getParagraphFormat--) | 段落書式を返します。 |
| [getPortionFormat()](#getPortionFormat--) | 部分書式を返します。 |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | 指定されたテキストフレームにテキスト書式をコピーします。 |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | 指定されたテキストフレームからテキスト書式をコピーします。 |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

チャートテキスト要素の書式を返します。読み取り専用 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)。

**戻り値:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

段落書式を返します。読み取り専用 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)。

**戻り値:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

部分書式を返します。読み取り専用 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)。

**戻り値:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

指定されたテキストフレームにテキスト書式をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキスト書式をコピーするテキストフレーム。 |
### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

指定されたテキストフレームからテキスト書式をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキスト書式をコピーするテキストフレーム。 |