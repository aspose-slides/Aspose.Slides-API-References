---
title: ChartTextFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/charttextformat/
---
## ChartTextFormat 类

指定图表文本元素的默认文本格式。

### copyFrom {#copyFrom}

| 名称 | 描述 |
| --- | --- |
| copyFrom ([TextFrame](../textframe)) | 从指定的文本框复制文本格式。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| sourceTextFrame | [TextFrame](../textframe) | 用于复制文本格式的文本框。 |

**返回值：**
void


---

### copyTo {#copyTo}

| 名称 | 描述 |
| --- | --- |
| copyTo ([TextFrame](../textframe)) | 将文本格式复制到指定的文本框。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| destTextFrame | [TextFrame](../textframe) | 要将文本格式复制到的文本框。 |

**返回值：**
void


---

### getParagraphFormat {#getParagraphFormat}

| 名称 | 描述 |
| --- | --- |
| getParagraphFormat () | ParagraphFormat。只读 IChartParagraphFormat。 |

**返回值：**
[ParagraphFormat](../paragraphformat)


---

### getPortionFormat {#getPortionFormat}

| 名称 | 描述 |
| --- | --- |
| getPortionFormat () | PortionFormat。只读 IChartPortionFormat。 |

**返回值：**
[ChartPortionFormat](../chartportionformat)


---

### getTextBlockFormat {#getTextBlockFormat}

| 名称 | 描述 |
| --- | --- |
| getTextBlockFormat () | TextBlockFormat。只读 IChartTextBlockFormat。 |

**返回值：**
[TextFrameFormat](../textframeformat)