---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the sizing of the slide region width when a child of restoredTop height when a child of restoredLeft of the normal view when the region is of a variable restored sizeneither minimized nor maximized.
type: docs
url: /zh/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

指定普通视图中幻灯片区域的大小（当为 restoredTop 的子项时为宽度，当为 restoredLeft 的子项时为高度），当区域具有可变的恢复大小（既未最小化也未最大化）。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 指定幻灯片区域的大小（当为 RestoredTop 的子项时为宽度，当为 RestoredLeft 的子项时为高度）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 指定幻灯片区域的大小（当为 RestoredTop 的子项时为宽度，当为 RestoredLeft 的子项时为高度）。 |
| [getAutoAdjust()](#getAutoAdjust--) | 指定在调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的大小。读/写 boolean。 |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 指定在调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的大小。读/写 boolean。 |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

指定幻灯片区域的大小（当为 RestoredTop 的子项时为宽度，当为 RestoredLeft 的子项时为高度）。读/写 float。

**返回:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

指定幻灯片区域的大小（当为 RestoredTop 的子项时为宽度，当为 RestoredLeft 的子项时为高度）。读/写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

指定在调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的大小。读/写 boolean。

**返回:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

指定在调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的大小。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |