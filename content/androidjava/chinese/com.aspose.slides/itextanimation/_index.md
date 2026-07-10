---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API 参考
description: 表示文本动画。
type: docs
url: /zh/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

表示文本动画。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 在当前序列的末尾添加新效果，以结束组文本动画。 |
| [getBuildType()](#getBuildType--) | 构建类型列表（例如 |
| [setBuildType(int value)](#setBuildType-int-) | 构建类型列表（例如 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 链接形状效果是否属于组（null）读/写 [IEffect](../../com.aspose.slides/ieffect)。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 链接形状效果是否属于组（null）读/写 [IEffect](../../com.aspose.slides/ieffect)。 |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

在当前序列的末尾添加新效果，以结束组文本动画。仅当文本段落的数量大于或等于该组效果的计数时才有效！

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| effectType | int | 动画效果的类型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 动画效果的子类型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的触发类型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回值：**
[IEffect](../../com.aspose.slides/ieffect) - 新效果对象 [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

文本动画的构建类型列表（例如段落 1,2,3, 同时全部）。读/写 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**返回值：**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

文本动画的构建类型列表（例如段落 1,2,3, 同时全部）。读/写 \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

链接形状效果是否属于组（null）读/写 [IEffect](../../com.aspose.slides/ieffect)。

**返回值：**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

链接形状效果是否属于组（null）读/写 [IEffect](../../com.aspose.slides/ieffect)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |