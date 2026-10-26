---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: Line または Stock チャートのアップ/ダウン バーへのアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Line または Stock チャートのアップ/ダウン バーへのアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | アップ バーのフォーマットを返します。 |
| [getDownBarsFormat()](#getDownBarsFormat--) | ダウン バーのフォーマットを返します。 |
| [hasUpDownBars()](#hasUpDownBars--) | チャートにアップ/ダウン バーがあるかどうかを判定します。 |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | チャートにアップ/ダウン バーがあるかどうかを判定します。 |
| [getGapWidth()](#getGapWidth--) | ギャップ幅を返すまたは設定します。 |
| [setGapWidth(int value)](#setGapWidth-int-) | ギャップ幅を返すまたは設定します。 |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

アップ バーのフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

ダウン バーのフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

チャートにアップ/ダウン バーがあるかどうかを判定します。読み書き boolean。

**戻り値:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

チャートにアップ/ダウン バーがあるかどうかを判定します。読み書き boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

ギャップ幅を返すまたは設定します。読み書き int。

**戻り値:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

ギャップ幅を返すまたは設定します。読み書き int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |