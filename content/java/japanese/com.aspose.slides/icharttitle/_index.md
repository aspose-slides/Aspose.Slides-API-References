---
title: IChartTitle
second_title: Aspose.Slides for Java API リファレンス
description: チャートタイトルのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/icharttitle/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

チャートタイトルのプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 他のチャート要素がタイトルと重なることを許可するかどうかを判断します。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 他のチャート要素がタイトルと重なることを許可するかどうかを判断します。 |
| [getFormat()](#getFormat--) | タイトルの塗りつぶし、線、効果スタイルを返します。 |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


他のチャート要素がタイトルと重なることを許可するかどうかを判断します。 読み書き可能な boolean。

**戻り値:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


他のチャート要素がタイトルと重なることを許可するかどうかを判断します。 読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


タイトルの塗りつぶし、線、効果スタイルを返します。 読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)