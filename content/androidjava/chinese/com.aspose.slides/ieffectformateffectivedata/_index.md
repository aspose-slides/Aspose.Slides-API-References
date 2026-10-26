---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 不可变对象，包含有效的效果格式属性。
type: docs
url: /zh/com.aspose.slides/ieffectformateffectivedata/
---
**全部实现的接口:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

不可变对象，包含有效的效果格式属性。

--------------------

此接口与 [IEffectFormat](../../com.aspose.slides/ieffectformat) 接口一起使用，以返回在继承应用后的有效格式化值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | 如果所有效果均已禁用（如刚创建的默认 EffectFormat 对象），则返回 true。 |
| [getBlurEffect()](#getBlurEffect--) | 模糊效果。 |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 填充叠加效果。 |
| [getGlowEffect()](#getGlowEffect--) | 辉光效果。 |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 内部阴影。 |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 外部阴影。 |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | 预设阴影。 |
| [getReflectionEffect()](#getReflectionEffect--) | 反射。 |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | 柔边。 |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

如果所有效果均已禁用（如刚创建的默认 EffectFormat 对象），则返回 true。只读布尔值。

**返回：**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

模糊效果。只读 [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)。

**返回：**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

填充叠加效果。只读 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

**返回：**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

辉光效果。只读 [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)。

**返回：**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

内部阴影。只读 [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)。

**返回：**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

外部阴影。只读 [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。

**返回：**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

预设阴影。只读 [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)。

**返回：**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

反射。只读 [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)。

**返回：**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

柔边。只读 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)。

**返回：**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)