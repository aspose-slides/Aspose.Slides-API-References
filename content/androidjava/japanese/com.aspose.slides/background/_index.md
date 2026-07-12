---
title: Background
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: スライドの背景を表します。
type: docs
url: /ja/com.aspose.slides/background/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
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
| [getStyleIndex()](#getStyleIndex--) | BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションで返します。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションで返します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な背景データを取得します。 |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | シェイプの親スライドを返します。 |
| [getPresentation()](#getPresentation--) | スライドの親プレゼンテーションを返します。 |
### getType() {#getType--}
```
public final byte getType()
```

背景塗りつぶしのタイプを返します。 読み書き [BackgroundType](../../com.aspose.slides/backgroundtype)。

**戻り値:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

背景塗りつぶしのタイプを返します。 読み書き [BackgroundType](../../com.aspose.slides/backgroundtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

BackgroundType.OwnBackground 塗りつぶしの FillFormat を返します。 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground 塗りつぶしの EffectFormat を返します。 読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

BackgroundType.Themed 塗りつぶしの ColorFormat を返します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションで返します。0 は塗りつぶしなしを意味します。1..999 - インデックス。 読み書き int。

**戻り値:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

BackgroundType.Themed 塗りつぶしのインデックスを背景テーマコレクションで返します。0 は塗りつぶしなしを意味します。1..999 - インデックス。 読み書き int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

継承が適用された有効な背景データを取得します。

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long。

**戻り値:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

シェイプの親スライドを返します。 読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

スライドの親プレゼンテーションを返します。 読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[Presentation](../../com.aspose.slides/presentation)