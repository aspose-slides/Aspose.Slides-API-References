---
title: IRow
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テーブルの行を表します。
type: docs
url: /ja/com.aspose.slides/irow/
---
**すべての実装インターフェイス:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

テーブルの行を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeight()](#getHeight--) | 行の高さを取得します。 |
| [getMinimalHeight()](#getMinimalHeight--) | 行の最小可能高さを取得または設定します。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 行の最小可能高さを取得または設定します。 |
| [getRowFormat()](#getRowFormat--) | この行の書式設定プロパティを含む RowFormat オブジェクトを取得します。 |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

行の高さを取得します。読み取り専用 double.

**戻り値:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

行の最小可能高さを取得または設定します。読み取り/書き込み可能 double.

**戻り値:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

行の最小可能高さを取得または設定します。読み取り/書き込み可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

この行の書式設定プロパティを含む RowFormat オブジェクトを取得します。読み取り専用 [IRowFormat](../../com.aspose.slides/irowformat)。

**戻り値:**
[IRowFormat](../../com.aspose.slides/irowformat)