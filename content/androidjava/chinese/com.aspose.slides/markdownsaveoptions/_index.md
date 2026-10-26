---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 表示控制演示文稿如何保存为 markdown 的选项。
type: docs
url: /zh/com.aspose.slides/markdownsaveoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

表示控制演示文稿如何保存为 markdown 的选项。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Ctor. |
## Methods

| Method | Description |
| --- | --- |
| [getExportType()](#getExportType--) | Specifies markdown specification to convert presentation. |
| [setExportType(int value)](#setExportType-int-) | Specifies markdown specification to convert presentation. |
| [getBasePath()](#getBasePath--) | Specifies the base path where document with resources will be saved. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Specifies the base path where document with resources will be saved. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Specifies folder name to save images. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Specifies folder name to save images. |
| [getNewLineType()](#getNewLineType--) | Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Specifies whether the generated document should show comments or not. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Specifies whether the generated document should show comments or not. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Specifies whether the generated document should show number of each slide or not. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Specifies whether the generated document should show number of each slide or not. |
| [getFlavor()](#getFlavor--) | Specifies markdown specification to convert presentation. |
| [setFlavor(int value)](#setFlavor-int-) | Specifies markdown specification to convert presentation. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Gets or sets the format string used for slide number headers in Markdown output. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Gets or sets the format string used for slide number headers in Markdown output. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Specifies how repeated regular space characters should be handled during Markdown export. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Specifies how repeated regular space characters should be handled during Markdown export. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | If set to true, removes empty or whitespace-only lines from the final Markdown output. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | If set to true, removes empty or whitespace-only lines from the final Markdown output. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Occurs for each non-SVG image (bitmap or metafile) during Markdown export. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Occurs for each SVG image during Markdown export. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Ctor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```
Specifies markdown specification to convert presentation. Default is  TextOnly .

**Returns:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```
Specifies markdown specification to convert presentation. Default is  TextOnly .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Specifies the base path where document with resources will be saved. Default is the current directory of the application.

**Returns:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Specifies the base path where document with resources will be saved. Default is the current directory of the application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Specifies folder name to save images. Default is  Images .

**Returns:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Specifies folder name to save images. Default is  Images .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). Default is  Unix .

**Returns:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Specifies whether the generated document should have new lines \\r(Macintosh) of \\n(Unix) or \\r\\n(Windows). Default is  Unix .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Specifies whether the generated document should show comments or not. Default is false.

**Returns:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Specifies whether the generated document should show comments or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Specifies whether the generated document should show number of each slide or not. Default is false.

**Returns:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Specifies whether the generated document should show number of each slide or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Specifies markdown specification to convert presentation. Default is  Multi-markdown .

**Returns:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Specifies markdown specification to convert presentation. Default is  Multi-markdown .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

获取或设置用于 Markdown 输出中幻灯片编号标题的格式字符串。格式必须包含 "\{0\}" 占位符，在导出期间会被幻灯片索引替换。示例："\# Slide \{0\}" 将生成 "\# Slide 1"、"\# Slide 2" 等。

**返回：**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

获取或设置用于 Markdown 输出中幻灯片编号标题的格式字符串。格式必须包含 "\{0\}" 占位符，在导出期间会被幻灯片索引替换。示例："\# Slide \{0\}" 将生成 "\# Slide 1"、"\# Slide 2" 等。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格的处理方式： - 保持为普通空格字符， - 在普通空格和不间断空格实体 (�) 之间交替， - 或在第一个空格之后全部替换为不间断空格，以在 Markdown 输出中保持视觉对齐。默认值为 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces#AlternateSpacesToNbsp)。

**Returns:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格的处理方式：- 保持为普通空格字符，- 在普通空格和不间断空格实体 (�) 之间交替，- 或在第一个空格之后全部替换为不间断空格，以在 Markdown 输出中保持视觉对齐。默认值为 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

如果设置为 true，则从最终的 Markdown 输出中删除空行或仅包含空白的行。默认值为 false。

**Returns:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

如果设置为 true，则从最终的 Markdown 输出中删除空行或仅包含空白的行。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）发生。允许自定义图像的保存方式及引用方式。如果未处理，该图像将以相对链接的方式保存在本地。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown 图像保存事件。 |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)

在 Markdown 导出期间，对每个 SVG 图像都会发生此事件。允许覆盖默认的保存和链接生成。如果未处理，SVG 将以相对链接的方式保存在本地。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG 图像保存事件。 |