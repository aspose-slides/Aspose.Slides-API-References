---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，代表有效的 3-D 格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithreedformateffectivedata/
---
**已實作的介面：**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

不可變的物件，代表有效的 3-D 格式屬性。

--------------------

此介面與 [IThreeDFormat](../../com.aspose.slides/ithreedformat) 介面共同使用，以返回套用繼承的有效格式值。

## 方法

| Method | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 返回 3D 輪廓的寬度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 返回 擠出效果的高度。 |
| [getDepth()](#getDepth--) | 返回 3D 形狀的深度。 |
| [getBevelTop()](#getBevelTop--) | 返回 頂部 3D 斜角的類型。 |
| [getBevelBottom()](#getBevelBottom--) | 返回 底部 3D 斜角的類型。 |
| [getContourColor()](#getContourColor--) | 返回 輪廓的顏色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 返回 擠出的顏色。 |
| [getCamera()](#getCamera--) | 返回 相機的設定。 |
| [getLightRig()](#getLightRig--) | 返回 光源的類型。 |
| [getMaterial()](#getMaterial--) | 返回 材料的類型。 |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

返回 3D 輪廓的寬度。只讀 double.

**返回：**
double

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

返回 擠出效果的高度。只讀 double.

**返回：**
double

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

返回 3D 形狀的深度。只讀 double.

**返回：**
double

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

返回 頂部 3D 斜角的類型。只讀 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**返回：**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

返回 底部 3D 斜角的類型。只讀 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**返回：**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)

### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

返回 輪廓的顏色。只讀 java.awt.Color.

**返回：**
java.awt.Color

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

返回 擠出的顏色。只讀 java.awt.Color.

**返回：**
java.awt.Color

### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

返回 相機的設定。只讀 [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**返回：**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)

### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

返回 光源的類型。只讀 [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**返回：**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

返回 材料的類型。只讀 [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**返回：**
int