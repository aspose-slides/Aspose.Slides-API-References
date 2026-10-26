---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Java API Reference
description: 指定普通视图中幻灯片区域的大小（当作为 restoredTop 的子项时表示宽度，作为 restoredLeft 的子项时表示高度），当该区域具有可变的恢复大小（既未最小化也未最大化）时。
type: docs
url: /zh/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

指定普通视图中幻灯片区域的大小（当作为 restoredTop 的子项时表示宽度，作为 restoredLeft 的子项时表示高度），当该区域具有可变的恢复大小（既未最小化也未最大化）时。
## Methods

| 方法 | 描述 |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | 指定幻灯片区域的大小（当作为 RestoredTop 的子项时为宽度，作为 RestoredLeft 的子项时为高度）。 |
| [setDimensionSize(float value)](#setDimensionSize-float-) | 指定幻灯片区域的大小（当作为 RestoredTop 的子项时为宽度，作为 RestoredLeft 的子项时为高度）。 |
| [getAutoAdjust()](#getAutoAdjust--) | 指定在调整包含视图的窗口大小时，是否应让侧内容区域的大小补偿新的尺寸。Read/write boolean |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | 指定在调整包含视图的窗口大小时，是否应让侧内容区域的大小补偿新的尺寸。Read/write boolean |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

指定幻灯片区域的大小（当作为 RestoredTop 的子项时为宽度，作为 RestoredLeft 的子项时为高度）。Read/write float.

**Returns:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

指定幻灯片区域的大小（当作为 RestoredTop 的子项时为宽度，作为 RestoredLeft 的子项时为高度）。Read/write float.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

指定在调整包含视图的窗口大小时，是否应让侧内容区域的大小补偿新的尺寸。Read/write boolean.

**Returns:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

指定在调整包含视图的窗口大小时，是否应让侧内容区域的大小补偿新的尺寸。Read/write boolean.

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |