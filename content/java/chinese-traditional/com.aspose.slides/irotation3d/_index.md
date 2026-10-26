---
title: IRotation3D
second_title: Aspose.Slides for Java API 參考
description: 表示圖表的 3D 旋轉。
type: docs
url: /zh-hant/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

表示圖表的 3D 旋轉。
## 方法

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | 返回或設定繞 X 軸的旋轉角度，即 |
| [setRotationX(byte value)](#setRotationX-byte-) | 返回或設定繞 X 軸的旋轉角度，即 |
| [getRotationY()](#getRotationY--) | 返回或設定繞 Y 軸的旋轉角度，即 |
| [setRotationY(int value)](#setRotationY-int-) | 返回或設定繞 Y 軸的旋轉角度，即 |
| [getPerspective()](#getPerspective--) | 返回或設定 3D 圖表的透視值（視野角度），範圍 0 到 100。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 返回或設定 3D 圖表的透視值（視野角度），範圍 0 到 100。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | 判斷圖表坐標軸是否為直角，而非以透視方式繪製。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 判斷圖表坐標軸是否為直角，而非以透視方式繪製。 |
| [getDepthPercents()](#getDepthPercents--) | 返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（20% 到 2000% 之間）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（20% 到 2000% 之間）。 |
| [getHeightPercents()](#getHeightPercents--) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（5% 到 500% 之間）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（5% 到 500% 之間）。 |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

返回或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度之間）。此屬性符合 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的「Y Rotation」選項。讀寫 byte。

**Returns:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

返回或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度之間）。此屬性符合 ECMA-376 中的 21.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的「Y Rotation」選項。讀寫 byte。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

返回或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度之間）。此屬性符合 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的「X Rotation」選項。讀寫 int。

**Returns:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

返回或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度之間）。此屬性符合 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的「X Rotation」選項。讀寫 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

返回或設定 3D 圖表的透視值（視野角度），範圍 0 到 100。若 RightAngleAxes 屬性為 true，則此值被忽略。讀寫 byte。

**Returns:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

返回或設定 3D 圖表的透視值（視野角度），範圍 0 到 100。若 RightAngleAxes 屬性為 true，則此值被忽略。讀寫 byte。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

判斷圖表坐標軸是否為直角，而非以透視方式繪製。換言之，此屬性決定坐標軸的角度是否獨立於圖表的旋轉或仰角。讀寫 boolean。

**Returns:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

判斷圖表坐標軸是否為直角，而非以透視方式繪製。換言之，此屬性決定坐標軸的角度是否獨立於圖表的旋轉或仰角。讀寫 boolean。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（20% 到 2000% 之間）。讀寫 int。

**Returns:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（20% 到 2000% 之間）。讀寫 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

指定 3-D 圖表的高度，以圖表寬度的百分比表示（5% 到 500% 之間）。讀寫 int。

**Returns:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

指定 3-D 圖表的高度，以圖表寬度的百分比表示（5% 到 500% 之間）。讀寫 int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |