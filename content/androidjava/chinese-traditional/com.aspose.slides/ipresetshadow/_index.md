---
title: IPresetShadow
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示預設陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/ipresetshadow/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

表示預設陰影效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getDirection()](#getDirection--) | 陰影的方向。 |
| [setDirection(float value)](#setDirection-float-) | 陰影的方向。 |
| [getDistance()](#getDistance--) | 陰影的距離。 |
| [setDistance(double value)](#setDistance-double-) | 陰影的距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影的顏色。 |
| [getPreset()](#getPreset--) | 預設。 |
| [setPreset(int value)](#setPreset-int-) | 預設。 |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


陰影的方向。讀寫 float。

**傳回值：**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


陰影的方向。讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


陰影的距離。讀寫 double。

**傳回值：**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


陰影的距離。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


陰影的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


預設。讀寫 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**傳回值：**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


預設。讀寫 [PresetShadowType](../../com.aspose.slides/presetshadowtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |