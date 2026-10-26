---
title: IThreeDFormat
second_title: Aspose.Slides for Java API 參考文件
description: 表示 3-D 屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithreedformat/
---
**所有已實作的介面:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

表示 3-D 屬性。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 取得或設定 3D 輪廓的寬度。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 取得或設定 3D 輪廓的寬度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 取得或設定 擠壓效果的高度。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 取得或設定 擠壓效果的高度。 |
| [getDepth()](#getDepth--) | 取得或設定 3D 形狀的深度。 |
| [setDepth(double value)](#setDepth-double-) | 取得或設定 3D 形狀的深度。 |
| [getBevelTop()](#getBevelTop--) | 取得或設定 上部 3D 倒角的類型。 |
| [getBevelBottom()](#getBevelBottom--) | 取得或設定 下部 3D 倒角的類型。 |
| [getContourColor()](#getContourColor--) | 取得或設定 輪廓的顏色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 取得或設定 擠壓的顏色。 |
| [getCamera()](#getCamera--) | 取得或設定 相機的設定。 |
| [getLightRig()](#getLightRig--) | 取得或設定 光源的類型。 |
| [getMaterial()](#getMaterial--) | 取得或設定 材質的類型。 |
| [setMaterial(int value)](#setMaterial-int-) | 取得或設定 材質的類型。 |
| [getEffective()](#getEffective--) | 取得套用繼承的有效 3-D 格式化資料。 |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

取得或設定 3D 輪廓的寬度。可讀寫 double。

**返回值：**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

取得或設定 3D 輪廓的寬度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

取得或設定 擠壓效果的高度。可讀寫 double。

**返回值：**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

取得或設定 擠壓效果的高度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

取得或設定 3D 形狀的深度。可讀寫 double。

**返回值：**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

取得或設定 3D 形狀的深度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

取得或設定 上部 3D 倒角的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回值：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

取得或設定 下部 3D 倒角的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**返回值：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

取得或設定 輪廓的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

取得或設定 擠壓的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回值：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

取得或設定 相機的設定。唯讀 [ICamera](../../com.aspose.slides/icamera)。

**返回值：**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

取得或設定 光源的類型。唯讀 [ILightRig](../../com.aspose.slides/ilightrig)。

**返回值：**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

取得或設定 材質的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**返回值：**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

取得或設定 材質的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

取得套用繼承的有效 3-D 格式化資料。

**返回值：**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - 一個 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)。