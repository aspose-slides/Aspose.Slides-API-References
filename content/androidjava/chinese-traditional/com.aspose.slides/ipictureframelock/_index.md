---
title: IPictureFrameLock
second_title: Aspose.Slides for Android via Java API 參考
description: 確定在父 PictureFrameEx 上哪些操作被停用。
type: docs
url: /zh-hant/com.aspose.slides/ipictureframelock/
---
**全部已實作的介面：**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IPictureFrameLock extends IBaseShapeLock
```

判斷在父 PictureFrameEx 上哪些操作被停用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 判斷是否禁止將此形狀加入群組。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 判斷是否禁止將此形狀加入群組。 |
| [getSelectLocked()](#getSelectLocked--) | 判斷是否禁止選取此形狀。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 判斷是否禁止選取此形狀。 |
| [getRotationLocked()](#getRotationLocked--) | 判斷是否禁止變更此形狀的旋轉角度。 |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | 判斷是否禁止變更此形狀的旋轉角度。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 判斷在調整大小時是否必須保持此形狀的長寬比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 判斷在調整大小時是否必須保持此形狀的長寬比。 |
| [getPositionLocked()](#getPositionLocked--) | 判斷是否禁止移動此形狀。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 判斷是否禁止移動此形狀。 |
| [getSizeLocked()](#getSizeLocked--) | 判斷是否禁止調整此形狀的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 判斷是否禁止調整此形狀的大小。 |
| [getEditPointsLocked()](#getEditPointsLocked--) | 判斷是否禁止直接變更此形狀的輪廓。 |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | 判斷是否禁止直接變更此形狀的輪廓。 |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | 判斷是否禁止變更調整值。 |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | 判斷是否禁止變更調整值。 |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | 判斷是否禁止變更箭頭端點。 |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | 判斷是否禁止變更箭頭端點。 |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | 判斷是否禁止更改形狀類型。 |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | 判斷是否禁止更改形狀類型。 |
| [getCropLocked()](#getCropLocked--) | 判斷是否禁止影像裁剪。 |
| [setCropLocked(boolean value)](#setCropLocked-boolean-) | 判斷是否禁止影像裁剪。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

判斷是否禁止將此形狀加入群組。 可讀寫 boolean。

**返回：**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

判斷是否禁止將此形狀加入群組。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

判斷是否禁止選取此形狀。 可讀寫 boolean。

**返回：**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

判斷是否禁止選取此形狀。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

判斷是否禁止變更此形狀的旋轉角度。 可讀寫 boolean。

**返回：**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

判斷是否禁止變更此形狀的旋轉角度。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

判斷在調整大小時是否必須保持此形狀的長寬比。 可讀寫 boolean。

**返回：**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

判斷在調整大小時是否必須保持此形狀的長寬比。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

判斷是否禁止移動此形狀。 可讀寫 boolean。

**返回：**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

判斷是否禁止移動此形狀。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

判斷是否禁止調整此形狀的大小。 可讀寫 boolean。

**返回：**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

判斷是否禁止調整此形狀的大小。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

判斷是否禁止直接變更此形狀的輪廓。 可讀寫 boolean。

**返回：**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

判斷是否禁止直接變更此形狀的輪廓。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

判斷是否禁止變更調整值。 可讀寫 boolean。

**返回：**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

判斷是否禁止變更調整值。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

判斷是否禁止變更箭頭端點。 可讀寫 boolean。

**返回：**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

判斷是否禁止變更箭頭端點。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

判斷是否禁止更改形狀類型。 可讀寫 boolean。

**返回：**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

判斷是否禁止更改形狀類型。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getCropLocked() {#getCropLocked--}
```
public abstract boolean getCropLocked()
```

判斷是否禁止影像裁剪。 可讀寫 boolean。

**返回：**
boolean
### setCropLocked(boolean value) {#setCropLocked-boolean-}
```
public abstract void setCropLocked(boolean value)
```

判斷是否禁止影像裁剪。 可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |