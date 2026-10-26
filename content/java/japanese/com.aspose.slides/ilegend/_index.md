---
title: ILegend
second_title: Aspose.Slides for Java API リファレンス
description: チャートの凡例プロパティを表します。
type: docs
url: /ja/com.aspose.slides/ilegend/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

チャートの凡例プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 他のチャート要素が凡例と重なることを許可するかどうかを決定します。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 他のチャート要素が凡例と重なることを許可するかどうかを決定します。 |
| [getPosition()](#getPosition--) | チャート上の凡例の位置を指定します。 |
| [setPosition(int value)](#setPosition-int-) | チャート上の凡例の位置を指定します。 |
| [getFormat()](#getFormat--) | 凡例のフォーマットを返します。 |
| [getEntries()](#getEntries--) | 凡例エントリを取得します。 |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

他のチャート要素が凡例と重なることを許可するかどうかを決定します。読み取り/書き込み boolean.

**戻り値:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

他のチャート要素が凡例と重なることを許可するかどうかを決定します。読み取り/書き込み boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

チャート上の凡例の位置を指定します。X、Y、Width、Heigt プロパティの Non-NaN 値はこのプロパティの効果を上書きします。読み取り/書き込み [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

チャート上の凡例の位置を指定します。X、Y、Width、Heigt プロパティの Non-NaN 値はこのプロパティの効果を上書きします。読み取り/書き込み [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

凡例のフォーマットを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

凡例エントリを取得します。読み取り専用 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)。

**戻り値:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)