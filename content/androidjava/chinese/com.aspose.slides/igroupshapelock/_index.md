---
title: IGroupShapeLock
second_title: Aspose.Slides Android 版 Java API 参考
description: 确定在父 GroupShape 上禁用的操作。
type: docs
url: /zh/com.aspose.slides/igroupshapelock/
---
**所有实现的接口：**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGroupShapeLock extends IBaseShapeLock
```

确定在父 GroupShape 上哪些操作被禁用。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 确定是否禁止将此形状添加到组中。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 确定是否禁止将此形状添加到组中。 |
| [getUngroupingLocked()](#getUngroupingLocked--) | 确定是否禁止拆分此 groupshape。 |
| [setUngroupingLocked(boolean value)](#setUngroupingLocked-boolean-) | 确定是否禁止拆分此 groupshape。 |
| [getSelectLocked()](#getSelectLocked--) | 确定是否禁止选择此形状。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 确定是否禁止选择此形状。 |
| [getRotationLocked()](#getRotationLocked--) | 确定是否禁止更改此形状的旋转角度。 |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | 确定是否禁止更改此形状的旋转角度。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 确定在调整大小时是否必须保持形状的宽高比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 确定在调整大小时是否必须保持形状的宽高比。 |
| [getPositionLocked()](#getPositionLocked--) | 确定是否禁止移动此形状。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 确定是否禁止移动此形状。 |
| [getSizeLocked()](#getSizeLocked--) | 确定是否禁止调整此形状的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 确定是否禁止调整此形状的大小。 |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

确定是否禁止将此形状添加到组中。 可读写布尔。

**返回：**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

确定是否禁止将此形状添加到组中。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getUngroupingLocked() {#getUngroupingLocked--}
```
public abstract boolean getUngroupingLocked()
```

确定是否禁止拆分此 groupshape。 可读写布尔。

**返回：**
boolean
### setUngroupingLocked(boolean value) {#setUngroupingLocked-boolean-}
```
public abstract void setUngroupingLocked(boolean value)
```

确定是否禁止拆分此 groupshape。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

确定是否禁止选择此形状。 可读写布尔。

**返回：**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

确定是否禁止选择此形状。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

确定是否禁止更改此形状的旋转角度。 可读写布尔。

**返回：**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

确定是否禁止更改此形状的旋转角度。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

确定在调整大小时是否必须保持形状的宽高比。 可读写布尔。

**返回：**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

确定在调整大小时是否必须保持形状的宽高比。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

确定是否禁止移动此形状。 可读写布尔。

**返回：**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

确定是否禁止移动此形状。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

确定是否禁止调整此形状的大小。 可读写布尔。

**返回：**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

确定是否禁止调整此形状的大小。 可读写布尔。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |