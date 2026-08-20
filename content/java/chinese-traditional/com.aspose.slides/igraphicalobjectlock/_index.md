---
title: IGraphicalObjectLock
second_title: Aspose.Slides for Java API 參考文檔
description: 判斷父級 GraphicalObject 哪些操作被禁用。
type: docs
url: /zh-hant/com.aspose.slides/igraphicalobjectlock/
---
**所有已實作的介面:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

判斷父級 GraphicalObject 哪些操作被禁用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 判斷是否禁止將此形狀加入群組。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 判斷是否禁止將此形狀加入群組。 |
| [getDrilldownLocked()](#getDrilldownLocked--) | 判斷是否禁止選取此物件的子形狀。 |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | 判斷是否禁止選取此物件的子形狀。 |
| [getSelectLocked()](#getSelectLocked--) | 判斷是否禁止選取此形狀。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 判斷是否禁止選取此形狀。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 判斷形狀在調整大小時是否必須保持長寬比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 判斷形狀在調整大小時是否必須保持長寬比。 |
| [getPositionLocked()](#getPositionLocked--) | 判斷是否禁止移動此形狀。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 判斷是否禁止移動此形狀。 |
| [getSizeLocked()](#getSizeLocked--) | 判斷是否禁止調整此形狀的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 判斷是否禁止調整此形狀的大小。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

判斷是否禁止將此形狀加入群組。讀寫布林值。

**返回:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

判斷是否禁止將此形狀加入群組。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

判斷是否禁止選取此物件的子形狀。讀寫布林值。

**返回:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

判斷是否禁止選取此物件的子形狀。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

判斷是否禁止選取此形狀。讀寫布林值。

**返回:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

判斷是否禁止選取此形狀。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

判斷形狀在調整大小時是否必須保持長寬比。讀寫布林值。

**返回:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

判斷形狀在調整大小時是否必須保持長寬比。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

判斷是否禁止移動此形狀。讀寫布林值。

**返回:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

判斷是否禁止移動此形狀。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

判斷是否禁止調整此形狀的大小。讀寫布林值。

**返回:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

判斷是否禁止調整此形狀的大小。讀寫布林值。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |