---
title: IEffectFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示形状的效果属性。
type: docs
url: /zh/com.aspose.slides/ieffectformat/
---
**所有已实现的接口：**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

表示形状的效果属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | 如果所有效果均已禁用（如刚创建的默认 EffectFormat 对象），则返回 true。 |
| [getBlurEffect()](#getBlurEffect--) | 模糊效果。 |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | 模糊效果。 |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 填充叠加效果。 |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | 填充叠加效果。 |
| [getGlowEffect()](#getGlowEffect--) | 辉光效果。 |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | 辉光效果。 |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 内部阴影。 |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | 内部阴影。 |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 外部阴影。 |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | 外部阴影。 |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | 预设阴影。 |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | 预设阴影。 |
| [getReflectionEffect()](#getReflectionEffect--) | 反射效果。 |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | 反射效果。 |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | 柔和边缘。 |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | 柔和边缘。 |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | 设置模糊效果。 |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | 启用填充叠加效果。 |
| [enableGlowEffect()](#enableGlowEffect--) | 启用辉光效果。 |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | 启用内部阴影效果。 |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | 启用外部阴影效果。 |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | 启用预设阴影效果。 |
| [enableReflectionEffect()](#enableReflectionEffect--) | 启用反射效果。 |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | 启用柔和边缘效果。 |
| [disableBlurEffect()](#disableBlurEffect--) | 禁用模糊效果。 |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | 禁用填充叠加效果。 |
| [disableGlowEffect()](#disableGlowEffect--) | 禁用辉光效果。 |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | 禁用内部阴影效果。 |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | 禁用外部阴影效果。 |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | 禁用预设阴影效果。 |
| [disableReflectionEffect()](#disableReflectionEffect--) | 禁用反射效果。 |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | 禁用柔和边缘效果。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效效果格式化数据。 |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

如果所有效果均已禁用（如刚创建的默认 EffectFormat 对象），则返回 true。只读 boolean。

**返回：**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

模糊效果。可读写 [IBlur](../../com.aspose.slides/iblur)。

**返回：**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

模糊效果。可读写 [IBlur](../../com.aspose.slides/iblur)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

填充叠加效果。可读写 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**返回：**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

填充叠加效果。可读写 [IFillOverlay](../../com.aspose.slides/ifilloverlay)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

辉光效果。可读写 [IGlow](../../com.aspose.slides/iglow)。

**返回：**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

辉光效果。可读写 [IGlow](../../com.aspose.slides/iglow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

内部阴影。可读写 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**返回：**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

内部阴影。可读写 [IInnerShadow](../../com.aspose.slides/iinnershadow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

外部阴影。可读写 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**返回：**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

外部阴影。可读写 [IOuterShadow](../../com.aspose.slides/ioutershadow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

预设阴影。可读写 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**返回：**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

预设阴影。可读写 [IPresetShadow](../../com.aspose.slides/ipresetshadow)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

反射效果。可读写 [IReflection](../../com.aspose.slides/ireflection)。

**返回：**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

反射效果。可读写 [IReflection](../../com.aspose.slides/ireflection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

柔和边缘。可读写 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**返回：**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

柔和边缘。可读写 [ISoftEdge](../../com.aspose.slides/isoftedge)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

设置模糊效果。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| radius | double | 半径。 |
| grow | boolean | 增长。 |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

启用填充叠加效果。

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

启用辉光效果。

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

启用内部阴影效果。

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

启用外部阴影效果。

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

启用预设阴影效果。

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

启用反射效果。

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

启用柔和边缘效果。

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

禁用模糊效果。

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

禁用填充叠加效果。

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

禁用辉光效果。

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

禁用内部阴影效果。

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

禁用外部阴影效果。

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

禁用预设阴影效果。

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

禁用反射效果。

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

禁用柔和边缘效果。

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

获取已应用继承的有效效果格式化数据。

**返回：**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).