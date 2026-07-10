---
title: ISoftEdge
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示软边缘效果。
type: docs
url: /zh/com.aspose.slides/isoftedge/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface ISoftEdge extends IImageTransformOperation, IAccessiblePVIObject<ISoftEdgeEffectiveData>
```

表示 Soft Edge 效果。形状的边缘被模糊，而填充不受影响。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 指定要应用于边缘的模糊半径。 |
| [setRadius(double value)](#setRadius-double-) | 指定要应用于边缘的模糊半径。 |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

指定要应用于边缘的模糊半径。读/写 double.

**返回：**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

指定要应用于边缘的模糊半径。读/写 double.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |