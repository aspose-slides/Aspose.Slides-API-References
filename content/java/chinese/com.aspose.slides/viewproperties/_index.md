---
title: ViewProperties
second_title: Aspose.Slides for Java API 参考
description: 演示文稿范围的视图属性。
type: docs
url: /zh/com.aspose.slides/viewproperties/
---
**继承:**
java.lang.Object

**全部实现的接口:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

演示文稿范围的视图属性。
## 方法

| 方法 | 说明 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定在上次保存演示文稿时使用的视图模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定在上次保存演示文稿时使用的视图模式。 |
| [getShowComments()](#getShowComments--) | 指定是否应显示幻灯片批注。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否应显示幻灯片批注。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示普通视图属性。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定与幻灯片视图模式关联的通用视图属性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定与备注视图模式关联的通用视图属性。 |
| [getGridSpacing()](#getGridSpacing--) | 返回或设置演示文稿底层网格应使用的网格间距（单位为点）。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 返回或设置演示文稿底层网格应使用的网格间距（单位为点）。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

指定在上次保存演示文稿时使用的视图模式。读写 [ViewType](../../com.aspose.slides/viewtype).

**返回:**
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

指定在上次保存演示文稿时使用的视图模式。读写 [ViewType](../../com.aspose.slides/viewtype).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

指定是否应显示幻灯片批注。读写 [NullableBool](../../com.aspose.slides/nullablebool).

**返回:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

指定是否应显示幻灯片批注。读写 [NullableBool](../../com.aspose.slides/nullablebool).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。只读 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**返回:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

指定与幻灯片视图模式关联的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**返回:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

指定与备注视图模式关联的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**返回:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

返回或设置演示文稿底层网格应使用的网格间距（单位为点）。读写 float.

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

网格间距值必须为正数。典型的取值范围是 1 mm（2.8349607 points）到 2 inches（144 points）。

**返回:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

返回或设置演示文稿底层网格应使用的网格间距（单位为点）。读写 float.

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

网格间距值必须为正数。典型的取值范围是 1 mm（2.8349607 points）到 2 inches（144 points）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject