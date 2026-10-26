---
title: IGraphicalObjectLock
second_title: Aspose.Slides for Android via Java API 参考
description: 确定在父 GraphicalObject 上禁用哪些操作。
type: docs
url: /zh/com.aspose.slides/igraphicalobjectlock/
---
**所有已实现的接口：**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

确定在父 GraphicalObject 上禁用哪些操作。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 确定将此形状添加到组中是否被禁止。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 确定将此形状添加到组中是否被禁止。 |
| [getDrilldownLocked()](#getDrilldownLocked--) | 确定是否禁止选择此对象的子形状。 |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | 确定是否禁止选择此对象的子形状。 |
| [getSelectLocked()](#getSelectLocked--) | 确定是否禁止选择此形状。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 确定是否禁止选择此形状。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 确定在调整大小时是否必须保持宽高比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 确定在调整大小时是否必须保持宽高比。 |
| [getPositionLocked()](#getPositionLocked--) | 确定是否禁止移动此形状。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 确定是否禁止移动此形状。 |
| [getSizeLocked()](#getSizeLocked--) | 确定是否禁止调整此形状的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 确定是否禁止调整此形状的大小。 |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

确定将此形状添加到组中是否被禁止。读/写 布尔。

**返回：**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

确定将此形状添加到组中是否被禁止。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

确定是否禁止选择此对象的子形状。读/写 布尔。

**返回：**
boolean

### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

确定是否禁止选择此对象的子形状。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

确定是否禁止选择此形状。读/写 布尔。

**返回：**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

确定是否禁止选择此形状。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

确定在调整大小时是否必须保持宽高比。读/写 布尔。

**返回：**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

确定在调整大小时是否必须保持宽高比。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

确定是否禁止移动此形状。读/写 布尔。

**返回：**
boolean

### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

确定是否禁止移动此形状。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

确定是否禁止调整此形状的大小。读/写 布尔。

**返回：**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

确定是否禁止调整此形状的大小。读/写 布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |