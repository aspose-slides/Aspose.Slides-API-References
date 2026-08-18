---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 有効なエフェクトフォーマットプロパティを含む不変オブジェクト。
type: docs
url: /ja/com.aspose.slides/ieffectformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

有効な効果フォーマットプロパティを含む不変オブジェクト。

--------------------

このインターフェイスは [IEffectFormat](../../com.aspose.slides/ieffectformat) インターフェイスと共に使用され、継承が適用された有効なフォーマット値を返します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returns true if all effects are disabled (as just created, default EffectFormat object). |
| [getBlurEffect()](#getBlurEffect--) | Blur effect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Fill overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Glow effect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inner shadow. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Outer shadow. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Preset shadow. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflection. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Soft edge. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

すべてのエフェクトが無効になっている場合に true を返します（作成直後のデフォルト EffectFormat オブジェクトの場合）。読み取り専用 boolean。

**戻り値:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

ぼかしエフェクト。読み取り専用 [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)。

**戻り値:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクト。読み取り専用 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

**戻り値:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

グロウエフェクト。読み取り専用 [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)。

**戻り値:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

インナードシャドウ。読み取り専用 [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)。

**戻り値:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

アウタードシャドウ。読み取り専用 [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。

**戻り値:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

プリセットシャドウ。読み取り専用 [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)。

**戻り値:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

リフレクション。読み取り専用 [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)。

**戻り値:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

ソフトエッジ。読み取り専用 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)。

**戻り値:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)