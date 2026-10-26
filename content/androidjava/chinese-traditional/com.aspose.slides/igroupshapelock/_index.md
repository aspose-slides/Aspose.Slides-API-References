---
title: IGroupShapeLock
second_title: Aspose.Slides for Android via Java API 參考
description: 判斷父 GroupShape 上哪些操作被禁用。
type: docs
url: /zh-hant/com.aspose.slides/igroupshapelock/
---
**所有已實作的介面：**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGroupShapeLock extends IBaseShapeLock
```

判斷父 GroupShape 上哪些操作被禁用。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 判斷是否禁止將此形狀添加到群組中。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 判斷是否禁止將此形狀添加到群組中。 |
| [getUngroupingLocked()](#getUngroupingLocked--) | 判斷是否禁止拆分此群組形狀。 |
| [setUngroupingLocked(boolean value)](#setUngroupingLocked-boolean-) | 判斷是否禁止拆分此群組形狀。 |
| [getSelectLocked()](#getSelectLocked--) | 判斷是否禁止選取此形狀。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 判斷是否禁止選取此形狀。 |
| [getRotationLocked()](#getRotationLocked--) | 判斷是否禁止變更此形狀的旋轉角度。 |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | 判斷是否禁止變更此形狀的旋轉角度。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 判斷在調整大小時是否必須保持寬高比例。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 判斷在調整大小時是否必須保持寬高比例。 |
| [getPositionLocked()](#getPositionLocked--) | 判斷是否禁止移動此形狀。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 判斷是否禁止移動此形狀。 |
| [getSizeLocked()](#getSizeLocked--) | 判斷是否禁止調整此形狀的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 判斷是否禁止調整此形狀的大小。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

判斷是否禁止將此形狀添加到群組中。可讀寫布林。

**傳回值：**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

判斷是否禁止將此形狀添加到群組中。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getUngroupingLocked() {#getUngroupingLocked--}
```
public abstract boolean getUngroupingLocked()
```

判斷是否禁止拆分此群組形狀。可讀寫布林。

**傳回值：**
boolean
### setUngroupingLocked(boolean value) {#setUngroupingLocked-boolean-}
```
public abstract void setUngroupingLocked(boolean value)
```

判斷是否禁止拆分此群組形狀。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

判斷是否禁止選取此形狀。可讀寫布林。

**傳回值：**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

判斷是否禁止選取此形狀。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

判斷是否禁止變更此形狀的旋轉角度。可讀寫布林。

**傳回值：**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

判斷是否禁止變更此形狀的旋轉角度。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

判斷在調整大小時是否必須保持寬高比例。可讀寫布林。

**傳回值：**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

判斷在調整大小時是否必須保持寬高比例。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

判斷是否禁止移動此形狀。可讀寫布林。

**傳回值：**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

判斷是否禁止移動此形狀。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

判斷是否禁止調整此形狀的大小。可讀寫布林。

**傳回值：**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

判斷是否禁止調整此形狀的大小。可讀寫布林。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |