---
title: NormalViewProperties
second_title: Aspose.Slides Java API 参考
description: 表示普通视图属性。
type: docs
url: /zh/com.aspose.slides/normalviewproperties/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //实例化一个表示演示文件的 Presentation 对象
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 指定当侧边区域足够小时时，垂直分割条是否应自动折叠到最小化状态。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 指定当侧边区域足够小时时，垂直分割条是否应自动折叠到最小化状态。 |
| [getVerticalBarState()](#getVerticalBarState--) | 指定垂直分割条应显示的状态。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 指定垂直分割条应显示的状态。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 指定水平分割条应显示的状态。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 指定水平分割条应显示的状态。 |
| [getPreferSingleView()](#getPreferSingleView--) | 指定用户是否更倾向于查看全窗口的单内容区域，而不是具有三个内容区域的标准普通视图。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 指定用户是否更倾向于查看全窗口的单内容区域，而不是具有三个内容区域的标准普通视图。 |
| [getRestoredLeft()](#getRestoredLeft--) | 当侧边内容区域处于可变的恢复大小（既未最小化也未最大化）时，此元素指定普通视图侧边内容区域的大小。 |
| [getRestoredTop()](#getRestoredTop--) | 当顶部幻灯片区域处于可变的恢复大小（既未最小化也未最大化）时，此元素指定普通视图顶部幻灯片区域的大小。 |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。读写布尔值。

**返回值:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。读写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

指定当侧边区域足够小时时，垂直分割条是否应自动折叠到最小化状态。读写布尔值。

**返回值:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

指定当侧边区域足够小时时，垂直分割条是否应自动折叠到最小化状态。读写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

指定垂直分割条应显示的状态。垂直分割条将幻灯片与侧边内容区域分隔开。

**返回值:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

指定垂直分割条应显示的状态。垂直分割条将幻灯片与侧边内容区域分隔开。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

指定水平分割条应显示的状态。水平分割条将幻灯片与幻灯片下方的内容区域分隔开。

**返回值:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

指定水平分割条应显示的状态。水平分割条将幻灯片与幻灯片下方的内容区域分隔开。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

指定用户是否更倾向于查看全窗口的单内容区域，而不是具有三个内容区域的标准普通视图。如果启用，应用程序可能会选择在整个窗口中显示其中一个内容区域。读写布尔值。

**返回值:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

指定用户是否更倾向于查看全窗口的单内容区域，而不是具有三个内容区域的标准普通视图。如果启用，应用程序可能会选择在整个窗口中显示其中一个内容区域。读写布尔值。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

当侧边内容区域处于可变的恢复大小（既未最小化也未最大化）时，此元素指定普通视图侧边内容区域的大小。只读 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回值:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

当顶部幻灯片区域处于可变的恢复大小（既未最小化也未最大化）时，此元素指定普通视图顶部幻灯片区域的大小。只读 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回值:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)