---
title: AlphaModulate
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示 Alpha Modulate 效果。
type: docs
url: /zh/com.aspose.slides/alphamodulate/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

表示 Alpha Modulate 效果。效果 alpha（不透明度）值将乘以固定的百分比。效果容器指定一个包含 alpha 值以进行调制的效果。

## Methods

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Alpha Modulate 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaModulate](../../com.aspose.slides/alphamodulate) 是否等于当前的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。 |
| [hashCode()](#hashCode--) | 为特定类型提供哈希函数。 |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

获取应用继承后的有效 Alpha Modulate 效果数据。

**返回值：**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - 一个 [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaModulate](../../com.aspose.slides/alphamodulate) 是否等于当前的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。 |

**返回值：**
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

为特定类型提供哈希函数。

**返回值：**
int - 当前对象的哈希码。