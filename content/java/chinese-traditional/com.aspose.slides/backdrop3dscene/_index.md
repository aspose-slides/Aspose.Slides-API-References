---
title: Backdrop3DScene
second_title: Aspose.Slides for Java API 參考
description: 定義一個平面，於該平面上套用的效果（例如發光與陰影）會相對於其所套用的形狀進行。
type: docs
url: /zh-hant/com.aspose.slides/backdrop3dscene/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

定義一個平面，於該平面上套用的效果（例如發光與陰影）會相對於其所套用的形狀進行。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 傳回或設定法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 傳回或設定法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 傳回或設定 3D 空間中的點。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 傳回或設定 3D 空間中的點。 |
| [getUpVector()](#getUpVector--) | 傳回或設定代表向上的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 傳回或設定代表向上的向量。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

傳回或設定法向量。更精確地說，此屬性定義了與背景平面面向垂直的向量。向量以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**傳回:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

傳回或設定法向量。更精確地說，此屬性定義了與背景平面面向垂直的向量。向量以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

傳回或設定 3D 空間中的點。此點是定位背景平面的空間點。3D 點以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**傳回:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

傳回或設定 3D 空間中的點。此點是定位背景平面的空間點。3D 點以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

傳回或設定代表向上的向量。更精確地說，此屬性定義了相對於背景平面面向的向上向量。向量以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**傳回:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

傳回或設定代表向上的向量。更精確地說，此屬性定義了相對於背景平面面向的向上向量。向量以由 3 個 float 值組成的陣列表示，這些值定義 X、Y 和 Z 座標。讀寫 float[]。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float[] |  |