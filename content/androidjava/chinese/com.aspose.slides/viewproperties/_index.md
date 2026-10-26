---
title: ViewProperties
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 演示文稿全局视图属性。
type: docs
url: /zh/com.aspose.slides/viewproperties/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

演示文稿的全局视图属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定演示文稿上次保存时使用的视图模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定演示文稿上次保存时使用的视图模式。 |
| [getShowComments()](#getShowComments--) | 指定是否显示幻灯片注释。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否显示幻灯片注释。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示普通视图属性。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定与幻灯片视图模式相关的通用视图属性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定与备注视图模式相关的通用视图属性。 |
| [getGridSpacing()](#getGridSpacing--) | 返回或设置演示文稿底层网格的网格间距（以点为单位）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 返回或设置演示文稿底层网格的网格间距（以点为单位）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

指定演示文稿上次保存时使用的视图模式。可读写 [ViewType](../../com.aspose.slides/viewtype).

**Returns:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

指定演示文稿上次保存时使用的视图模式。可读写 [ViewType](../../com.aspose.slides/viewtype).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

指定是否显示幻灯片注释。可读写 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

指定是否显示幻灯片注释。可读写 [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。只读 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Returns:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

指定与幻灯片视图模式相关的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

指定与备注视图模式相关的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Returns:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

返回或设置演示文稿底层网格的网格间距（以点为单位）。可读写 float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Returns:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. Read/write float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

The grid spacing value must be a positive number . The typical value range is from 1 mm (2.8349607 points) to 2 inches (144 points).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()

返回 Parent\_Immediate 对象。只读 IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject