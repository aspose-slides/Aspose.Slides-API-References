---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，表示颜色更改效果。
type: docs
url: /zh/com.aspose.slides/icolorchangeeffectivedata/
---
**所有实现的接口:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

不可变对象，表示颜色更改效果。FromColor 的实例将被 ToColor 的实例替换。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 将被替换的颜色。 |
| [getToColor()](#getToColor--) | 将要替换的颜色。 |
| [getUseAlpha()](#getUseAlpha--) | 返回一个 boolean 值，用于判断是否应使用 alpha 组件。 |

### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```

将被替换的颜色。只读 java.awt.Color。

**返回值:**  
java.awt.Color

### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```

将用于替换的颜色。只读 java.awt.Color。

**返回值:**  
java.awt.Color

### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```

返回一个 boolean 值，用于判断是否应使用 alpha 组件。只读 boolean。

**返回值:**  
boolean