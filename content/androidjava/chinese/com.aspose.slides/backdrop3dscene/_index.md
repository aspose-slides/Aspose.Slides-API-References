---
title: Backdrop3DScene
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 定义一个平面，在该平面上相对于所应用形状的光晕和阴影等效果被应用。
type: docs
url: /zh/com.aspose.slides/backdrop3dscene/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

定义一个平面，在该平面上相对于所应用形状的光晕、阴影等效果被应用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 返回或设置法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 返回或设置法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 返回或设置三维空间中的点。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 返回或设置三维空间中的点。 |
| [getUpVector()](#getUpVector--) | 返回或设置表示向上的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 返回或设置表示向上的向量。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

返回或设置法向量。更准确地说，此属性定义了与背景平面面相垂直的向量。向量由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

返回或设置法向量。更准确地说，此属性定义了与背景平面面相垂直的向量。向量由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

返回或设置三维空间中的点。该点是锚定背景平面的空间点。三维点由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

返回或设置三维空间中的点。该点是锚定背景平面的空间点。三维点由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

返回或设置表示向上的向量。更准确地说，此属性定义了相对于背景平面面的向上向量。向量由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**返回:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

返回或设置表示向上的向量。更准确地说，此属性定义了相对于背景平面面的向上向量。向量由包含 X、Y、Z 坐标的 3 个 float 值的数组表示。读/写 float[]。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float[] |  |