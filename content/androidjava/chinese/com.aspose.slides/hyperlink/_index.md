---
title: Hyperlink
second_title: Aspose.Slides for Android via Java API 参考
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
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | 创建一个超链接实例。 |
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
| [getEndShow()](#getEndShow--) | 返回一个结束放映的超链接。 |
| [getActionType()](#getActionType--) | 返回 Hyperlink 动作的类型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示为此段设置的超链接，不考虑该段的实际内容。 |
| [getTargetFrame()](#getTargetFrame--) | 当存在时，返回父 HTML frameset 中父超链接目标的框架。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 当存在时，返回父 HTML frameset 中父超链接目标的框架。 |
| [getTooltip()](#getTooltip--) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [getHistory()](#getHistory--) | 确定在调用时是否将父超链接的目标添加到已查看超链接列表。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 确定在调用时是否将父超链接的目标添加到已查看超链接列表。 |
| [getHighlightClick()](#getHighlightClick--) | 确定在点击时是否应突出显示超链接。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 确定在点击时是否应突出显示超链接。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 确定在点击超链接时是否应停止声音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 确定在点击超链接时是否应停止声音。 |
| [getSound()](#getSound--) | 表示超链接的播放声音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示超链接的播放声音。 |
| [getColorSource()](#getColorSource--) | 表示超链接颜色的来源——样式或段落格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示超链接颜色的来源——样式或段落格式。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定两个 Hyperlink 实例是否相等。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 确定两个 Hyperlink 实例是否相等。 |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 测试两个超链接是否相等。 |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | 测试两个超链接是否不相等。 |
| [hashCode()](#hashCode--) | 为特定类型提供哈希函数，适用于哈希算法和哈希表等数据结构。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

创建一个超链接实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | java.lang.String | 超链接 URL。 |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

创建一个指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | 目标幻灯片。 |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

使用另一个超链接作为源创建超链接实例，覆盖次要属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | 源超链接 |
| targetFrame | java.lang.String | 目标框架 |
| tooltip | java.lang.String | 提示文本 |
| history | boolean | 确定在调用时是否将父超链接的目标添加到已查看超链接列表。 |
| stopSoundsOnClick | boolean | 确定在点击超链接时是否应停止声音。 |
| highlightClick | boolean | 确定在点击时是否应突出显示超链接。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

返回一个特殊的“什么也不做”超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

返回一个特殊的“播放媒体文件”超链接。用于 AudioFrame 和 VideoFrame。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

返回指向下一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

返回指向上一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

返回指向演示文稿第一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

返回指向演示文稿最后一张幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

返回指向最近查看的幻灯片的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

返回一个结束放映的超链接。只读 [Hyperlink](../../com.aspose.slides/hyperlink)。

**返回:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

返回 Hyperlink 动作的类型。只读 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**返回:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

指定外部 URL。只读 String。

**返回:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。只读 [ISlide](../../com.aspose.slides/islide)。

**返回:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

表示为此段设置的超链接，不考虑该段的实际内容。

--------------------

PowerPoint 对链接及其对应的段落文本有特定行为。它允许以有效的 URL 形式创建超链接文本，该文本可能与链接的真实地址不同。在这种情况下，在编辑窗口中查看链接时，它将被更改以匹配文本段落。此属性表示超链接的原始值。

**返回:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

返回当存在时父 HTML frameset 中父超链接目标的框架。只读/可写 String。

**返回:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

返回当存在时父 HTML frameset 中父超链接目标的框架。只读/可写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

返回可能在用户界面中显示的、与父超链接关联的字符串。只读/可写 String。

**返回:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

返回可能在用户界面中显示的、与父超链接关联的字符串。只读/可写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

确定在调用时是否将父超链接的目标添加到已查看超链接列表。只读/可写 boolean。

**返回:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

确定在调用时是否将父超链接的目标添加到已查看超链接列表。只读/可写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

确定在点击时是否应突出显示超链接。只读/可写 boolean。

**返回:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

确定在点击时是否应突出显示超链接。只读/可写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

确定在点击超链接时是否应停止声音。只读/可写 boolean。

**返回:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

确定在点击超链接时是否应停止声音。只读/可写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

表示超链接的播放声音。可读/可写 [IAudio](../../com.aspose.slides/iaudio)。

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Get the first shape hyperlink
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Extract the hyperlink sound in byte array
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Represents the playing sound of the hyperlink. Read/write [IAudio](../../com.aspose.slides/iaudio).

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
>          // 将超链接的声音提取为字节数组
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determines whether the two Hyperlink instances are equal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Hyperlink to compare with the current Hyperlink. |

**Returns:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

确定两个 Hyperlink 实例是否相等。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 与当前 Hyperlink 进行比较的 Hyperlink。 |

**Returns:**
boolean - **true** 如果指定的 Hyperlink 等于当前 Hyperlink；否则为 **false**。
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Tests two hyperlinks for equality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Tests two hyperlinks for inequality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | First hyperlink to be tested. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Second hyperlink to be tested. |

**Returns:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**Returns:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()

返回 Parent\_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject