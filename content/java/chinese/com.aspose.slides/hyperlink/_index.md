---
title: Hyperlink
second_title: Aspose.Slides for Java API 参考
description: 表示一个超链接。
type: docs
url: /zh/com.aspose.slides/hyperlink/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

表示一个超链接。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | 创建一个超链接的实例。 |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | 创建一个指向特定幻灯片的超链接实例。 |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | 使用另一个超链接作为源创建超链接实例，覆盖次要属性。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | 返回一个特殊的“什么也不做”超链接。 |
| [getMedia()](#getMedia--) | 返回一个特殊的“播放媒体文件”超链接。 |
| [getNextSlide()](#getNextSlide--) | 返回指向下一张幻灯片的超链接。 |
| [getPreviousSlide()](#getPreviousSlide--) | 返回指向上一张幻灯片的超链接。 |
| [getFirstSlide()](#getFirstSlide--) | 返回指向演示文稿第一张幻灯片的超链接。 |
| [getLastSlide()](#getLastSlide--) | 返回指向演示文稿最后一张幻灯片的超链接。 |
| [getLastVievedSlide()](#getLastVievedSlide--) | 返回指向最近查看的幻灯片的超链接。 |
| [getEndShow()](#getEndShow--) | 返回一个结束演示的超链接。 |
| [getActionType()](#getActionType--) | 返回 Hyperlink 的操作类型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示为该部分设置的超链接，而不考虑该部分的实际内容。 |
| [getTargetFrame()](#getTargetFrame--) | 在存在时，返回父超链接目标在父 HTML frameset 中的框架。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 在存在时，返回父超链接目标在父 HTML frameset 中的框架。 |
| [getTooltip()](#getTooltip--) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [getHistory()](#getHistory--) | 确定在调用时，是否将父超链接的目标添加到已查看超链接列表中。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 确定在调用时，是否将父超链接的目标添加到已查看超链接列表中。 |
| [getHighlightClick()](#getHighlightClick--) | 确定点击时是否应突出显示超链接。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 确定点击时是否应突出显示超链接。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 确定点击超链接时是否应停止声音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 确定点击超链接时是否应停止声音。 |
| [getSound()](#getSound--) | 表示超链接的播放声音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示超链接的播放声音。 |
| [getColorSource()](#getColorSource--) | 表示超链接颜色的来源——样式或部分格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示超链接颜色的来源——样式或部分格式。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 Hyperlink 实例是否相等。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 确定两个 Hyperlink 实例是否相等。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 测试两个超链接是否相等。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 测试两个超链接是否不相等。 |
| [hashCode()](#hashCode--) | 用作特定类型的哈希函数，适用于散列算法和哈希表等数据结构。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

创建一个超链接的实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

创建一个指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

使用另一个超链接作为源创建超链接实例，覆盖次要属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Source hyperlink |
| targetFrame | java.lang.String | 目标框架 |
| tooltip | java.lang.String | 工具提示文本 |
| history | boolean | 确定在调用时，是否将父超链接的目标添加到已查看超链接列表中。 |
| stopSoundsOnClick | boolean | 确定点击超链接时是否应停止声音。 |
| highlightClick | boolean | 确定点击时是否应突出显示超链接。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值：**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

返回一个特殊的“什么也不做”超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

返回一个特殊的“播放媒体文件”超链接。用于 AudioFrame 和 VideoFrame。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

返回指向下一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

返回指向上一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

返回指向演示文稿第一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

返回指向演示文稿最后一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

返回指向最近查看的幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

返回一个结束演示的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回值：**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

返回 Hyperlink 的操作类型。只读 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**返回值：**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

指定外部 URL。只读 String。

**返回值：**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。只读 [ISlide](../../com.aspose.slides/islide)。

**返回值：**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

表示为该部分设置的超链接，而不考虑该部分的实际内容。

--------------------

PowerPoint 对链接及其对应的文本在段落中的行为有特定规则。它允许以有效的 URL 形式创建超链接文本，该文本可能与链接的真实地址不同。在这种情况下，当您在编辑窗口中查看链接时，它会被更改以匹配文本段落。此属性表示超链接的原始值。

**返回值：**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

在存在时，返回父超链接目标在父 HTML frameset 中的框架。可读/写 String。

**返回值：**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

在存在时，返回父超链接目标在父 HTML frameset 中的框架。可读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

返回可能在用户界面中显示的、与父超链接关联的字符串。可读/写 String。

**返回值：**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

返回可能在用户界面中显示的、与父超链接关联的字符串。可读/写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

确定在调用时，是否将父超链接的目标添加到已查看超链接列表中。可读/写 boolean。

**返回值：**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

确定在调用时，是否将父超链接的目标添加到已查看超链接列表中。可读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

确定点击时是否应突出显示超链接。可读/写 boolean。

**返回值：**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

确定点击时是否应突出显示超链接。可读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

确定点击超链接时是否应停止声音。可读/写 boolean。

**返回值：**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

确定点击超链接时是否应停止声音。可读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

表示超链接的播放声音。可读/写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 获取第一个形状的超链接
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 将超链接声音提取为字节数组
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回值：**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

表示超链接的播放声音。可读/写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // 获取第一个形状的超链接
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // 将超链接声音提取为字节数组
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

表示超链接颜色的来源——样式或部分格式。可读/写 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**返回值：**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

表示超链接颜色的来源——样式或部分格式。可读/写 [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定两个 Hyperlink 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与当前 Hyperlink 比较的 Hyperlink。 |

**返回值：**
boolean - **true** 表示指定的 Hyperlink 等于当前 Hyperlink；否则为 **false**。

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

确定两个 Hyperlink 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 用于与当前 Hyperlink 比较的 Hyperlink。 |

**返回值：**
boolean - **true** 表示指定的 Hyperlink 等于当前 Hyperlink；否则为 **false**。

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

测试两个超链接是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一个待测试的超链接。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二个待测试的超链接。 |

**返回值：**
boolean - **true** 表示超链接相等。

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

测试两个超链接是否不相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第一个待测试的超链接。 |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | 第二个待测试的超链接。 |

**返回值：**
boolean - **false** 表示超链接相等。

### hashCode() {#hashCode--}
```
public int hashCode()
```

用作特定类型的哈希函数，适用于散列算法和哈希表等数据结构。

**返回值：**
int - URL 的哈希码。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值：**
com.aspose.slides.IDOMObject