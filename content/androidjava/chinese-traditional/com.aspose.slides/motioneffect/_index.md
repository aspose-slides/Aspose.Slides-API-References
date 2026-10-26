---
title: MotionEffect
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示效果的運動效果行為。
type: docs
url: /zh-hant/com.aspose.slides/motioneffect/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**已實作的所有介面：**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

表示效果的運動效果行為。
## 建構式

| 建構式 | 描述 |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定動畫起始的 x/y 座標（以百分比表示）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定動畫起始的 x/y 座標（以百分比表示）。 |
| [getTo()](#getTo--) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述動畫的相對位移值（以百分比表示）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述動畫的相對位移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用於將運動路徑繞 X 角度旋轉的旋轉中心。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | 描述用於將運動路徑繞 X 角度旋轉的旋轉中心。 |
| [getOrigin()](#getOrigin--) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。 |
| [getPath()](#getPath--) | 指定動畫運動的路徑原語及其座標。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定動畫運動的路徑原語及其座標。 |
| [getPathEditMode()](#getPathEditMode--) | 指定當形狀移動時，運動路徑的移動方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定當形狀移動時，運動路徑的移動方式。 |
| [getAngle()](#getAngle--) | 描述運動路徑的相對角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述運動路徑的相對角度。 |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```


### getFrom() {#getFrom--}
```
public final PointF getFrom()
```


指定動畫起始的 x/y 座標（以百分比表示）。讀寫 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```


指定動畫起始的 x/y 座標（以百分比表示）。讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```


指定動畫運動效果的目標位置（以百分比表示）。讀寫 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```


指定動畫運動效果的目標位置（以百分比表示）。讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```


描述動畫的相對位移值（以百分比表示）。讀寫 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```


描述動畫的相對位移值（以百分比表示）。讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```


描述用於將運動路徑繞 X 角度旋轉的旋轉中心。讀寫 android.graphics.PointF。

**返回：**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```


描述用於將運動路徑繞 X 角度旋轉的旋轉中心。讀寫 android.graphics.PointF。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```


指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。讀寫 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**返回：**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```


指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。讀寫 [MotionOriginType](../../com.aspose.slides/motionorigintype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```


指定動畫運動的路徑原語及其座標。讀寫 [IMotionPath](../../com.aspose.slides/imotionpath)。

**返回：**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```


指定動畫運動的路徑原語及其座標。讀寫 [IMotionPath](../../com.aspose.slides/imotionpath)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```


指定當形狀移動時，運動路徑的移動方式。讀寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**返回：**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```


指定當形狀移動時，運動路徑的移動方式。讀寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


描述運動路徑的相對角度。讀寫 float。

**返回：**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


描述運動路徑的相對角度。讀寫 float。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |