---
title: MotionEffect
second_title: Aspose.Slides for Java API 參考文件
description: 代表效果的運動效果行為。
type: docs
url: /zh-hant/com.aspose.slides/motioneffect/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**所有已實作的介面：**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

表示效果的運動效果行為。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定動畫開始的 x/y 座標（以百分比表示）。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 指定動畫開始的 x/y 座標（以百分比表示）。 |
| [getTo()](#getTo--) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述動畫的相對偏移值（以百分比表示）。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 描述動畫的相對偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用於將運動路徑旋轉 X 角度的旋轉中心。 |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | 描述用於將運動路徑旋轉 X 角度的旋轉中心。 |
| [getOrigin()](#getOrigin--) | 指定運動路徑的原點相對於什麼，例如投影片的佈局或父項目。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定運動路徑的原點相對於什麼，例如投影片的佈局或父項目。 |
| [getPath()](#getPath--) | 指定動畫運動的路徑原語及其座標。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定動畫運動的路徑原語及其座標。 |
| [getPathEditMode()](#getPathEditMode--) | 指定當形狀移動時運動路徑的移動方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定當形狀移動時運動路徑的移動方式。 |
| [getAngle()](#getAngle--) | 描述運動路徑的相對角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述運動路徑的相對角度。 |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```


指定動畫開始的 x/y 座標（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**傳回：**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```


指定動畫開始的 x/y 座標（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```


指定動畫運動效果的目標位置（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**傳回：**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```


指定動畫運動效果的目標位置（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```


描述動畫的相對偏移值（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**傳回：**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```


描述動畫的相對偏移值（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```


描述用於將運動路徑旋轉 X 角度的旋轉中心。讀/寫 java.awt.geom.Point2D.Float.

**傳回：**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```


描述用於將運動路徑旋轉 X 角度的旋轉中心。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


指定運動路徑的原點相對於什麼，例如投影片的佈局或父項目。讀/寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**傳回：**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


指定運動路徑的原點相對於什麼，例如投影片的佈局或父項目。讀/寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


指定動畫運動的路徑原語及其座標。讀/寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**傳回：**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


指定動畫運動的路徑原語及其座標。讀/寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


指定當形狀移動時運動路徑的移動方式。讀/寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**傳回：**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


指定當形狀移動時運動路徑的移動方式。讀/寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


描述運動路徑的相對角度。讀/寫 float.

**傳回：**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


描述運動路徑的相對角度。讀/寫 float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |