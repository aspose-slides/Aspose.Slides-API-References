---
title: IEffectFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: シェイプのエフェクトプロパティを表します。
type: docs
url: /ja/com.aspose.slides/ieffectformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

シェイプのエフェクトプロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | すべてのエフェクトが無効になっている場合に true を返します (作成直後のデフォルト EffectFormat オブジェクトと同様)。 |
| [getBlurEffect()](#getBlurEffect--) | ぼかし効果。 |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ぼかし効果。 |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 塗りつぶしオーバーレイ効果。 |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | 塗りつぶしオーバーレイ効果。 |
| [getGlowEffect()](#getGlowEffect--) | グロウ効果。 |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | グロウ効果。 |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 内部シャドウ。 |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | 内部シャドウ。 |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 外部シャドウ。 |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | 外部シャドウ。 |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | プリセットシャドウ。 |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | プリセットシャドウ。 |
| [getReflectionEffect()](#getReflectionEffect--) | 反射効果。 |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | 反射効果。 |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ソフトエッジ。 |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | ソフトエッジ。 |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ぼかし効果を設定します。 |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | 塗りつぶしオーバーレイ効果を有効にします。 |
| [enableGlowEffect()](#enableGlowEffect--) | グロウ効果を有効にします。 |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | 内部シャドウ効果を有効にします。 |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | 外部シャドウ効果を有効にします。 |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | プリセットシャドウ効果を有効にします。 |
| [enableReflectionEffect()](#enableReflectionEffect--) | 反射効果を有効にします。 |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | ソフトエッジ効果を有効にします。 |
| [disableBlurEffect()](#disableBlurEffect--) | ぼかし効果を無効にします。 |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | 塗りつぶしオーバーレイ効果を無効にします。 |
| [disableGlowEffect()](#disableGlowEffect--) | グロウ効果を無効にします。 |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | 内部シャドウ効果を無効にします。 |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | 外部シャドウ効果を無効にします。 |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | プリセットシャドウ効果を無効にします。 |
| [disableReflectionEffect()](#disableReflectionEffect--) | 反射効果を無効にします。 |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | ソフトエッジ効果を無効にします。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なエフェクト書式データを取得します。 |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

すべてのエフェクトが無効になっている場合に true を返します (作成直後のデフォルト EffectFormat オブジェクトと同様)。読み取り専用の boolean。

**戻り値:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

ぼかし効果。読み書き可能 [IBlur](../../com.aspose.slides/iblur)。

**戻り値:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

ぼかし効果。読み書き可能 [IBlur](../../com.aspose.slides/iblur)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

塗りつぶしオーバーレイ効果。読み書き可能 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**戻り値:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

塗りつぶしオーバーレイ効果。読み書き可能 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

グロウ効果。読み書き可能 [IGlow](../../com.aspose.slides/iglow)。

**戻り値:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

グロウ効果。読み書き可能 [IGlow](../../com.aspose.slides/iglow)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

反射効果。読み書き可能 [IReflection](../../com.aspose.slides/ireflection)。

**戻り値:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

反射効果。読み書き可能 [IReflection](../../com.aspose.slides/ireflection)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

ぼかし効果を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 拡大。 |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

塗りつぶしオーバーレイ効果を有効にします。

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

グロウ効果を有効にします。

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

内部シャドウ効果を有効にします。

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

外部シャドウ効果を有効にします。

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

プリセットシャドウ効果を有効にします。

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

反射効果を有効にします。

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

ソフトエッジ効果を有効にします。

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

ぼかし効果を無効にします。

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

塗りつぶしオーバーレイ効果を無効にします。

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

グロウ効果を無効にします。

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

内部シャドウ効果を無効にします。

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

外部シャドウ効果を無効にします。

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

プリセットシャドウ効果を無効にします。

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

反射効果を無効にします。

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

ソフトエッジ効果を無効にします。

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

継承が適用された有効なエフェクト書式データを取得します。

**戻り値:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)。