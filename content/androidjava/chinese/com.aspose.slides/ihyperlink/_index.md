---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference 的中文文档
description: 表示一个超链接。
type: docs
url: /zh/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

表示一个超链接。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getActionType()](#getActionType--) | 返回 HyperLinkEx 的操作类型。 |
| [getExternalUrl()](#getExternalUrl--) | 指定外部 URL。如果此属性变为非 null，则属性 TargetSlide 将变为 null。 |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | 表示为此段设置的超链接，而不考虑段的实际内容。 |
| [getTargetSlide()](#getTargetSlide--) | 如果 HyperlinkEx 目标为特定幻灯片，则返回该幻灯片。 |
| [getTargetFrame()](#getTargetFrame--) | 返回父超链接目标所在的父 HTML frameset 中的框架（如果存在）。 |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | 返回父超链接目标所在的父 HTML frameset 中的框架（如果存在）。 |
| [getTooltip()](#getTooltip--) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | 返回可能在用户界面中显示的、与父超链接关联的字符串。 |
| [getHistory()](#getHistory--) | 确定在调用时是否将父超链接的目标添加到已查看超链接列表中。 |
| [setHistory(boolean value)](#setHistory-boolean-) | 确定在调用时是否将父超链接的目标添加到已查看超链接列表中。 |
| [getHighlightClick()](#getHighlightClick--) | 确定点击时是否应突出显示超链接。 |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | 确定点击时是否应突出显示超链接。 |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | 确定在点击超链接时是否应停止声音。 |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | 确定在点击超链接时是否应停止声音。 |
| [getSound()](#getSound--) | 表示超链接的播放声音。 |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | 表示超链接的播放声音。 |
| [getColorSource()](#getColorSource--) | 表示超链接颜色的来源——样式或段格式。 |
| [setColorSource(int value)](#setColorSource-int-) | 表示超链接颜色的来源——样式或段格式。 |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | 确定两个 Hyperlink 实例是否相等。 |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

返回 HyperLinkEx 的操作类型。只读 [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype)。

**返回：**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

指定外部 URL。如果此属性变为非 null，则属性 TargetSlide 将变为 null。只读 String。

**返回：**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

表示为此段设置的超链接，而不考虑段的实际内容。

--------------------

PowerPoint 对链接及其对应的文本在段中有特殊行为。它允许以有效 URL 的形式创建超链接文本，该 URL 与链接的真实地址不同。在这种情况下，当在编辑窗口中查看链接时，它会被更改为匹配文本段。此属性表示超链接的原始值。

**返回：**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

如果 HyperlinkEx 目标为特定幻灯片，则返回该幻灯片。如果此属性变为非 null，则属性 ExternalUrl 将变为 null。只读 [ISlide](../../com.aspose.slides/islide)。

**返回：**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

返回父超链接目标所在的父 HTML frameset 中的框架（如果存在）。读写 String。

**返回：**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

返回父超链接目标所在的父 HTML frameset 中的框架（如果存在）。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

返回可能在用户界面中显示的、与父超链接关联的字符串。读写 String。

**返回：**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

返回可能在用户界面中显示的、与父超链接关联的字符串。读写 String。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

确定在调用时是否将父超链接的目标添加到已查看超链接列表中。读写 boolean。

**返回：**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

确定在调用时是否将父超链接的目标添加到已查看超链接列表中。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

确定点击时是否应突出显示超链接。读写 boolean。

**返回：**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

确定点击时是否应突出显示超链接。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

确定在点击超链接时是否应停止声音。读写 boolean。

**返回：**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

确定在点击超链接时是否应停止声音。读写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

表示超链接的播放声音。读写 [IAudio](../../com.aspose.slides/iaudio)。

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
public abstract void setSound(IAudio value)
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
>          // 提取超链接声音的字节数组
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
public abstract int getColorSource()
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Returns:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Represents the source of hyperlink color - either styles or portion format. Read/write [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)

确定两个 Hyperlink 实例是否相等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | 要与当前 Hyperlink 进行比较的 Hyperlink。 |

**返回：**
boolean - **true** 表示指定的 Hyperlink 与当前 Hyperlink 相等；否则 **false**。