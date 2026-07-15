---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變物件，代表有效的 3-D 格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithreedformateffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

不可變物件，代表有效的 3-D 格式屬性。

--------------------

此介面與 [IThreeDFormat](../../com.aspose.slides/ithreedformat) 介面一起使用，以返回套用繼承的有效格式化值。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 傳回 3D 輪廓的寬度。 |
| [getExtrusionHeight()](#getExtrusionHeight--) | 傳回擠出效果的高度。 |
| [getDepth()](#getDepth--) | 傳回 3D 形狀的深度。 |
| [getBevelTop()](#getBevelTop--) | 傳回頂部 3D 斜角的類型。 |
| [getBevelBottom()](#getBevelBottom--) | 傳回底部 3D 斜角的類型。 |
| [getContourColor()](#getContourColor--) | 傳回輪廓的顏色。 |
| [getExtrusionColor()](#getExtrusionColor--) | 傳回擠出的顏色。 |
| [getCamera()](#getCamera--) | 傳回相機的設定。 |
| [getLightRig()](#getLightRig--) | 傳回光源的類型。 |
| [getMaterial()](#getMaterial--) | 傳回材質的類型。 |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


傳回 3D 輪廓的寬度。唯讀 double。

**傳回：**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


傳回擠出效果的高度。唯讀 double。

**傳回：**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


傳回 3D 形狀的深度。唯讀 double。

**傳回：**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


傳回頂部 3D 斜角的類型。唯讀 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**傳回：**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


傳回底部 3D 斜角的類型。唯讀 [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)。

**傳回：**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


傳回輪廓的顏色。唯讀 java.lang.Integer。

**傳回：**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


傳回擠出的顏色。唯讀 java.lang.Integer。

**傳回：**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


傳回相機的設定。唯讀 [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)。

**傳回：**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


傳回光源的類型。唯讀 [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)。

**傳回：**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


傳回材質的類型。唯讀 [MaterialPresetType](../../com.aspose.slides/materialpresettype)。

**傳回：**
int