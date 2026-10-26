---
title: HtmlGenerator
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/htmlgenerator/
---
## HtmlGenerator 类

 Html 生成器。
 
### addAttributeValue {#addAttributeValue}

| Name | Description |
| --- | --- |
| addAttributeValue (String) | 对属性值加引号并将其添加到 html 文件。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | String | 属性值字符串。 |

 **返回值：**
void


---


### addAttributeValue {#addAttributeValue}

| Name | Description |
| --- | --- |
| addAttributeValue (char[]) | 对属性值加引号并将其添加到 html 文件。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |

 **返回值：**
void


---


### addAttributeValue {#addAttributeValue}

| Name | Description |
| --- | --- |
| addAttributeValue (char[], int, int) | 对属性值加引号并将其添加到 html 文件。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

 **返回值：**
void


---


### addHtml {#addHtml}

| Name | Description |
| --- | --- |
| addHtml (String) | 添加格式化的 HTML 文本。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| html | String | 要添加的文本。 |

 **返回值：**
void


---


### addHtml {#addHtml}

| Name | Description |
| --- | --- |
| addHtml (char[]) | 添加格式化的 HTML 文本。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |

 **返回值：**
void


---


### addHtml {#addHtml}

| Name | Description |
| --- | --- |
| addHtml (char[], int, int) | 添加格式化的 HTML 文本。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

 **返回值：**
void


---


### addText {#addText}

| Name | Description |
| --- | --- |
| addText (String) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不被替换。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| text | String | 要添加的文本。 |

 **返回值：**
void


---


### addText {#addText}

| Name | Description |
| --- | --- |
| addText (char[]) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不被替换。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |

 **返回值：**
void


---


### addText {#addText}

| Name | Description |
| --- | --- |
| addText (char[], int, int) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不被替换。 |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

 **返回值：**
void


---


### getNextSlideIndex {#getNextSlideIndex}

| Name | Description |
| --- | --- |
| getNextSlideIndex () | 返回将在当前幻灯片之后渲染的幻灯片索引，如果当前渲染的是最后一张幻灯片则返回 -1。只读 int。 |

 **返回值：**
int


---


### getPreviousSlideIndex {#getPreviousSlideIndex}

| Name | Description |
| --- | --- |
| getPreviousSlideIndex () | 返回先前渲染的幻灯片索引，如果是第一张幻灯片正在渲染则返回 -1。只读 int。 |

 **返回值：**
int


---


### getSlideImageSize {#getSlideImageSize}

| Name | Description |
| --- | --- |
| getSlideImageSize () | 返回幻灯片图像大小。只读 java.awt.geom.Dimension2D。 |

 **返回值：**
Dimension2D


---


### getSlideImageSizeUnit {#getSlideImageSizeUnit}

| Name | Description |
| --- | --- |
| getSlideImageSizeUnit () | 返回指定幻灯片图像大小的单位。只读 SvgCoordinateUnit。 |

 **返回值：**
int


---


### getSlideImageSizeUnitCode {#getSlideImageSizeUnitCode}

| Name | Description |
| --- | --- |
| getSlideImageSizeUnitCode () | 返回指定幻灯片图像大小的单位的 CSS 代码。只读 String。 |

 **返回值：**
String


---


### getSlideIndex {#getSlideIndex}

| Name | Description |
| --- | --- |
| getSlideIndex () | 返回当前渲染的幻灯片索引。只读 int。 |

 **返回值：**
int


---