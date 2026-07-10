---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: 定义一个平面，在该平面上，诸如辉光和阴影等效果相对于其所应用的形状进行应用。
type: docs
url: /zh/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

定义一个平面，在该平面上，诸如辉光和阴影等效果相对于其所应用的形状进行应用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 返回或设置法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 返回或设置法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 返回或设置三维空间中的点。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 返回或设置三维空间中的点。 |
| [getUpVector()](#getUpVector--) | 返回或设置表示向上的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 返回或设置表示向上的向量。 |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


返回或设置法向量。更精确地说，此属性定义一个垂直于背景平面面的向量。向量由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**返回值：**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


返回或设置法向量。更精确地说，此属性定义一个垂直于背景平面面的向量。向量由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


返回或设置三维空间中的点。此点是锚定背景平面的空间点。三维点由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**返回值：**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


返回或设置三维空间中的点。此点是锚定背景平面的空间点。三维点由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


返回或设置表示向上的向量。更精确地说，此属性定义一个相对于背景平面面的向上向量。向量由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**返回值：**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


返回或设置表示向上的向量。更精确地说，此属性定义一个相对于背景平面面的向上向量。向量由包含 X、Y 和 Z 坐标的 3 个 float 值的数组表示。可读写 float[]。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |