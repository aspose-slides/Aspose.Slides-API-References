---
title: Luminance
second_title: Aspose.Slides for Java API 参考
description: 表示亮度效果。
type: docs
url: /zh/com.aspose.slides/luminance/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

表示亮度效果。亮度线性地将所有颜色向白色或黑色偏移。对比度将所有颜色缩放，使它们更接近或更远离。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效亮度效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [Luminance](../../com.aspose.slides/luminance) 是否等于当前的 [Luminance](../../com.aspose.slides/luminance)。 |
| [hashCode()](#hashCode--) | 作为特定类型的散列函数。 |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```

获取在应用继承后的有效亮度效果数据。

**返回：**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - 一个 [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [Luminance](../../com.aspose.slides/luminance) 是否等于当前的 [Luminance](../../com.aspose.slides/luminance)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [Luminance](../../com.aspose.slides/luminance)。 |

**返回：**
boolean - 如果对象相等则返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的散列函数。

**返回：**
int - 当前对象的散列码。