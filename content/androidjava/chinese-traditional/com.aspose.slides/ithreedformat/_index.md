---
title: IThreeDFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示 3-D 屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithreedformat/
---
**所有已實作的介面：**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

表示 3-D 屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 傳回或設定 3D 輪廓的寬度。 |
| [setContourWidth(double value)](#setContourWidth-double-) | 傳回或設定 3D 輪廓的寬度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 傳回或設定 拉伸效果的高度。 |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | 傳回或設定 拉伸效果的高度。 |
| [getDepth()](#getDepth--) | 傳回或設定 3D 形狀的深度。 |
| [setDepth(double value)](#setDepth-double-) | 傳回或設定 3D 形狀的深度。 |
| [getBevelTop()](#getBevelTop--) | 傳回或設定 top 3D bevel 的類型。 |
| [getBevelBottom()](#getBevelBottom--) | 傳回或設定 bottom 3D bevel 的類型。 |
| [getContourColor()](#getContourColor--) | 傳回或設定 輪廓的顏色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 傳回或設定 拉伸的顏色。 |
| [getCamera()](#getCamera--) | 傳回或設定 相機的設定。 |
| [getLightRig()](#getLightRig--) | 傳回或設定 光源的類型。 |
| [getMaterial()](#getMaterial--) | 傳回或設定 材質的類型。 |
| [setMaterial(int value)](#setMaterial-int-) | 傳回或設定 材質的類型。 |
| [getEffective()](#getEffective--) | 取得套用繼承的有效 3-D 格式化資料。 |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

傳回或設定 3D 輪廓的寬度。可讀寫 double。

**傳回：**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

傳回或設定 3D 輪廓的寬度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

傳回或設定 拉伸效果的高度。可讀寫 double。

**傳回：**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

傳回或設定 拉伸效果的高度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

傳回或設定 3D 形狀的深度。可讀寫 double。

**傳回：**
double

### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

傳回或設定 3D 形狀的深度。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

傳回或設定 top 3D bevel 的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**傳回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

傳回或設定 bottom 3D bevel 的類型。唯讀 [IShapeBevel](../../com.aspose.slides/ishapebevel)。

**傳回：**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

傳回或設定 輪廓的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

傳回或設定 拉伸的顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**傳回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

傳回或設定 相機的設定。唯讀 [ICamera](../../com.aspose.slides/icamera)。

**傳回：**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

傳回或設定 光源的類型。唯讀 [ILightRig](../../com.aspose.slides/ilightrig)。

**傳回：**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

傳回或設定 材質的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**傳回：**
int

### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

傳回或設定 材質的類型。可讀寫 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

取得套用繼承的有效 3-D 格式化資料。

**傳回：**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - 一個 [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata)。