---
title: ColorChange
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示颜色更改效果。
type: docs
url: /zh/com.aspose.slides/colorchange/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已实现的接口:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

表示一个颜色更改效果。FromColor 的实例被 ToColor 的实例替换。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 将被替换的颜色。 |
| [getToColor()](#getToColor--) | 将用于替换的颜色。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效颜色更改效果数据。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [ColorChange](../../com.aspose.slides/colorchange) 是否等于当前的 [ColorChange](../../com.aspose.slides/colorchange)。 |
| [hashCode()](#hashCode--) | 为特定类型提供散列函数。 |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

将被替换的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

用于替换的颜色。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

获取应用继承后的有效颜色更改效果数据。

**返回:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - 一个 [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [ColorChange](../../com.aspose.slides/colorchange) 是否等于当前的 [ColorChange](../../com.aspose.slides/colorchange)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [ColorChange](../../com.aspose.slides/colorchange)。 |

**返回:**
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

为特定类型提供散列函数。

**返回:**
int - 当前对象的散列码。