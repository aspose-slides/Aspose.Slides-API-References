---
title: IPictureFrameLock
second_title: Aspose.Slides for Android via Java API 参考
description: 确定在父级 PictureFrameEx 上禁用哪些操作。
type: docs
url: /zh/com.aspose.slides/ipictureframelock/
---
**所有已实现的接口：**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IPictureFrameLock extends IBaseShapeLock
```

确定在父级 PictureFrameEx 上禁用哪些操作。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | 确定是否禁止将此形状添加到组中。 |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | 确定是否禁止将此形状添加到组中。 |
| [getSelectLocked()](#getSelectLocked--) | 确定是否禁止选择此形状。 |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | 确定是否禁止选择此形状。 |
| [getRotationLocked()](#getRotationLocked--) | 确定是否禁止更改此形状的旋转角度。 |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | 确定是否禁止更改此形状的旋转角度。 |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | 确定在调整大小时是否必须保持宽高比。 |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | 确定在调整大小时是否必须保持宽高比。 |
| [getPositionLocked()](#getPositionLocked--) | 确定是否禁止移动此形状。 |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | 确定是否禁止移动此形状。 |
| [getSizeLocked()](#getSizeLocked--) | 确定是否禁止调整此形状的大小。 |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | 确定是否禁止调整此形状的大小。 |
| [getEditPointsLocked()](#getEditPointsLocked--) | 确定是否禁止直接更改此形状的轮廓。 |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | 确定是否禁止直接更改此形状的轮廓。 |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | 确定是否禁止更改调整值。 |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | 确定是否禁止更改调整值。 |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | 确定是否禁止更改箭头端点。 |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | 确定是否禁止更改箭头端点。 |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | 确定是否禁止更改形状类型。 |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | 确定是否禁止更改形状类型。 |
| [getCropLocked()](#getCropLocked--) | 确定是否禁止图像裁剪。 |
| [setCropLocked(boolean value)](#setCropLocked-boolean-) | 确定是否禁止图像裁剪。 |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

确定是否禁止将此形状添加到组中。 读/写 布尔值。

**返回：**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

确定是否禁止将此形状添加到组中。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

确定是否禁止选择此形状。 读/写 布尔值。

**返回：**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

确定是否禁止选择此形状。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

确定是否禁止更改此形状的旋转角度。 读/写 布尔值。

**返回：**
boolean

### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

确定是否禁止更改此形状的旋转角度。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

确定在调整大小时是否必须保持宽高比。 读/写 布尔值。

**返回：**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

确定在调整大小时是否必须保持宽高比。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

确定是否禁止移动此形状。 读/写 布尔值。

**返回：**
boolean

### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

确定是否禁止移动此形状。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

确定是否禁止调整此形状的大小。 读/写 布尔值。

**返回：**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

确定是否禁止调整此形状的大小。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

确定是否禁止直接更改此形状的轮廓。 读/写 布尔值。

**返回：**
boolean

### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

确定是否禁止直接更改此形状的轮廓。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

确定是否禁止更改调整值。 读/写 布尔值。

**返回：**
boolean

### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

确定是否禁止更改调整值。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

确定是否禁止更改箭头端点。 读/写 布尔值。

**返回：**
boolean

### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

确定是否禁止更改箭头端点。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

确定是否禁止更改形状类型。 读/写 布尔值。

**返回：**
boolean

### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

确定是否禁止更改形状类型。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getCropLocked() {#getCropLocked--}
```
public abstract boolean getCropLocked()
```

确定是否禁止图像裁剪。 读/写 布尔值。

**返回：**
boolean

### setCropLocked(boolean value) {#setCropLocked-boolean-}
```
public abstract void setCropLocked(boolean value)
```

确定是否禁止图像裁剪。 读/写 布尔值。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |