---
title: HSL
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种色相/饱和度/亮度效果。
type: docs
url: /zh/com.aspose.slides/hsl/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

表示一种色相/饱和度/亮度效果。色相、饱和度和亮度可以相对于其当前值进行调整。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效色相/饱和度/亮度效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的[HSL](../../com.aspose.slides/hsl)是否等于当前的[HSL](../../com.aspose.slides/hsl)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

获取应用继承后的有效色相/饱和度/亮度效果数据。

**返回：**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - 一个[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的[HSL](../../com.aspose.slides/hsl)是否等于当前的[HSL](../../com.aspose.slides/hsl)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的[HSL](../../com.aspose.slides/hsl)。 |

**返回：**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。