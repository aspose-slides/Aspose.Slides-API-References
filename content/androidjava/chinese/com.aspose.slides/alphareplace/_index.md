---
title: AlphaReplace
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示 Alpha Replace 效果。
type: docs
url: /zh/com.aspose.slides/alphareplace/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect
```
public final class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

表示 Alpha Replace 效果。效果的 alpha（不透明度）值将被固定的 alpha 替代。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取在继承应用后的有效 Alpha Replace 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaReplace](../../com.aspose.slides/alphareplace) 是否等于当前的 [AlphaReplace](../../com.aspose.slides/alphareplace)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |
### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```

获取在继承应用后的有效 Alpha Replace 效果数据。

**返回值:**
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - 一个 [IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaReplace](../../com.aspose.slides/alphareplace) 是否等于当前的 [AlphaReplace](../../com.aspose.slides/alphareplace)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaReplace](../../com.aspose.slides/alphareplace)。 |

**返回值:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回值:**
int - 当前对象的哈希码。