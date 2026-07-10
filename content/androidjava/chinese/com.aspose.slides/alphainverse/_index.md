---
title: AlphaInverse
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示 Alpha Inverse 效果。
type: docs
url: /zh/com.aspose.slides/alphainverse/
---
**继承：**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**  
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect  
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

表示 Alpha Inverse 效果。Alpha（不透明度）值通过从 100% 中减去来进行反转。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Alpha Inverse 效果数据。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaInverse](../../com.aspose.slides/alphainverse) 是否等于当前的 [AlphaInverse](../../com.aspose.slides/alphainverse)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

获取应用继承后的有效 Alpha Inverse 效果数据。

**返回值:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - 一个 [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaInverse](../../com.aspose.slides/alphainverse) 是否等于当前的 [AlphaInverse](../../com.aspose.slides/alphainverse)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的 [AlphaInverse](../../com.aspose.slides/alphainverse)。 |

**返回值:**
boolean - 如果对象相等则返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回值:**
int - 当前对象的哈希码。