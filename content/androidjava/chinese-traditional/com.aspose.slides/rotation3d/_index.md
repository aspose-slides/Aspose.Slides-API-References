---
title: Rotation3D
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖表的 3D 旋轉。
type: docs
url: /zh-hant/com.aspose.slides/rotation3d/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

表示圖表的 3D 旋轉。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRotationX()](#getRotationX--) | 返回或設定繞 X 軸的旋轉角度，即 |
| [setRotationX(byte value)](#setRotationX-byte-) | 返回或設定繞 X 軸的旋轉角度，即 |
| [getRotationY()](#getRotationY--) | 返回或設定繞 Y 軸的旋轉角度，即 |
| [setRotationY(int value)](#setRotationY-int-) | 返回或設定繞 Y 軸的旋轉角度，即 |
| [getPerspective()](#getPerspective--) | 返回或設定 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。 |
| [setPerspective(byte value)](#setPerspective-byte-) | 返回或設定 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。 |
| [getRightAngleAxes()](#getRightAngleAxes--) | 判斷圖表軸是否為直角，而非以透視方式繪製。 |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | 判斷圖表軸是否為直角，而非以透視方式繪製。 |
| [getDepthPercents()](#getDepthPercents--) | 返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。 |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。 |
| [getHeightPercents()](#getHeightPercents--) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。 |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

返回或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度之間）。此屬性符合 ECMA-376 中 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的 "Y Rotation" 選項。可讀寫 byte。

**返回:**  
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

返回或設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度之間）。此屬性符合 ECMA-376 中 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 中的 "Y Rotation" 選項。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

返回或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度之間）。此屬性符合 ECMA-376 中 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的 "X Rotation" 選項。可讀寫 int。

**返回:**  
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

返回或設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度之間）。此屬性符合 ECMA-376 中 21.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 中的 "X Rotation" 選項。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

返回或設定 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。如果 RightAngleAxes 屬性值為 true，則忽略此設定。可讀寫 byte。

**返回:**  
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

返回或設定 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。如果 RightAngleAxes 屬性值為 true，則忽略此設定。可讀寫 byte。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

判斷圖表軸是否為直角，而非以透視方式繪製。換言之，它決定圖表軸的角度是否獨立於圖表的旋轉或仰角。可讀寫 boolean。

**返回:**  
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

判斷圖表軸是否為直角，而非以透視方式繪製。換言之，它決定圖表軸的角度是否獨立於圖表的旋轉或仰角。可讀寫 boolean。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。可讀寫 int。

**返回:**  
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

返回或設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。可讀寫 int。

**返回:**  
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。可讀寫 int。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject