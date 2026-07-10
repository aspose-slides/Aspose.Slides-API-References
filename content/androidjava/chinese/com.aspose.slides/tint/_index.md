---
title: Tint
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示一种 Tint 效果。
type: docs
url: /zh/com.aspose.slides/tint/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.ITint](../../com.aspose.slides/itint), com.aspose.slides.IVisualEffect
```
public final class Tint extends ImageTransformOperation implements ITint, IVisualEffect
```

表示一种 Tint 效果。通过指定的量将效果颜色值向色相移动或远离色相。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Tint 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [Tint](../../com.aspose.slides/tint) 是否等于当前的 [Tint](../../com.aspose.slides/tint)。 |
| [hashCode()](#hashCode--) | 为特定类型提供哈希函数。 |
### getEffective() {#getEffective--}
```
public final ITintEffectiveData getEffective()
```

获取应用继承后的有效 Tint 效果数据。

**返回值：**
[ITintEffectiveData](../../com.aspose.slides/itinteffectivedata) - 一个 [ITintEffectiveData](../../com.aspose.slides/itinteffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [Tint](../../com.aspose.slides/tint) 是否等于当前的 [Tint](../../com.aspose.slides/tint)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [Tint](../../com.aspose.slides/tint)。 |

**返回值：**
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

为特定类型提供哈希函数。

**返回值：**
int - 当前对象的哈希码。