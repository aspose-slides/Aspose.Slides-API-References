---
title: AlphaBiLevel
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Alpha Bi-Level 效果。
type: docs
url: /zh/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

表示 Alpha Bi-Level 效果。小于阈值的 Alpha（不透明度）值将被更改为 0（完全透明），大于或等于阈值的 Alpha 值将被更改为 100%（完全不透明）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回效果阈值。 |
| [setThreshold(float value)](#setThreshold-float-) | 返回效果阈值。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Alpha Bi-Level 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel) 是否等于当前的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

返回效果阈值。可读写 float。

**返回值：**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

返回效果阈值。可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

获取应用继承后的有效 Alpha Bi-Level 效果数据。

**返回值：**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - 一个 [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel) 是否等于当前的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaBiLevel](../../com.aspose.slides/alphabilevel)。 |

**返回值：**
boolean - 如果对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回值：**
int - 当前对象的哈希码。