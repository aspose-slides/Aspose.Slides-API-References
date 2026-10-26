---
title: IMotionEffect
second_title: Aspose.Slides for Android 之 Java API 參考
description: 表示效果的運動效果行為。
type: docs
url: /zh-hant/com.aspose.slides/imotioneffect/
---
**所有已實作的介面：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

表示效果的運動效果行為。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定要從哪裡開始動畫的 x/y 座標（以百分比表示）。 |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | 指定要從哪裡開始動畫的 x/y 座標（以百分比表示）。 |
| [getTo()](#getTo--) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述動畫的相對偏移值（以百分比表示）。 |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | 描述動畫的相對偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用於將運動路徑繞 X 角度旋轉的旋轉中心。 |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | 描述用於將運動路徑繞 X 角度旋轉的旋轉中心。 |
| [getOrigin()](#getOrigin--) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父物件。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父物件。 |
| [getPath()](#getPath--) | 指定動畫運動的路徑基元以及後續座標。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定動畫運動的路徑基元以及後續座標。 |
| [getPathEditMode()](#getPathEditMode--) | 指定當形狀移動時，運動路徑的移動方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定當形狀移動時，運動路徑的移動方式。 |
| [getAngle()](#getAngle--) | 描述運動路徑的相對角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述運動路徑的相對角度。 |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

指定要從哪裡開始動畫的 x/y 座標（以百分比表示）。讀寫 android.graphics.PointF.

**傳回值：**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

指定要從哪裡開始動畫的 x/y 座標（以百分比表示）。讀寫 android.graphics.PointF.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

指定動畫運動效果的目標位置（以百分比表示）。讀寫 android.graphics.PointF.

**傳回值：**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

指定動畫運動效果的目標位置（以百分比表示）。讀寫 android.graphics.PointF.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

描述動畫的相對偏移值（以百分比表示）。讀寫 android.graphics.PointF.

**傳回值：**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

描述動畫的相對偏移值（以百分比表示）。讀寫 android.graphics.PointF.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

描述用於將運動路徑繞 X 角度旋轉的旋轉中心。讀寫 android.graphics.PointF.

**傳回值：**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

描述用於將運動路徑繞 X 角度旋轉的旋轉中心。讀寫 android.graphics.PointF.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

指定運動路徑的原點相對於什麼，例如投影片的版面配置或父物件。讀寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**傳回值：**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

指定運動路徑的原點相對於什麼，例如投影片的版面配置或父物件。讀寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

指定動畫運動的路徑基元以及後續座標。讀寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**傳回值：**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

指定動畫運動的路徑基元以及後續座標。讀寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

指定當形狀移動時，運動路徑的移動方式。讀寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**傳回值：**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

指定當形狀移動時，運動路徑的移動方式。讀寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

描述運動路徑的相對角度。讀寫 float.

**傳回值：**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

描述運動路徑的相對角度。讀寫 float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |