---
title: BiLevel
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种双层（黑/白）效果。
type: docs
url: /zh/com.aspose.slides/bilevel/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已实现的接口：**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

表示一种双层（黑/白）效果。亮度低于指定阈值的输入颜色将被更改为黑色。亮度大于或等于指定值的输入颜色将被设置为白色。Alpha 效果值不受此效果影响。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取应用继承后的有效双层效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的[BiLevel](../../com.aspose.slides/bilevel)是否等于当前的[BiLevel](../../com.aspose.slides/bilevel)。 |
| [hashCode()](#hashCode--) | 作为特定类型的散列函数。 |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

获取应用继承后的有效双层效果数据。

**返回：**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - 一个 [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的[BiLevel](../../com.aspose.slides/bilevel)是否等于当前的[BiLevel](../../com.aspose.slides/bilevel)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [BiLevel](../../com.aspose.slides/bilevel)。 |

**返回：**
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的散列函数。

**返回：**
int - 当前对象的散列码。