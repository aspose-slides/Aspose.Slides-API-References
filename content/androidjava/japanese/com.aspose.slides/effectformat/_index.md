---
title: EffectFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: シェイプのエフェクトプロパティを表します。
type: docs
url: /ja/com.aspose.slides/effectformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**すべての実装インターフェイス:**  
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

シェイプのエフェクトプロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | すべてのエフェクトが無効になっている場合に true を返します (作成直後のデフォルト EffectFormat オブジェクトの場合)。 |
| [getBlurEffect()](#getBlurEffect--) | ぼかしエフェクト。 |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | ぼかしエフェクト。 |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクト。 |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | 塗りつぶしオーバーレイエフェクト。 |
| [getGlowEffect()](#getGlowEffect--) | グロウエフェクト。 |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | グロウエフェクト。 |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | インナーシャドウ。 |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | インナーシャドウ。 |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | アウトシャドウ。 |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | アウトシャドウ。 |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | プリセットシャドウ。 |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | プリセットシャドウ。 |
| [getReflectionEffect()](#getReflectionEffect--) | リフレクション。 |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | リフレクション。 |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ソフトエッジ。 |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | ソフトエッジ。 |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ぼかしエフェクトを設定します。 |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクトを有効にします。 |
| [enableGlowEffect()](#enableGlowEffect--) | グロウエフェクトを有効にします。 |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | インナーシャドウエフェクトを有効にします。 |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | アウトシャドウエフェクトを有効にします。 |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | プリセットシャドウエフェクトを有効にします。 |
| [enableReflectionEffect()](#enableReflectionEffect--) | リフレクションエフェクトを有効にします。 |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | ソフトエッジエフェクトを有効にします。 |
| [disableBlurEffect()](#disableBlurEffect--) | ぼかしエフェクトを無効にします。 |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | 塗りつぶしオーバーレイエフェクトを無効にします。 |
| [disableGlowEffect()](#disableGlowEffect--) | グロウエフェクトを無効にします。 |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | インナーシャドウエフェクトを無効にします。 |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | アウトシャドウエフェクトを無効にします。 |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | プリセットシャドウエフェクトを無効にします。 |
| [disableReflectionEffect()](#disableReflectionEffect--) | リフレクションエフェクトを無効にします。 |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | ソフトエッジエフェクトを無効にします。 |
| [getEffective()](#getEffective--) | 継承が適用された効果の書式設定データを取得します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**  
long

### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

すべてのエフェクトが無効になっている場合に true を返します (作成直後のデフォルト EffectFormat オブジェクトの場合)。読み取り専用 boolean 。

**戻り値:**  
boolean

### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

ぼかしエフェクト。読み書き [IBlur](../../com.aspose.slides/iblur)。

**戻り値:**  
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

ぼかしエフェクト。読み書き [IBlur](../../com.aspose.slides/iblur)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクト。読み書き [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**戻り値:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

塗りつぶしオーバーレイエフェクト。読み書き [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

グロウエフェクト。読み書き [IGlow](../../com.aspose.slides/iglow)。

**戻り値:**  
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

グロウエフェクト。読み書き [IGlow](../../com.aspose.slides/iglow)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

インナーシャドウ。読み書き [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**戻り値:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

インナーシャドウ。読み書き [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

アウトシャドウ。読み書き [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**戻り値:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

アウトシャドウ。読み書き [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

プリセットシャドウ。読み書き [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**戻り値:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

プリセットシャドウ。読み書き [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

リフレクション。読み書き [IReflection](../../com.aspose.slides/ireflection)。

**戻り値:**  
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

リフレクション。読み書き [IReflection](../../com.aspose.slides/ireflection)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

ソフトエッジ。読み書き [ISoftEdge](../../com.aspose.slides/isoftedge)。

**戻り値:**  
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

ソフトエッジ。読み書き [ISoftEdge](../../com.aspose.slides/isoftedge)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

ぼかしエフェクトを設定します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 拡大。 |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクトを有効にします。

### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

グロウエフェクトを有効にします。

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

インナーシャドウエフェクトを有効にします。

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

アウトシャドウエフェクトを有効にします。

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

プリセットシャドウエフェクトを有効にします。

### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

リフレクションエフェクトを有効にします。

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

ソフトエッジエフェクトを有効にします。

### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

ぼかしエフェクトを無効にします。

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

塗りつぶしオーバーレイエフェクトを無効にします。

### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

グロウエフェクトを無効にします。

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

インナーシャドウエフェクトを無効にします。

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

アウトシャドウエフェクトを無効にします。

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

プリセットシャドウエフェクトを無効にします。

### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

リフレクションエフェクトを無効にします。

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

ソフトエッジエフェクトを無効にします。

### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

継承が適用された効果の書式設定データを取得します。

--------------------

> ```
> This example demonstrates getting some of shape's effective effect properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
>  	else
>  	{
>  		if (effectiveEffectFormat.getBlurEffect() != null)
>  			System.out.println("Blur effect radius: " + effectiveEffectFormat.getBlurEffect().getRadius());
>  		if (effectiveEffectFormat.getFillOverlayEffect() != null)
>  			System.out.println("Fill overlay effect fill type: " + effectiveEffectFormat.getFillOverlayEffect().getFillFormat().getFillType());
>  		if (effectiveEffectFormat.getGlowEffect() != null)
>  			System.out.println("Glow effect color: " + effectiveEffectFormat.getGlowEffect().getColor());
>  		if (effectiveEffectFormat.getInnerShadowEffect() != null)
>  			System.out.println("Inner shadow effect shadow color: " + effectiveEffectFormat.getInnerShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getOuterShadowEffect() != null)
>  			System.out.println("Outer shadow effect shadow color: " + effectiveEffectFormat.getOuterShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getPresetShadowEffect() != null)
>  			System.out.println("Preset shadow effect shadow color: " + effectiveEffectFormat.getPresetShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getReflectionEffect() != null)
>  			System.out.println("Reflection effect distance: " + effectiveEffectFormat.getReflectionEffect().getDistance());
>  		if (effectiveEffectFormat.getSoftEdgeEffect() != null)
>  			System.out.println("Soft edge effect radius: " + effectiveEffectFormat.getSoftEdgeEffect().getRadius());
>  	}
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).