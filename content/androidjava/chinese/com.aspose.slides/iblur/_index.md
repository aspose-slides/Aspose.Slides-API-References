---
title: IBlur
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示应用于整个形状（包括填充）的模糊效果。
type: docs
url: /zh/com.aspose.slides/iblur/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

表示应用于整个形状（包括填充）的模糊效果。所有颜色通道，包括 alpha，都会受到影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 返回或设置模糊半径。 |
| [setRadius(double value)](#setRadius-double-) | 返回或设置模糊半径。 |
| [getGrow()](#getGrow--) | 确定是否应因模糊而扩大对象的边界。True 表示边界会扩大，false 表示不会。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 确定是否应因模糊而扩大对象的边界。True 表示边界会扩大，false 表示不会。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

返回或设置模糊半径。读/写 double.

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

返回或设置模糊半径。读/写 double.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

确定是否应因模糊而扩大对象的边界。True 表示边界会扩大，false 表示不会。读/写 boolean.

**返回：**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

确定是否应因模糊而扩大对象的边界。True 表示边界会扩大，false 表示不会。读/写 boolean.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |