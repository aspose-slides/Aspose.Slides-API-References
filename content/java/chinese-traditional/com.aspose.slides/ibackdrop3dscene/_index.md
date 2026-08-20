---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API 參考
description: 定義一個平面，在此平面上根據所套用的形狀應用發光與陰影等效果。
type: docs
url: /zh-hant/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

定義一個平面，在此平面上根據所套用的形狀應用發光與陰影等效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

返回或設定法向量。更精確地說，此屬性定義了與背景平面表面垂直的向量。向量以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

返回或設定法向量。更精確地說，此屬性定義了與背景平面表面垂直的向量。向量以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

返回或設定 3D 空間中的點。此點為錨定背景平面的空間點。3D 點以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

返回或設定 3D 空間中的點。此點為錨定背景平面的空間點。3D 點以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

返回或設定向上向量。更精確地說，此屬性定義了相對於背景平面表面的向上向量。向量以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

返回或設定向上向量。更精確地說，此屬性定義了相對於背景平面表面的向上向量。向量以包含 X、Y、Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |