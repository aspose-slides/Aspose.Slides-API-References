---
title: IEffectFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示形狀的效果屬性。
type: docs
url: /zh-hant/com.aspose.slides/ieffectformat/
---
**所有已實作的介面:**  
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

表示形狀的效果屬性。

## 方法

| 方法 | 描述 |
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

### isNoEffects() {#isNoEffects--}}
```
public abstract boolean isNoEffects()
```

如果所有效果皆已停用（剛建立時的預設 EffectFormat 物件），則回傳 true。唯讀 boolean。

**回傳：**  
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

模糊效果。讀/寫 [IBlur](../../com.aspose.slides/iblur)。

**回傳：**  
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

模糊效果。讀/寫 [IBlur](../../com.aspose.slides/iblur)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

填充覆疊效果。讀/寫 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**回傳：**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

填充覆疊效果。讀/寫 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

發光效果。讀/寫 [IGlow](../../com.aspose.slides/iglow)。

**回傳：**  
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

發光效果。讀/寫 [IGlow](../../com.aspose.slides/iglow)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

內部陰影。讀/寫 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**回傳：**  
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

內部陰影。讀/寫 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

外部陰影。讀/寫 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**回傳：**  
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

外部陰影。讀/寫 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

預設陰影。讀/寫 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**回傳：**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

預設陰影。讀/寫 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

反射。讀/寫 [IReflection](../../com.aspose.slides/ireflection)。

**回傳：**  
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

反射。讀/寫 [IReflection](../../com.aspose.slides/ireflection)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

柔和邊緣。讀/寫 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**回傳：**  
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

柔和邊緣。讀/寫 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

設定模糊效果。

**參數：**  
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| radius | double | 半徑。 |
| grow | boolean | 增長。 |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

啟用填充覆疊效果。

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

啟用柔和邊緣效果。

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

停用模糊效果。

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

停用填充覆疊效果。

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

停用柔和邊緣效果。

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

取得套用繼承後的有效效果格式資料。

**回傳：**  
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).