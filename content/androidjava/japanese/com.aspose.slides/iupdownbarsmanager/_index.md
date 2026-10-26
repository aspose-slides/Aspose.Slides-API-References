---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Provide access to up/down bars of Line- or Stock-chart.
type: docs
url: /ja/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Line または Stock チャートのアップ/ダウンバーへのアクセスを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | アップバーのフォーマットを返します。 |
| [getDownBarsFormat()](#getDownBarsFormat--) | ダウンバーのフォーマットを返します。 |
| [hasUpDownBars()](#hasUpDownBars--) | チャートにアップ/ダウンバーがあるかどうかを判断します。 |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | チャートにアップ/ダウンバーがあるかどうかを判断します。 |
| [getGapWidth()](#getGapWidth--) | ギャップ幅を返すまたは設定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | ギャップ幅を返すまたは設定します。 |

### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

アップバーのフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

ダウンバーのフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

チャートにアップ/ダウンバーがあるかどうかを判断します。読み書き可能 boolean。

**戻り値:**
boolean

### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

チャートにアップ/ダウンバーがあるかどうかを判断します。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

ギャップ幅を返すまたは設定します。読み書き可能 int。

**戻り値:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

ギャップ幅を返すまたは設定します。読み書き可能 int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |