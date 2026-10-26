---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Java API 参考
description: 表示控制演示文稿保存为 markdown 的选项。
type: docs
url: /zh/com.aspose.slides/markdownsaveoptions/
---
**继承:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

表示控制演示文稿保存为 markdown 的选项。

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

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | 构造函数. |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getExportType()](#getExportType--) | 指定用于转换演示文稿的 markdown 规范。 |
| [setExportType(int value)](#setExportType-int-) | 指定用于转换演示文稿的 markdown 规范。 |
| [getBasePath()](#getBasePath--) | 指定保存带资源的文档的基本路径。 |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | 指定保存带资源的文档的基本路径。 |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | 指定用于保存图像的文件夹名称。 |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | 指定用于保存图像的文件夹名称。 |
| [getNewLineType()](#getNewLineType--) | 指定生成的文档应使用哪种换行符：\\r（Macintosh）或 \\n（Unix）或 \\r\\n（Windows）。 |
| [setNewLineType(int value)](#setNewLineType-int-) | 指定生成的文档应使用哪种换行符：\\r（Macintosh）或 \\n（Unix）或 \\r\\n（Windows）。 |
| [getShowComments()](#getShowComments--) | 指定生成的文档是否显示评论。 |
| [setShowComments(boolean value)](#setShowComments-boolean-) | 指定生成的文档是否显示评论。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 指定生成的文档是否包含隐藏幻灯片。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 指定生成的文档是否包含隐藏幻灯片。 |
| [getShowSlideNumber()](#getShowSlideNumber--) | 指定生成的文档是否显示每张幻灯片的编号。 |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | 指定生成的文档是否显示每张幻灯片的编号。 |
| [getFlavor()](#getFlavor--) | 指定用于转换演示文稿的 markdown 规范。 |
| [setFlavor(int value)](#setFlavor-int-) | 指定用于转换演示文稿的 markdown 规范。 |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | 获取或设置 Markdown 输出中幻灯片编号标题使用的格式字符串。 |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | 获取或设置 Markdown 输出中幻灯片编号标题使用的格式字符串。 |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | 指定在 Markdown 导出期间如何处理重复的普通空格字符。 |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | 指定在 Markdown 导出期间如何处理重复的普通空格字符。 |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | 如果设置为 true，则从最终的 Markdown 输出中删除空行或仅包含空白的行。 |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | 如果设置为 true，则从最终的 Markdown输出中删除空行或仅包含空白的行。 |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | 在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）触发。 |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | 在 Markdown 导出期间，对每个 SVG 图像触发。 |

### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


构造函数。

### getExportType() {#getExportType--}
```
public final int getExportType()
```


指定用于转换演示文稿的 markdown 规范。默认是 TextOnly .

**返回值:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```


指定用于转换演示文稿的 markdown 规范。默认是 TextOnly .

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```


指定保存带资源的文档的基本路径。默认是应用程序的当前目录。

**返回值:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```


指定保存带资源的文档的基本路径。默认是应用程序的当前目录。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```


指定用于保存图像的文件夹名称。默认是 Images 。

**返回值:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```


指定用于保存图像的文件夹名称。默认是 Images 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```


指定生成的文档应使用哪种换行符：\\r（Macintosh）或 \\n（Unix）或 \\r\\n（Windows）。默认是 Unix 。

**返回值:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```


指定生成的文档应使用哪种换行符：\\r（Macintosh）或 \\n（Unix）或 \\r\\n（Windows）。默认是 Unix 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```


指定生成的文档是否显示评论。默认是 false。

**返回值:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```


指定生成的文档是否显示评论。默认是 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


指定生成的文档是否包含隐藏幻灯片。默认是 false。

**返回值:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


指定生成的文档是否包含隐藏幻灯片。默认是 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```


指定生成的文档是否显示每张幻灯片的编号。默认是 false。

**返回值:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```


指定生成的文档是否显示每张幻灯片的编号。默认是 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```


指定用于转换演示文稿的 markdown 规范。默认是 Multi-markdown 。

**返回值:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```


指定用于转换演示文稿的 markdown 规范。默认是 Multi-markdown 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```


获取或设置 Markdown 输出中幻灯片编号标题使用的格式字符串。该格式必须包含 “\{0\}” 占位符，导出时会被幻灯片索引替换。例如：“\# Slide \{0\}” 将产生 “\# Slide 1”、 “\# Slide 2”等。

**返回值:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```


获取或设置 Markdown 输出中幻灯片编号标题使用的格式字符串。该格式必须包含 “\{0\}” 占位符，导出时会被幻灯片索引替换。例如：“\# Slide \{0\}” 将产生 “\# Slide 1”、 “\# Slide 2”等。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```


指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格是：- 保持为普通空格字符，- 在普通空格和不换行空格实体（�）之间交替，- 或在第一个后全部替换为不换行空格以在 Markdown 输出中保持视觉对齐。默认值是 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)。

**返回值:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```


指定在 Markdown 导出期间如何处理重复的普通空格字符。此属性定义连续空格是：- 保持为普通空格字符，- 在普通空格和不换行空格实体（�）之间交替，- 或在第一个后全部替换为不换行空格以在 Markdown 输出中保持视觉对齐。默认值是 [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```


如果设置为 true，则从最终的 Markdown 输出中删除空行或仅包含空白的行。默认是 false。

**返回值:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```


如果设置为 true，则从最终的 Markdown 输出中删除空行或仅包含空白的行。默认是 false。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```


在 Markdown 导出期间，对每个非 SVG 图像（位图或元文件）触发。允许自定义图像的保存方式和引用方式。如果未处理，则图像以相对链接本地保存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown 图像保存事件。 |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```


在 Markdown 导出期间，对每个 SVG 图像触发。允许覆盖默认的保存和链接生成方式。如果未处理，则 SVG 以相对链接本地保存。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG 图像保存事件。 |