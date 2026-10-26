---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變物件，包含有效的效果格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ieffectformateffectivedata/
---
**已實作的介面：**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

不可變物件，包含有效的效果格式屬性。

--------------------

此介面與 [IEffectFormat](../../com.aspose.slides/ieffectformat) 介面一起使用，以回傳套用繼承的有效格式化值。

## 方法

| 方法 | 描述 |
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

如果所有效果皆已停用，則傳回 true（如剛建立的預設 EffectFormat 物件）。唯讀 boolean。

**返回：**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

模糊效果。唯讀 [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)。

**返回：**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

填充覆蓋效果。唯讀 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

**返回：**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

發光效果。唯讀 [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)。

**返回：**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

內部陰影。唯讀 [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)。

**返回：**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

外部陰影。唯讀 [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。

**返回：**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

預設陰影。唯讀 [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)。

**返回：**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

反射效果。唯讀 [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)。

**返回：**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

柔和邊緣。唯讀 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)。

**返回：**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)