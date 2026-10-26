---
title: IGraphicalObjectLock
second_title: Aspose.Slides for Android via Java API 參考
description: 決定在父 GraphicalObject 上哪些操作被禁用。
type: docs
url: /zh-hant/com.aspose.slides/igraphicalobjectlock/
---
**所有已實作的介面:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

決定在父 GraphicalObject 上哪些操作被禁用。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 決定是否禁止將此形狀新增至群組。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 決定是否禁止將此形狀新增至群組。 |
| [getDrilldownLocked()](#getDrilldownLocked--) | 決定是否禁止選取此物件的子形狀。 |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | 決定是否禁止選取此物件的子形狀。 |
| [getSelectLocked()](#getSelectLocked--) | 決定是否禁止選取此形狀。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 決定是否禁止選取此形狀。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 決定形狀在調整大小時是否必須保留長寬比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 決定形狀在調整大小時是否必須保留長寬比。 |
| [getPositionLocked()](#getPositionLocked--) | 決定是否禁止移動此形狀。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 決定是否禁止移動此形狀。 |
| [getSizeLocked()](#getSizeLocked--) | 決定是否禁止調整此形狀的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 決定是否禁止調整此形狀的大小。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

決定是否禁止將此形狀新增至群組。 可讀寫 boolean。

**傳回:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

決定是否禁止將此形狀新增至群組。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

決定是否禁止選取此物件的子形狀。 可讀寫 boolean。

**傳回:**
boolean
### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

決定是否禁止選取此物件的子形狀。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

決定是否禁止選取此形狀。 可讀寫 boolean。

**傳回:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

決定是否禁止選取此形狀。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

決定形狀在調整大小時是否必須保留長寬比。 可讀寫 boolean。

**傳回:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

決定形狀在調整大小時是否必須保留長寬比。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

決定是否禁止移動此形狀。 可讀寫 boolean。

**傳回:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

決定是否禁止移動此形狀。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

決定是否禁止調整此形狀的大小。 可讀寫 boolean。

**傳回:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

決定是否禁止調整此形狀的大小。 可讀寫 boolean。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |