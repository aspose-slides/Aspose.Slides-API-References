---
title: IBackground
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライドの背景を表します。
type: docs
url: /ja/com.aspose.slides/ibackground/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

スライドの背景を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 背景塗りつぶしのタイプを返します。 |
| [setType(byte value)](#setType-byte-) | 背景塗りつぶしのタイプを返します。 |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground 塗りつぶしの FillFormat を返します。 |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground 塗りつぶしの EffectFormat を返します。 |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed 塗りつぶしの ColorFormat を返します。 |
| [getStyleIndex()](#getStyleIndex--) | 背景テーマコレクション内の BackgroundType.Themed 塗りつぶしのインデックスを返します。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 背景テーマコレクション内の BackgroundType.Themed 塗りつぶしのインデックスを返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な背景データを取得します。 |
### getType() {#getType--}
```
public abstract byte getType()
```

背景塗りつぶしのタイプを返します。 読み取り/書き込み [BackgroundType](../../com.aspose.slides/backgroundtype)。

**戻り値:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

背景塗りつぶしのタイプを返します。 読み取り/書き込み [BackgroundType](../../com.aspose.slides/backgroundtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

BackgroundType.OwnBackground 塗りつぶしの FillFormat を返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground 塗りつぶしの EffectFormat を返します。 読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

BackgroundType.Themed 塗りつぶしの ColorFormat を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションから返します。0 は塗りなしを意味します。1..999 はインデックスです。 読み取り/書き込み int。

**戻り値:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションから返します。0 は塗りなしを意味します。1..999 はインデックスです。 読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

継承が適用された有効な背景データを取得します。

**戻り値:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).