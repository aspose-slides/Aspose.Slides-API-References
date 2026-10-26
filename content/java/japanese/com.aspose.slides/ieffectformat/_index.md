---
title: IEffectFormat
second_title: Aspose.Slides for Java API リファレンス
description: シェイプのエフェクトプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ieffectformat/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

シェイプのエフェクトプロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | すべてのエフェクトが無効になっている場合に true を返します（作成直後のデフォルト EffectFormat オブジェクトの場合）。 |
| [getBlurEffect()](#getBlurEffect--) | ぼかしエフェクト。 |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ぼかしエフェクト。 |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクト。 |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | 塗りつぶしオーバーレイエフェクト。 |
| [getGlowEffect()](#getGlowEffect--) | 発光エフェクト。 |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | 発光エフェクト。 |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 内部シャドウ。 |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | 内部シャドウ。 |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 外部シャドウ。 |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | 外部シャドウ。 |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | プリセットシャドウ。 |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | プリセットシャドウ。 |
| [getReflectionEffect()](#getReflectionEffect--) | 反射。 |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | 反射。 |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ソフトエッジ。 |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | ソフトエッジ。 |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ぼかしエフェクトを設定します。 |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクトを有効にします。 |
| [enableGlowEffect()](#enableGlowEffect--) | 発光エフェクトを有効にします。 |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | 内部シャドウエフェクトを有効にします。 |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | 外部シャドウエフェクトを有効にします。 |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | プリセットシャドウエフェクトを有効にします。 |
| [enableReflectionEffect()](#enableReflectionEffect--) | 反射エフェクトを有効にします。 |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | ソフトエッジエフェクトを有効にします。 |
| [disableBlurEffect()](#disableBlurEffect--) | ぼかしエフェクトを無効にします。 |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクトを無効にします。 |
| [disableGlowEffect()](#disableGlowEffect--) | 発光エフェクトを無効にします。 |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | 内部シャドウエフェクトを無効にします。 |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | 外部シャドウエフェクトを無効にします。 |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | プリセットシャドウエフェクトを無効にします。 |
| [disableReflectionEffect()](#disableReflectionEffect--) | 反射エフェクトを無効にします。 |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | ソフトエッジエフェクトを無効にします。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なエフェクト書式設定データを取得します。 |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

すべてのエフェクトが無効になっている場合に true を返します（作成直後のデフォルト EffectFormat オブジェクトの場合）。読み取り専用の boolean。

**戻り値:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

ぼかしエフェクト。読み書き可能 [IBlur](../../com.aspose.slides/iblur)。

**戻り値:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

ぼかしエフェクト。読み書き可能 [IBlur](../../com.aspose.slides/iblur)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクト。読み書き可能 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**戻り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

塗りつぶしオーバーレイエフェクト。読み書き可能 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

発光エフェクト。読み書き可能 [IGlow](../../com.aspose.slides/iglow)。

**戻り値:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

発光エフェクト。読み書き可能 [IGlow](../../com.aspose.slides/iglow)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

内部シャドウ。読み書き可能 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**戻り値:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

内部シャドウ。読み書き可能 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

外部シャドウ。読み書き可能 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**戻り値:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

外部シャドウ。読み書き可能 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

プリセットシャドウ。読み書き可能 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**戻り値:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

プリセットシャドウ。読み書き可能 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

反射。読み書き可能 [IReflection](../../com.aspose.slides/ireflection)。

**戻り値:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

反射。読み書き可能 [IReflection](../../com.aspose.slides/ireflection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

ソフトエッジ。読み書き可能 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**戻り値:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

ソフトエッジ。読み書き可能 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

ぼかしエフェクトを設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 拡大。 |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクトを有効にします。
### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

発光エフェクトを有効にします。
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

内部シャドウエフェクトを有効にします。
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

外部シャドウエフェクトを有効にします。
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

プリセットシャドウエフェクトを有効にします。
### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

反射エフェクトを有効にします。
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

ソフトエッジエフェクトを有効にします。
### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

ぼかしエフェクトを無効にします。
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクトを無効にします。
### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

発光エフェクトを無効にします。
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

内部シャドウエフェクトを無効にします。
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

外部シャドウエフェクトを無効にします。
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

プリセットシャドウエフェクトを無効にします。
### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

反射エフェクトを無効にします。
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

ソフトエッジエフェクトを無効にします。
### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

継承が適用された有効なエフェクト書式設定データを取得します。

**戻り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) の。