---
title: IEffectFormat
second_title: Aspose.Slides for Java API 參考
description: 表示形狀的效果屬性。
type: docs
url: /zh-hant/com.aspose.slides/ieffectformat/
---
**所有已實作的介面：**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

表示形狀的效果屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returns true if all effects are disabled (as just created, default EffectFormat object). |
| [getBlurEffect()](#getBlurEffect--) | Blur effect. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | Blur effect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Fill overlay effect. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | Fill overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Glow effect. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | Glow effect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inner shadow. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | Inner shadow. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Outer shadow. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | Outer shadow. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Preset shadow. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | Preset shadow. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflection. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | Reflection. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Soft edge. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | Soft edge. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | Sets blur effect. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | Enables fill overlay effect. |
| [enableGlowEffect()](#enableGlowEffect--) | Enables glow effect. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | Enables inner shadow effect. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | Enables outer shadow effect. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | Enables preset shadows effect. |
| [enableReflectionEffect()](#enableReflectionEffect--) | Enables reflection effect. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | Enables soft edge effect. |
| [disableBlurEffect()](#disableBlurEffect--) | Disables blur effect. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | Disables fill overlay effect. |
| [disableGlowEffect()](#disableGlowEffect--) | Disable glow effect. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | Disables inner shadow effect. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | Disables outer shadow effect. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | Disables preset shadow effect. |
| [disableReflectionEffect()](#disableReflectionEffect--) | Disables reflection effect. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | Disables soft edge effect. |
| [getEffective()](#getEffective--) | Gets effective effect formatting data with the inheritance applied. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

返回 true 表示所有效果皆已停用（如同剛建立的預設 EffectFormat 物件）。唯讀布林值。

**返回：**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

Blur effect. 讀寫 [IBlur](../../com.aspose.slides/iblur)。

**返回：**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

Blur effect. 讀寫 [IBlur](../../com.aspose.slides/iblur)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

Fill overlay effect. 讀寫 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

Fill overlay effect. 讀寫 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

Glow effect. 讀寫 [IGlow](../../com.aspose.slides/iglow)。

**返回：**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

Glow effect. 讀寫 [IGlow](../../com.aspose.slides/iglow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

Inner shadow. 讀寫 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**返回：**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

Inner shadow. 讀寫 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

Outer shadow. 讀寫 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**返回：**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

Outer shadow. 讀寫 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

Preset shadow. 讀寫 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**返回：**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

Preset shadow. 讀寫 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

Reflection. 讀寫 [IReflection](../../com.aspose.slides/ireflection)。

**返回：**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

Reflection. 讀寫 [IReflection](../../com.aspose.slides/ireflection)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

Soft edge. 讀寫 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**返回：**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

Soft edge. 讀寫 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

設定模糊效果。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| radius | double | 半徑。 |
| grow | boolean | 增長。 |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

啟用填充覆蓋效果。

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

啟用發光效果。

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

啟用內部陰影效果。

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

啟用外部陰影效果。

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

啟用預設陰影效果。

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

啟用反射效果。

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

啟用柔化邊緣效果。

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

停用模糊效果。

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

停用填充覆蓋效果。

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

停用發光效果。

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

停用內部陰影效果。

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

停用外部陰影效果。

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

停用預設陰影效果。

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

停用反射效果。

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

停用柔化邊緣效果。

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

取得套用繼承後的有效效果格式化資料。

**返回：**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).