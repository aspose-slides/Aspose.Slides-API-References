---
title: Backdrop3DScene
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 定義一個平面，將發光與陰影等效果相對於所套用的形狀加以應用。
type: docs
url: /zh-hant/com.aspose.slides/backdrop3dscene/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作介面:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

定義一個平面，將發光與陰影等效果相對於其所套用的形狀應用於此平面上。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | 返回或設定法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 返回或設定法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 返回或設定 3D 空間中的點。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 返回或設定 3D 空間中的點。 |
| [getUpVector()](#getUpVector--) | 返回或設定表示向上的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 返回或設定表示向上的向量。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

返回或設定法向量。更精確地說，此屬性定義與背景平面表面垂直的向量。向量以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**返回:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

返回或設定法向量。更精確地說，此屬性定義與背景平面表面垂直的向量。向量以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

返回或設定 3D 空間中的點。此點是錨定背景平面的空間點。3D 點以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**返回:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

返回或設定 3D 空間中的點。此點是錨定背景平面的空間點。3D 點以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

返回或設定表示向上的向量。更精確地說，此屬性定義相對於背景平面表面的向上向量。向量以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**返回:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

返回或設定表示向上的向量。更精確地說，此屬性定義相對於背景平面表面的向上向量。向量以 3 個 float 值的陣列表示，分別定義 X、Y 與 Z 座標。可讀寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |