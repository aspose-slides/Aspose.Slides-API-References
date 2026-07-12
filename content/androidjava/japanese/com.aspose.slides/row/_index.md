---
title: Row
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テーブルの行を表します。
type: docs
url: /ja/com.aspose.slides/row/
---
**継承:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

テーブルの行を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeight()](#getHeight--) | 行の高さを返します。 |
| [getMinimalHeight()](#getMinimalHeight--) | 行の最小可能な高さを取得または設定します。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 行の最小可能な高さを取得または設定します。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | すべての行セルの部分に定義された部分フォーマットプロパティを設定します。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | すべての行セルの段落に定義された段落フォーマットプロパティを設定します。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | すべての行セルのテキストフレームに定義されたテキストフレームフォーマットプロパティを設定します。 |
| [getRowFormat()](#getRowFormat--) | この行の書式設定プロパティを含む RowFormat オブジェクトを返します。 |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

行の高さを返します。読み取り専用 double.

**戻り値:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

行の最小可能な高さを取得または設定します。読み書き可能 double.

**戻り値:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

行の最小可能な高さを取得または設定します。読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

すべての行セルの部分に定義された部分フォーマットプロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 必要なプロパティが設定された IPortionFormat オブジェクト。 |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

すべての行セルの段落に定義された段落フォーマットプロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 必要なプロパティが設定された IParagraphFormat オブジェクト。 |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

すべての行セルのテキストフレームに定義されたテキストフレームフォーマットプロパティを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 必要なプロパティが設定された ITextFrameFormat オブジェクト。 |
### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

この行の書式設定プロパティを含む RowFormat オブジェクトを返します。読み取り専用 [IRowFormat](../../com.aspose.slides/irowformat).

**戻り値:**
[IRowFormat](../../com.aspose.slides/irowformat)