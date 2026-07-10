---
title: GrayScale
second_title: Aspose.Slides for Android via Java API 参考
description: 表示灰度效果。
type: docs
url: /zh/com.aspose.slides/grayscale/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

表示灰度效果。将所有效果颜色值转换为对应其亮度的灰色阴影。效果的 alpha（不透明度）值不受影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效灰度效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等于当前的 [GrayScale](../../com.aspose.slides/grayscale)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

获取应用继承后的有效灰度效果数据。

**返回：**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - 一个 [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等于当前的 [GrayScale](../../com.aspose.slides/grayscale)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [GrayScale](../../com.aspose.slides/grayscale)。 |

**返回：**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。