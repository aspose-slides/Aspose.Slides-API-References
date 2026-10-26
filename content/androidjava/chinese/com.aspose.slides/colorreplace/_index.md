---
title: ColorReplace
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一种颜色替换效果。
type: docs
url: /zh/com.aspose.slides/colorreplace/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

表示一种颜色替换效果。所有效果颜色都会更改为固定颜色。Alpha 值不受影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getColor()](#getColor--) | 返回将替换每个像素颜色的颜色格式。 |
| [getEffective()](#getEffective--) | 获取在应用继承后有效的颜色替换效果数据。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [ColorReplace](../../com.aspose.slides/colorreplace) 是否等于当前的 [ColorReplace](../../com.aspose.slides/colorreplace)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

返回将替换每个像素颜色的颜色格式。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

获取在应用继承后有效的颜色替换效果数据。

**返回：**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

确定指定的 [ColorReplace](../../com.aspose.slides/colorreplace) 是否等于当前的 [ColorReplace](../../com.aspose.slides/colorreplace)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [ColorReplace](../../com.aspose.slides/colorreplace)。 |

**返回：**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。