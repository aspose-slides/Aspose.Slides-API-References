---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /zh/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

表示普通视图属性。普通视图由三个内容区域组成：幻灯片本身、侧边内容区域和底部内容区域。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | 指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。 |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | 指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。 |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | 指定当侧边区域足够小时时，垂直分割条是否应自动折叠至最小化状态。 |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | 指定当侧边区域足够小时时，垂直分割条是否应自动折叠至最小化状态。 |
| [getVerticalBarState()](#getVerticalBarState--) | 指定垂直分割条应显示的状态。 |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | 指定垂直分割条应显示的状态。 |
| [getHorizontalBarState()](#getHorizontalBarState--) | 指定水平分割条应显示的状态。 |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | 指定水平分割条应显示的状态。 |
| [getPreferSingleView()](#getPreferSingleView--) | 指定用户是否更倾向于在全窗口单内容区域中查看，而不是具有三个内容区域的标准普通视图。 |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | 指定用户是否更倾向于在全窗口单内容区域中查看，而不是具有三个内容区域的标准普通视图。 |
| [getRestoredLeft()](#getRestoredLeft--) | 当侧边内容区域处于可变的恢复大小（既非最小化也非最大化）时，此元素指定普通视图中侧边内容区域的大小。 |
| [getRestoredTop()](#getRestoredTop--) | 当顶部幻灯片区域处于可变的恢复大小（既非最小化也非最大化）时，此元素指定普通视图中顶部幻灯片区域的大小。 |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。读/写 布尔。

**返回:**  
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

指定当在普通视图模式的任何内容区域显示大纲内容时，应用程序是否应显示图标。读/写 布尔。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

指定当侧边区域足够小时时，垂直分割条是否应自动折叠至最小化状态。读/写 布尔。

**返回:**  
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

指定当侧边区域足够小时时，垂直分割条是否应自动折叠至最小化状态。读/写 布尔。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
``` 
public abstract int getVerticalBarState()
```

指定垂直分割条应显示的状态。垂直分割条将幻灯片与侧边内容区域分开。

**返回:**  
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

指定垂直分割条应显示的状态。垂直分割条将幻灯片与侧边内容区域分开。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

指定水平分割条应显示的状态。水平分割条将幻灯片与幻灯片下方的内容区域分开。

**返回:**  
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

指定水平分割条应显示的状态。水平分割条将幻灯片与幻灯片下方的内容区域分开。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

指定用户是否更倾向于在全窗口单内容区域中查看，而不是具有三个内容区域的标准普通视图。如果启用，应用程序可能会选择在整个窗口中显示其中一个内容区域。读/写 布尔。

**返回:**  
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

指定用户是否更倾向于在全窗口单内容区域中查看，而不是具有三个内容区域的标准普通视图。如果启用，应用程序可能会选择在整个窗口中显示其中一个内容区域。读/写 布尔。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

当侧边内容区域处于可变的恢复大小（既非最小化也非最大化）时，此元素指定普通视图中侧边内容区域的大小。只读 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

当顶部幻灯片区域处于可变的恢复大小（既非最小化也非最大化）时，此元素指定普通视图中顶部幻灯片区域的大小。只读 [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)。

**返回:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)