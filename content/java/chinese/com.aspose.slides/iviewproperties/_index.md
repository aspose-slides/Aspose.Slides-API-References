---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: 演示文稿范围的视图属性。
type: docs
url: /zh/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

整个演示文稿的视图属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLastView()](#getLastView--) | 指定在上次保存演示文稿时使用的视图模式。 |
| [setLastView(int value)](#setLastView-int-) | 指定在上次保存演示文稿时使用的视图模式。 |
| [getShowComments()](#getShowComments--) | 指定是否应显示幻灯片注释。 |
| [setShowComments(byte value)](#setShowComments-byte-) | 指定是否应显示幻灯片注释。 |
| [getSlideViewProperties()](#getSlideViewProperties--) | 指定与幻灯片视图模式相关的通用视图属性。 |
| [getNotesViewProperties()](#getNotesViewProperties--) | 指定与备注视图模式相关的通用视图属性。 |
| [getNormalViewProperties()](#getNormalViewProperties--) | 表示普通视图属性。 |
| [getGridSpacing()](#getGridSpacing--) | 返回或设置演示文稿底层网格应使用的网格间距，单位为点。 |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 返回或设置演示文稿底层网格应使用的网格间距，单位为点。 |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

指定在上次保存演示文稿时使用的视图模式。读/写 [ViewType](../../com.aspose.slides/viewtype)。

**返回：**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

指定在上次保存演示文稿时使用的视图模式。读/写 [ViewType](../../com.aspose.slides/viewtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

指定是否应显示幻灯片注释。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

指定是否应显示幻灯片注释。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

指定与幻灯片视图模式相关的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**返回：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

指定与备注视图模式相关的通用视图属性。只读 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)。

**返回：**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。只读 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties)。

**返回：**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

返回或设置演示文稿底层网格应使用的网格间距，单位为点。读/写 float.

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

网格间距值必须为正数。典型值范围为 1 毫米（2.8349607 点）到 2 英寸（144 点）。

**返回：**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

返回或设置演示文稿底层网格应使用的网格间距，单位为点。读/写 float.

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

网格间距值必须为正数。典型值范围为 1 毫米（2.8349607 点）到 2 英寸（144 点）。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |