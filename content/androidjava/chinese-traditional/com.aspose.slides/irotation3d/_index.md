---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Represents 3D rotation of a chart.
type: docs
url: /zh-hant/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

表示圖表的 3D 旋轉。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRotationX()](#getRotationX--) | 取得或設定繞 X 軸的旋轉角度，即 |
| [setRotationX(byte value)](#setRotationX-byte-) | 取得或設定繞 X 軸的旋轉角度，即 |
| [getRotationY()](#getRotationY--) | 取得或設定繞 Y 軸的旋轉角度，即 |
| [setRotationY(int value)](#setRotationY-int-) | 取得或設定繞 Y 軸的旋轉角度，即 |
| [getPerspective()](#getPerspective--) | 取得或設定 3D 圖表的透視值（視野角度），範圍在 0 到 100 之間。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 取得或設定 3D 圖表的透視值（視野角度），範圍在 0 到 100 之間。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | 判斷圖表坐標軸是否呈直角，而非以透視方式繪製。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 判斷圖表坐標軸是否呈直角，而非以透視方式繪製。 |
| [getDepthPercents()](#getDepthPercents--) | 取得或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 取得或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。 |
| [getHeightPercents()](#getHeightPercents--) | 指定 3D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 指定 3D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。 |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

取得或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（範圍為 -90 到 90 度）。此屬性對應 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的「Y Rotation」選項。讀寫 byte。

**返回：**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

取得或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（範圍為 -90 到 90 度）。此屬性對應 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的「Y Rotation」選項。讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

取得或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（範圍為 0 到 360 度）。此屬性對應 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的「X Rotation」選項。讀寫 int。

**返回：**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

取得或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（範圍為 0 到 360 度）。此屬性對應 ECMA-376 中的 21.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的「X Rotation」選項。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

取得或設定 3D 圖表的透視值（視野角度），範圍在 0 到 100 之間。如果 RightAngleAxes 屬性值為 true，則會被忽略。讀寫 byte。

**返回：**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

取得或設定 3D 圖表的透視值（視野角度），範圍在 0 到 100 之間。如果 RightAngleAxes 屬性值為 true，則會被忽略。讀寫 byte。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

判斷圖表坐標軸是否呈直角，而非以透視方式繪製。換句話說，它決定坐標軸的角度是否與圖表的旋轉或傾斜無關。讀寫 boolean。

**返回：**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

判斷圖表坐標軸是否呈直角，而非以透視方式繪製。換句話說，它決定坐標軸的角度是否與圖表的旋轉或傾斜無關。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

取得或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。讀寫 int。

**返回：**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

取得或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

指定 3D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。讀寫 int。

**返回：**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

指定 3D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |