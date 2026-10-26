---
title: AlphaModulateFixed
second_title: Aspose.Slides Java API 参考
description: 表示 Alpha Modulate Fixed 效果。
type: docs
url: /zh/com.aspose.slides/alphamodulatefixed/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口：**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

表示 Alpha Modulate Fixed 效果。效果 alpha（不透明度）值乘以固定百分比。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAmount()](#getAmount--) | 返回效果的百分比量。 |
| [setAmount(float value)](#setAmount-float-) | 返回效果的百分比量。 |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效 Alpha Modulate Fixed 效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等于当前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |
| [hashCode()](#hashCode--) | 用作特定类型的哈希函数。 |
### getAmount() {#getAmount--}
```
public final float getAmount()
```

返回效果的百分比量。读/写 float.

**返回：**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

返回效果的百分比量。读/写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

获取在应用继承后的有效 Alpha Modulate Fixed 效果数据。

**返回：**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - 一个 [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等于当前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |

**返回：**
boolean - 若对象相等则为 true；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

用作特定类型的哈希函数。

**返回：**
int - 当前对象的哈希码。