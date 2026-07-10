---
title: IColorChangeEffectiveData
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示颜色变换效果的不可变对象。
type: docs
url: /zh/com.aspose.slides/icolorchangeeffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

不可变对象，表示颜色变换效果。FromColor 的实例将被 ToColor 的实例替换。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color which will be replaced. |
| [getToColor()](#getToColor--) | Color which will replace. |
| [getUseAlpha()](#getUseAlpha--) | Returns a boolean value which determines if alpha component should be used. |
### getFromColor() {#getFromColor--}
```
public abstract Integer getFromColor()
```

将被替换的颜色。只读 java.lang.Integer.

**返回：**
java.lang.Integer
### getToColor() {#getToColor--}
```
public abstract Integer getToColor()
```

将替换的颜色。只读 java.lang.Integer.

**返回：**
java.lang.Integer
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```

返回一个布尔值，决定是否应使用 alpha 组件。只读 boolean.

**返回：**
boolean