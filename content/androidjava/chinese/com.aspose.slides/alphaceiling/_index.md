---
title: AlphaCeiling
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Alpha Ceiling 效果。
type: docs
url: /zh/com.aspose.slides/alphaceiling/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已实现的接口:**  
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect  
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

表示 Alpha Ceiling 效果。Alpha（不透明度）值大于零的将被更改为 100%。换句话说，任何部分透明的对象都将变为完全不透明。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效 Alpha Ceiling 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaCeiling](../../com.aspose.slides/alphaceiling) 是否等于当前的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。 |
| [hashCode()](#hashCode--) | 作为特定类型的哈希函数。 |

### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```

获取应用继承后的有效 Alpha Ceiling 效果数据。

**返回:**  
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - 一个 [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaCeiling](../../com.aspose.slides/alphaceiling) 是否等于当前的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaCeiling](../../com.aspose.slides/alphaceiling)。 |

**返回:**  
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回:**  
int - 当前对象的哈希码。