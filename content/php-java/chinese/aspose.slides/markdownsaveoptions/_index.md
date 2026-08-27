---
title: MarkdownSaveOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/markdownsaveoptions/
---
## MarkdownSaveOptions 类

 表示控制演示文稿保存为 Markdown 的选项。

### MarkdownSaveOptions {#MarkdownSaveOptions}

| 名称 | 描述 |
| --- | --- |
| MarkdownSaveOptions() | 构造函数。 |

**返回值：**
MarkdownSaveOptions


---


### getBasePath {#getBasePath}

| 名称 | 描述 |
| --- | --- |
| getBasePath () | 指定保存带资源的文档的基础路径。默认是应用程序的当前目录。 |

**返回值：**
String


---


### getExportType {#getExportType}

| 名称 | 描述 |
| --- | --- |
| getExportType () | 指定用于转换演示文稿的 Markdown 规范。默认是 TextOnly。 |

**返回值：**
int


---


### getFlavor {#getFlavor}

| 名称 | 描述 |
| --- | --- |
| getFlavor () | 指定用于转换演示文稿的 Markdown 规范。默认是 Multi-markdown。 |

**返回值：**
int


---


### getHandleRepeatedSpaces {#getHandleRepeatedSpaces}

| 名称 | 描述 |
| --- | --- |
| getHandleRepeatedSpaces () | 指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格是：- 保持为普通空格字符，- 在普通空格和不间断空格实体 (&nbsp;) 之间交替，- 或在第一个空格之后全部替换为不间断空格，以在 Markdown 输出中保留视觉对齐。默认值为 HandleRepeatedSpaces#AlternateSpacesToNbsp。 |

**返回值：**
int


---


### getImagesSaveFolderName {#getImagesSaveFolderName}

| 名称 | 描述 |
| --- | --- |
| getImagesSaveFolderName () | 指定用于保存图像的文件夹名称。默认是 Images。 |

**返回值：**
String


---


### getNewLineType {#getNewLineType}

| 名称 | 描述 |
| --- | --- |
| getNewLineType () | 指定生成的文档应使用 \\r（Macintosh）还是 \\n（Unix）或 \\r\\n（Windows）作为换行符。默认是 Unix。 |

**返回值：**
int


---


### getRemoveEmptyLines {#getRemoveEmptyLines}

| 名称 | 描述 |
| --- | --- |
| getRemoveEmptyLines () | 若设置为 true，则从最终的 Markdown 输出中移除空行或仅包含空白的行。默认是 false。 |

**返回值：**
boolean


---


### getShowComments {#getShowComments}

| 名称 | 描述 |
| --- | --- |
| getShowComments () | 指定生成的文档是否显示注释。默认是 false。 |

**返回值：**
boolean


---


### getShowHiddenSlides {#getShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| getShowHiddenSlides () | 指定生成的文档是否包含隐藏的幻灯片。默认是 false。 |

**返回值：**
boolean


---


### getShowSlideNumber {#getShowSlideNumber}

| 名称 | 描述 |
| --- | --- |
| getShowSlideNumber () | 指定生成的文档是否显示每张幻灯片的编号。默认是 false。 |

**返回值：**
boolean


---


### getSlideNumberFormat {#getSlideNumberFormat}

| 名称 | 描述 |
| --- | --- |
| getSlideNumberFormat () | 获取或设置在 Markdown 输出中用于幻灯片编号标题的格式字符串。格式必须包含 “{0}” 占位符，在导出时将被幻灯片索引替换。例如：“# Slide {0}” 将生成 “# Slide 1”, “# Slide 2” 等。 |

**返回值：**
String

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果格式字符串不包含 “{0}” 占位符，则抛出。 |


---


### setBasePath {#setBasePath}

| 名称 | 描述 |
| --- | --- |
| setBasePath (String) | 指定保存带资源的文档的基础路径。默认是应用程序的当前目录。 |

**返回值：**
void


---


### setExportType {#setExportType}

| 名称 | 描述 |
| --- | --- |
| setExportType (int) | 指定用于转换演示文稿的 Markdown 规范。默认是 TextOnly。 |

**返回值：**
void


---


### setFlavor {#setFlavor}

| 名称 | 描述 |
| --- | --- |
| setFlavor (int) | 指定用于转换演示文稿的 Markdown 规范。默认是 Multi-markdown。 |

**返回值：**
void


---


### setHandleRepeatedSpaces {#setHandleRepeatedSpaces}

| 名称 | 描述 |
| --- | --- |
| setHandleRepeatedSpaces (int) | 指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格是：- 保持为普通空格字符，- 在普通空格和不间断空格实体 (&nbsp;) 之间交替，- 或在第一个空格之后全部替换为不间断空格，以在 Markdown 输出中保留视觉对齐。默认值为 HandleRepeatedSpaces#AlternateSpacesToNbsp。 |

**返回值：**
void


---


### setImageSaving {#setImageSaving}

| 名称 | 描述 |
| --- | --- |
| setImageSaving ([MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler)) | 对每个非 SVG 图像（位图或元文件）在 Markdown 导出期间触发。允许自定义图像的保存方式和引用方式。若未处理，则图像以相对链接方式本地保存。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownImageSavingHandler](../markdownsaveoptions.markdownimagesavinghandler) | Markdown 图像保存事件。 |

**返回值：**
void


---


### setImagesSaveFolderName {#setImagesSaveFolderName}

| 名称 | 描述 |
| --- | --- |
| setImagesSaveFolderName (String) | 指定用于保存图像的文件夹名称。默认是 Images。 |

**返回值：**
void


---


### setNewLineType {#setNewLineType}

| 名称 | 描述 |
| --- | --- |
| setNewLineType (int) | 指定生成的文档应使用 \\r（Macintosh）还是 \\n（Unix）或 \\r\\n（Windows）作为换行符。默认是 Unix。 |

**返回值：**
void


---


### setRemoveEmptyLines {#setRemoveEmptyLines}

| 名称 | 描述 |
| --- | --- |
| setRemoveEmptyLines (boolean) | 若设置为 true，则从最终的 Markdown 输出中移除空行或仅包含空白的行。默认是 false。 |

**返回值：**
void


---


### setShowComments {#setShowComments}

| 名称 | 描述 |
| --- | --- |
| setShowComments (boolean) | 指定生成的文档是否显示注释。默认是 false。 |

**返回值：**
void


---


### setShowHiddenSlides {#setShowHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| setShowHiddenSlides (boolean) | 指定生成的文档是否包含隐藏的幻灯片。默认是 false。 |

**返回值：**
void


---


### setShowSlideNumber {#setShowSlideNumber}

| 名称 | 描述 |
| --- | --- |
| setShowSlideNumber (boolean) | 指定生成的文档是否显示每张幻灯片的编号。默认是 false。 |

**返回值：**
void


---


### setSlideNumberFormat {#setSlideNumberFormat}

| 名称 | 描述 |
| --- | --- |
| setSlideNumberFormat (String) | 获取或设置在 Markdown 输出中用于幻灯片编号标题的格式字符串。格式必须包含 “{0}” 占位符，在导出时将被幻灯片索引替换。例如：“# Slide {0}” 将生成 “# Slide 1”, “# Slide 2” 等。 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentException | 如果格式字符串不包含 “{0}” 占位符，则抛出。 |


---


### setSvgImageSaving {#setSvgImageSaving}

| 名称 | 描述 |
| --- | --- |
| setSvgImageSaving ([MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler)) | 对每个 SVG 图像在 Markdown 导出期间触发。允许覆盖默认的保存和链接生成方式。若未处理，则 SVG 以相对链接方式本地保存。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownSaveOptions.MarkdownSvgImageSavingHandler](../markdownsaveoptions.markdownsvgimagesavinghandler) | Markdown SVG 图像保存事件。 |

**返回值：**
void


---