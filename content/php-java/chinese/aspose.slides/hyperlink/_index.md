---
title: Hyperlink
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/hyperlink/
---
## Hyperlink 类

 表示一个超链接。

### Hyperlink {#Hyperlink}

| 名称 | 描述 |
| --- | --- |
| Hyperlink(String) | 创建一个超链接的实例。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| url | String | 超链接 URL。 |

**返回值：**
Hyperlink


---


### Hyperlink {#Hyperlink}

| 名称 | 描述 |
| --- | --- |
| Hyperlink([Slide](../slide)) | 创建一个指向特定幻灯片的超链接实例。注意：创建的超链接应分配给同一演示文稿中的某个对象，否则链接将保存为 NoAction。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| slide | [Slide](../slide) | 目标幻灯片。 |

**返回值：**
Hyperlink


---


### Hyperlink {#Hyperlink}

| 名称 | 描述 |
| --- | --- |
| Hyperlink([Hyperlink](../hyperlink), String, String, boolean, boolean, boolean) | 使用另一个超链接作为来源创建超链接实例，覆盖次要属性。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| source | [Hyperlink](../hyperlink) | 源超链接 |
| targetFrame | String | 目标框架 |
| tooltip | String | 工具提示文本 |
| history | boolean | 确定在调用父超链接时，是否将其目标添加到已查看超链接的列表中。 |
| stopSoundsOnClick | boolean | 确定在点击超链接时是否应停止声音。 |
| highlightClick | boolean | 确定在点击时是否应突出显示超链接。 |

**返回值：**
Hyperlink


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals (Object) | 确定两个 Hyperlink 实例是否相等。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| obj | Object | 用于与当前 Hyperlink 比较的 Hyperlink。 |

**返回值：**
boolean


---


### equals {#equals}

| 名称 | 描述 |
| --- | --- |
| equals ([Hyperlink](../hyperlink)) | 确定两个 Hyperlink 实例是否相等。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| hlink | [Hyperlink](../hyperlink) | 用于与当前 Hyperlink 比较的 Hyperlink。 |

**返回值：**
boolean


---


### getActionType {#getActionType}

| 名称 | 描述 |
| --- | --- |
| getActionType () | 返回 Hyperlink 操作的类型。只读 HyperlinkActionType。 |

**返回值：**
int


---


### getColorSource {#getColorSource}

| 名称 | 描述 |
| --- | --- |
| getColorSource () | 表示超链接颜色的来源——样式或段落格式。读写 HyperlinkColorSource。 |

**返回值：**
int


---


### getEndShow {#getEndShow}

| 名称 | 描述 |
| --- | --- |
| getEndShow () | 返回结束演示的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getExternalUrl {#getExternalUrl}

| 名称 | 描述 |
| --- | --- |
| getExternalUrl () | 指定外部 URL。只读 String。 |

**返回值：**
String


---


### getExternalUrlOriginal {#getExternalUrlOriginal}

| 名称 | 描述 |
| --- | --- |
| getExternalUrlOriginal () | 表示为此段落设置的超链接，而不考虑段落的实际内容。PowerPoint 对链接及其对应的段落文本有特殊行为。它允许以有效 URL 的形式为超链接创建文本，该文本与链接的真实地址不同。在这种情况下，当在编辑窗口中查看链接时，它将被更改以匹配文本段落。此属性表示超链接的原始值。 |

**返回值：**
String


---


### getFirstSlide {#getFirstSlide}

| 名称 | 描述 |
| --- | --- |
| getFirstSlide () | 返回指向演示文稿第一张幻灯片的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getHighlightClick {#getHighlightClick}

| 名称 | 描述 |
| --- | --- |
| getHighlightClick () | 确定在点击时是否应突出显示超链接。读写 boolean。 |

**返回值：**
boolean


---


### getHistory {#getHistory}

| 名称 | 描述 |
| --- | --- |
| getHistory () | 确定在调用父超链接时，是否将其目标添加到已查看超链接的列表中。读写 boolean。 |

**返回值：**
boolean


---


### getLastSlide {#getLastSlide}

| 名称 | 描述 |
| --- | --- |
| getLastSlide () | 返回指向演示文稿最后一张幻灯片的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getLastVievedSlide {#getLastVievedSlide}

| 名称 | 描述 |
| --- | --- |
| getLastVievedSlide () | 返回指向最后一次查看的幻灯片的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getMedia {#getMedia}

| 名称 | 描述 |
| --- | --- |
| getMedia () | 返回一个特殊的“播放媒体文件”超链接。用于 AudioFrame 和 VideoFrame。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getNextSlide {#getNextSlide}

| 名称 | 描述 |
| --- | --- |
| getNextSlide () | 返回指向下一张幻灯片的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getNoAction {#getNoAction}

| 名称 | 描述 |
| --- | --- |
| getNoAction () | 返回一个特殊的“什么也不做”超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getPreviousSlide {#getPreviousSlide}

| 名称 | 描述 |
| --- | --- |
| getPreviousSlide () | 返回指向上一张幻灯片的超链接。只读 Hyperlink。 |

**返回值：**
Hyperlink


---


### getSound {#getSound}

| 名称 | 描述 |
| --- | --- |
| getSound () | 表示超链接的播放声音。读写 IAudio。 |

**返回值：**
[Audio](../audio)


---


### getStopSoundOnClick {#getStopSoundOnClick}

| 名称 | 描述 |
| --- | --- |
| getStopSoundOnClick () | 确定在点击超链接时是否应停止声音。读写 boolean。 |

**返回值：**
boolean


---


### getTargetFrame {#getTargetFrame}

| 名称 | 描述 |
| --- | --- |
| getTargetFrame () | 返回父 HTML 框架集中父超链接目标所在的框架（如果存在）。读写 String。 |

**返回值：**
String


---


### getTargetSlide {#getTargetSlide}

| 名称 | 描述 |
| --- | --- |
| getTargetSlide () | 如果 Hyperlink 指向特定幻灯片，则返回该幻灯片。只读 ISlide。 |

**返回值：**
[Slide](../slide)


---


### getTooltip {#getTooltip}

| 名称 | 描述 |
| --- | --- |
| getTooltip () | 返回可能在用户界面中显示的、与父超链接关联的字符串。读写 String。 |

**返回值：**
String


---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

**返回值：**
long


---


### hashCode {#hashCode}

| 名称 | 描述 |
| --- | --- |
| hashCode () | 作为特定类型的哈希函数，适用于哈希算法和如散列表等数据结构。 |

**返回值：**
int


---


### op_Equality {#op_Equality}

| 名称 | 描述 |
| --- | --- |
| op_Equality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | 测试两个超链接是否相等。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | 要测试的第一个超链接。 |
| hlink2 | [Hyperlink](../hyperlink) | 要测试的第二个超链接。 |

**返回值：**
boolean


---


### op_Inequality {#op_Inequality}

| 名称 | 描述 |
| --- | --- |
| op_Inequality ([Hyperlink](../hyperlink), [Hyperlink](../hyperlink)) | 测试两个超链接是否不相等。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| hlink1 | [Hyperlink](../hyperlink) | 要测试的第一个超链接。 |
| hlink2 | [Hyperlink](../hyperlink) | 要测试的第二个超链接。 |

**返回值：**
boolean


---


### setColorSource {#setColorSource}

| 名称 | 描述 |
| --- | --- |
| setColorSource (int) | 表示超链接颜色的来源——样式或段落格式。读写 HyperlinkColorSource。 |

**返回值：**
void


---


### setHighlightClick {#setHighlightClick}

| 名称 | 描述 |
| --- | --- |
| setHighlightClick (boolean) | 确定在点击时是否应突出显示超链接。读写 boolean。 |

**返回值：**
void


---


### setHistory {#setHistory}

| 名称 | 描述 |
| --- | --- |
| setHistory (boolean) | 确定在调用父超链接时，是否将其目标添加到已查看超链接的列表中。读写 boolean。 |

**返回值：**
void


---


### setSound {#setSound}

| 名称 | 描述 |
| --- | --- |
| setSound ([Audio](../audio)) | 表示超链接的播放声音。读写 IAudio。 |

**返回值：**
void


---


### setStopSoundOnClick {#setStopSoundOnClick}

| 名称 | 描述 |
| --- | --- |
| setStopSoundOnClick (boolean) | 确定在点击超链接时是否应停止声音。读写 boolean。 |

**返回值：**
void


---


### setTargetFrame {#setTargetFrame}

| 名称 | 描述 |
| --- | --- |
| setTargetFrame (String) | 设置父 HTML 框架集中父超链接目标所在的框架（如果存在）。读写 String。 |

**返回值：**
void


---


### setTooltip {#setTooltip}

| 名称 | 描述 |
| --- | --- |
| setTooltip (String) | 设置可能在用户界面中显示的、与父超链接关联的字符串。读写 String。 |

**返回值：**
void


---