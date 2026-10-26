---
title: Blur
second_title: Aspose.Slides for Java API 参考
description: 表示对整个形状（包括其填充）应用的模糊效果。
type: docs
url: /zh/com.aspose.slides/blur/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有实现的接口:**  
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect  
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

表示对整个形状（包括其填充）应用的模糊效果。所有颜色通道（包括 alpha）都会受到影响。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或设置模糊半径。 |
| [setRadius(double value)](#setRadius-double-) | 返回或设置模糊半径。 |
| [getGrow()](#getGrow--) | 确定是否应因模糊而扩大对象的边界。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 确定是否应因模糊而扩大对象的边界。 |
| [getEffective()](#getEffective--) | 获取在应用继承后有效的模糊效果数据。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [Blur](../../com.aspose.slides/blur) 是否等于当前的 [Blur](../../com.aspose.slides/blur)。 |
| [hashCode()](#hashCode--) | 充当特定类型的哈希函数。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

返回或设置模糊半径。可读写 double。

**返回：**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

返回或设置模糊半径。可读写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

确定是否应因模糊而扩大对象的边界。true 表示边界被扩大，false 表示未扩大。可读写 boolean。

**返回：**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

确定是否应因模糊而扩大对象的边界。true 表示边界被扩大，false 表示未扩大。可读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

获取在应用继承后有效的模糊效果数据。

**返回：**  
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - 一个 [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [Blur](../../com.aspose.slides/blur) 是否等于当前的 [Blur](../../com.aspose.slides/blur)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [Blur](../../com.aspose.slides/blur)。 |

**返回：**  
boolean - 如果对象相等则返回 true；否则返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

充当特定类型的哈希函数。

**返回：**  
int - 当前对象的哈希码。