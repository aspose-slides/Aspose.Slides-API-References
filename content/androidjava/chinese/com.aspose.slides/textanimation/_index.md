---
title: TextAnimation
second_title: Aspose.Slides for Android Java API 参考
description: 表示文本动画。
type: docs
url: /zh/com.aspose.slides/textanimation/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

表示文本动画。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 将新效果添加到当前序列的末尾，以结束组文本动画。 |
| [getBuildType()](#getBuildType--) | 构建类型列表（例如 ...）。 |
| [setBuildType(int value)](#setBuildType-int-) | 构建类型列表（例如 ...）。 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | 与组关联的形状效果或不关联（null）。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | 与组关联的形状效果或不关联（null）。 |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

将新效果添加到当前序列的末尾，以结束组文本动画。仅在文本段落计数大于或等于该组效果计数时有效！

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| effectType | int | 动画效果的类型 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | 动画效果的子类型 [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | 效果的触发类型 [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**返回值：**
[IEffect](../../com.aspose.slides/ieffect) - 新的效果对象 [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

文本动画的构建类型列表（例如段落 1、2、3、一次性全部）。读/写 [BuildType](../../com.aspose.slides/buildtype)。

**返回值：**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

文本动画的构建类型列表（例如段落 1、2、3、一次性全部）。读/写 [BuildType](../../com.aspose.slides/buildtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

与组关联的形状效果或不关联（null）。读/写 [IEffect](../../com.aspose.slides/ieffect)。

**返回值：**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

与组关联的形状效果或不关联（null）。读/写 [IEffect](../../com.aspose.slides/ieffect)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |