---
title: AlphaModulateFixed
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示 Alpha Modulate Fixed 效果。
type: docs
url: /zh/com.aspose.slides/alphamodulatefixed/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口:**  
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect  
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

表示 Alpha Modulate Fixed 效果。效果的 Alpha（不透明度）值会乘以固定的百分比。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAmount()](#getAmount--) | Returns an amount of effect in percents. |
| [setAmount(float value)](#setAmount-float-) | Returns an amount of effect in percents. |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate Fixed effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) is equal to the current [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getAmount() {#getAmount--}
```
public final float getAmount()
```

返回效果的百分比量。 可读写 float。

**返回值：**  
float

### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```

返回效果的百分比量。 可读写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```

获取已应用继承的有效 Alpha Modulate Fixed 效果数据。

**返回值：**  
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - 一个 [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) 是否等于当前的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed)。 |

**返回值：**  
boolean - 如果对象相等返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作为特定类型的哈希函数。

**返回值：**  
int - 当前对象的哈希码。