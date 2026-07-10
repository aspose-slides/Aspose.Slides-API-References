---
title: Duotone
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种 Duotone 效果。
type: docs
url: /zh/com.aspose.slides/duotone/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已实现的接口：**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

表示一种双音调效果。对于每个像素，通过线性插值将 Color1 和 Color2 组合，以确定该像素的新颜色。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目标颜色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目标颜色格式。 |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效 Duotone 效果数据。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [Duotone](../../com.aspose.slides/duotone) 是否等于当前的 [Duotone](../../com.aspose.slides/duotone)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

返回暗像素的目标颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

返回亮像素的目标颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

获取在应用继承后的有效 Duotone 效果数据。

**返回：**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata)。
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [Duotone](../../com.aspose.slides/duotone) 是否等于当前的 [Duotone](../../com.aspose.slides/duotone)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [Duotone](../../com.aspose.slides/duotone)。 |

**返回：**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。