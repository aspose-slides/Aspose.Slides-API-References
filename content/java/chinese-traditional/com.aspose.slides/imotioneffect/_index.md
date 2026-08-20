---
title: IMotionEffect
second_title: Aspose.Slides for Java API 參考
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

| 方法 | 描述 |
| --- | --- |
| [getFrom()](#getFrom--) | 指定要從何處開始動畫的 x/y 坐標（以百分比表示）。 |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | 指定要從何處開始動畫的 x/y 坐標（以百分比表示）。 |
| [getTo()](#getTo--) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | 指定動畫運動效果的目標位置（以百分比表示）。 |
| [getBy()](#getBy--) | 描述動畫的相對偏移值（以百分比表示）。 |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | 描述動畫的相對偏移值（以百分比表示）。 |
| [getRotationCenter()](#getRotationCenter--) | 描述用於將運動路徑旋轉 X 角度的旋轉中心。 |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | 描述用於將運動路徑旋轉 X 角度的旋轉中心。 |
| [getOrigin()](#getOrigin--) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。 |
| [setOrigin(int value)](#setOrigin-int-) | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。 |
| [getPath()](#getPath--) | 指定路徑基元，後接動畫運動的座標。 |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | 指定路徑基元，後接動畫運動的座標。 |
| [getPathEditMode()](#getPathEditMode--) | 指定當形狀移動時，運動路徑的移動方式。 |
| [setPathEditMode(int value)](#setPathEditMode-int-) | 指定當形狀移動時，運動路徑的移動方式。 |
| [getAngle()](#getAngle--) | 描述運動路徑的相對角度。 |
| [setAngle(float value)](#setAngle-float-) | 描述運動路徑的相對角度。 |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

指定要從何處開始動畫的 x/y 坐標（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**返回：**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

指定要從何處開始動畫的 x/y 坐標（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

指定動畫運動效果的目標位置（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**返回：**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

指定動畫運動效果的目標位置（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

描述動畫的相對偏移值（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**返回：**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

描述動畫的相對偏移值（以百分比表示）。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

描述用於將運動路徑旋轉 X 角度的旋轉中心。讀/寫 java.awt.geom.Point2D.Float.

**返回：**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

描述用於將運動路徑旋轉 X 角度的旋轉中心。讀/寫 java.awt.geom.Point2D.Float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。讀/寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**返回：**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。讀/寫 [MotionOriginType](../../com.aspose.slides/motionorigintype).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

指定路徑基元，後接動畫運動的座標。讀/寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**返回：**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

指定路徑基元，後接動畫運動的座標。讀/寫 [IMotionPath](../../com.aspose.slides/imotionpath).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

指定當形狀移動時，運動路徑的移動方式。讀/寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**返回：**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

指定當形狀移動時，運動路徑的移動方式。讀/寫 [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

描述運動路徑的相對角度。讀/寫 float.

**返回：**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

描述運動路徑的相對角度。讀/寫 float.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |