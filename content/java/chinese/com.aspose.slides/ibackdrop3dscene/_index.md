---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: 定义一个平面，在该平面上相对于被应用的形状，应用诸如辉光和阴影等效果。
type: docs
url: /zh/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

定义一个平面，在该平面上相对于被应用的形状，应用诸如辉光和阴影等效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 返回或设置法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 返回或设置法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 返回或设置3D空间中的点。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 返回或设置3D空间中的点。 |
| [getUpVector()](#getUpVector--) | 返回或设置表示上向的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 返回或设置表示上向的向量。 |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

返回或设置法向量。更准确地说，此属性定义了一个与背景平面面相垂直的向量。向量由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

返回或设置法向量。更准确地说，此属性定义了一个与背景平面面相垂直的向量。向量由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

返回或设置3D空间中的点。此点是锚定背景平面的空间点。3D 点由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

返回或设置3D空间中的点。此点是锚定背景平面的空间点。3D 点由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

返回或设置表示上向的向量。更准确地说，此属性定义了相对于背景平面面的上向向量。向量由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

返回或设置表示上向的向量。更准确地说，此属性定义了相对于背景平面面的上向向量。向量由定义 X、Y 和 Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |