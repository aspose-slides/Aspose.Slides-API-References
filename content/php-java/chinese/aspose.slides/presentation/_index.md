---
title: Presentation
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/presentation/
---
## Presentation 类

  表示一个 Microsoft PowerPoint 演示文稿。
 
### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation() | 此函数从头创建新的演示文稿。创建的演示文稿有一个空白幻灯片。 |

**返回：**
Presentation


---


### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation([LoadOptions](../loadoptions)) | 此函数从头创建新的演示文稿。创建的演示文稿有一个空白幻灯片。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| loadOptions | [LoadOptions](../loadoptions) | 附加的加载选项。 |

**返回：**
Presentation


---


### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation(InputStream) | 此函数是读取现有 Presentation 的主要机制。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 输入流。 |

**返回：**
Presentation


---


### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation(InputStream, [LoadOptions](../loadoptions)) | 此函数是读取现有 Presentation 的主要机制。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 输入流。 |
| loadOptions | [LoadOptions](../loadoptions) | 附加的加载选项。 |

**返回：**
Presentation


---


### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation(String) | 此函数获取用于读取 Presentation 内容的源文件路径。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 输入文件。 |

**返回：**
Presentation

**错误**

| 错误 | 条件 |
| --- | --- |
 | com.aspose.ms.System.ArgumentException | 当输入文件长度为零时抛出 |


---


### Presentation {#Presentation}

| 名称 | 描述 |
| --- | --- |
| Presentation(String, [LoadOptions](../loadoptions)) | 此函数获取用于读取 Presentation 内容的源文件路径。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 输入文件。 |
| loadOptions | [LoadOptions](../loadoptions) | 附加的加载选项。 |

**返回：**
Presentation

**错误**

| 错误 | 条件 |
| --- | --- |
 | ArgumentException | 当输入文件长度为零时抛出 |


---


### dispose {#dispose}

| 名称 | 描述 |
| --- | --- |
| dispose () | 释放此 Presentation 对象使用的所有资源。 |

**返回：**
void


---


### getAllCustomXmlParts {#getAllCustomXmlParts}

| 名称 | 描述 |
| --- | --- |
| getAllCustomXmlParts () | 返回演示文稿中的所有自定义数据部件。只读 ICustomXmlPart[]。 |

**返回：**
[CustomXmlPart](../customxmlpart)


---


### getAudios {#getAudios}

| 名称 | 描述 |
| --- | --- |
| getAudios () | 返回演示文稿中所有嵌入式音频文件的集合。只读 IAudioCollection。 |

**返回：**
[AudioCollection](../audiocollection)


---


### getCommentAuthors {#getCommentAuthors}

| 名称 | 描述 |
| --- | --- |
| getCommentAuthors () | 返回评论作者的集合。只读 ICommentAuthorCollection。 |

**返回：**
[CommentAuthorCollection](../commentauthorcollection)


---


### getCurrentDateTime {#getCurrentDateTime}

| 名称 | 描述 |
| --- | --- |
| getCurrentDateTime () | 返回或设置将替代 datetime 字段内容的日期时间。默认情况下为此 Presentation 对象创建的时间。读/写 java.util.Date。 |

**返回：**
Date


---


### getCustomData {#getCustomData}

| 名称 | 描述 |
| --- | --- |
| getCustomData () | 返回演示文稿的自定义数据。只读 ICustomData。 |

**返回：**
[CustomData](../customdata)


---


### getDefaultTextStyle {#getDefaultTextStyle}

| 名称 | 描述 |
| --- | --- |
| getDefaultTextStyle () | 返回形状的默认文本样式。只读 ITextStyle。 |

**返回：**
[TextStyle](../textstyle)


---


### getDigitalSignatures {#getDigitalSignatures}

| 名称 | 描述 |
| --- | --- |
| getDigitalSignatures () | 返回用于签署演示文稿的签名集合。只读 IDigitalSignatureCollection。 |

**返回：**
[DigitalSignatureCollection](../digitalsignaturecollection)


---


### getDocumentProperties {#getDocumentProperties}

| 名称 | 描述 |
| --- | --- |
| getDocumentProperties () | 返回包含标准和自定义文档属性的 DocumentProperties 对象。只读 IDocumentProperties。 |

**返回：**
[DocumentProperties](../documentproperties)


---


### getFirstSlideNumber {#getFirstSlideNumber}

| 名称 | 描述 |
| --- | --- |
| getFirstSlideNumber () | 表示演示文稿中的第一张幻灯片编号 |

**返回：**
int


---


### getFontsManager {#getFontsManager}

| 名称 | 描述 |
| --- | --- |
| getFontsManager () | 返回字体管理器。只读 IFontsManager。 |

**返回：**
[FontsManager](../fontsmanager)


---


### getHeaderFooterManager {#getHeaderFooterManager}

| 名称 | 描述 |
| --- | --- |
| getHeaderFooterManager () | 返回实际的页眉页脚管理器。只读 IPresentationHeaderFooterManager。 |

**返回：**
[PresentationHeaderFooterManager](../presentationheaderfootermanager)


---


### getHyperlinkQueries {#getHyperlinkQueries}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkQueries () | 提供对所有演示文稿幻灯片中（不包括母版、版式、备注幻灯片）包含的超链接的便捷访问。只读 IHyperlinkQueries。 |

**返回：**
[HyperlinkQueries](../hyperlinkqueries)


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages () | 返回演示文稿中所有图像的集合。只读 IImageCollection。 |

**返回：**
[ImageCollection](../imagecollection)


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions)) | 为演示文稿的所有幻灯片返回 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |

**返回：**
IImage


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[]) | 为演示文稿中指定的幻灯片返回缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |

**返回：**
IImage


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), float, float) | 为演示文稿中所有幻灯片返回自定义缩放的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
IImage


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], float, float) | 为演示文稿中指定的幻灯片返回自定义缩放的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| scaleX | float | 在 x 轴方向上缩放此缩略图的值。 |
| scaleY | float | 在 y 轴方向上缩放此缩略图的值。 |

**返回：**
IImage


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), Dimension) | 为演示文稿中所有幻灯片返回指定尺寸的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |
| imageSize | Dimension | 要创建的图像尺寸。 |

**返回：**
IImage


---


### getImages {#getImages}

| 名称 | 描述 |
| --- | --- |
| getImages ([RenderingOptions](../renderingoptions), int[], Dimension) | 为演示文稿中指定的幻灯片返回指定尺寸的缩略图 Image 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [RenderingOptions](../renderingoptions) | Tiff 选项。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| imageSize | Dimension | 要创建的图像尺寸。 |

**返回：**
IImage


---


### getLayoutSlides {#getLayoutSlides}

| 名称 | 描述 |
| --- | --- |
| getLayoutSlides () | 返回演示文稿中定义的所有版式幻灯片的列表。只读 IGlobalLayoutSlideCollection。您可以通过使用 IMasterSlide.LayoutSlides 属性访问用于添加/插入/删除/克隆版式幻灯片的替代 API。 |

**返回：**
[GlobalLayoutSlideCollection](../globallayoutslidecollection)


---


### getMasterHandoutSlideManager {#getMasterHandoutSlideManager}

| 名称 | 描述 |
| --- | --- |
| getMasterHandoutSlideManager () | 返回讲义母版管理器。只读 IMasterHandoutSlideManager。 |

**返回：**
MasterHandoutSlideManager


---


### getMasterNotesSlideManager {#getMasterNotesSlideManager}

| 名称 | 描述 |
| --- | --- |
| getMasterNotesSlideManager () | 返回备注母版管理器。只读 IMasterNotesSlideManager。 |

**返回：**
MasterNotesSlideManager


---


### getMasterTheme {#getMasterTheme}

| 名称 | 描述 |
| --- | --- |
| getMasterTheme () | 返回母版主题。只读 IMasterTheme。 |

**返回：**
[MasterTheme](../mastertheme)


---


### getMasters {#getMasters}

| 名称 | 描述 |
| --- | --- |
| getMasters () | 返回演示文稿中定义的所有母版幻灯片的列表。只读 IMasterSlideCollection。 |

**返回：**
[MasterSlideCollection](../masterslidecollection)


---


### getNotesSize {#getNotesSize}

| 名称 | 描述 |
| --- | --- |
| getNotesSize () | 返回备注幻灯片大小对象。只读 INotesSize。 |

**返回：**
[NotesSize](../notessize)


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回文本所属的父演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)


---


### getProtectionManager {#getProtectionManager}

| 名称 | 描述 |
| --- | --- |
| getProtectionManager () | 获取此演示文稿权限的管理器。只读 IProtectionManager。 |

**返回：**
[ProtectionManager](../protectionmanager)


---


### getSections {#getSections}

| 名称 | 描述 |
| --- | --- |
| getSections () | 返回演示文稿中定义的所有幻灯片分区的列表。只读 ISectionCollection。 |

**返回：**
[SectionCollection](../sectioncollection)


---


### getSensitivityLabels {#getSensitivityLabels}

| 名称 | 描述 |
| --- | --- |
| getSensitivityLabels () | 返回应用于演示文稿文档的敏感度标签集合。只读 ISensitivityLabelCollection。 |

**返回：**
[SensitivityLabelCollection](../sensitivitylabelcollection)


---


### getSlideById {#getSlideById}

| 名称 | 描述 |
| --- | --- |
| getSlideById (long) | 根据 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| id | long | 幻灯片的 Id。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getSlideShowSettings {#getSlideShowSettings}

| 名称 | 描述 |
| --- | --- |
| getSlideShowSettings () | 返回演示文稿的幻灯片放映设置。 |

**返回：**
SlideShowSettings


---


### getSlideSize {#getSlideSize}

| 名称 | 描述 |
| --- | --- |
| getSlideSize () | 返回幻灯片大小对象。只读 ISlideSize。 |

**返回：**
[SlideSize](../slidesize)


---


### getSlides {#getSlides}

| 名称 | 描述 |
| --- | --- |
| getSlides () | 返回演示文稿中定义的所有幻灯片的列表。只读 ISlideCollection。 |

**返回：**
[SlideCollection](../slidecollection)


---


### getSourceFormat {#getSourceFormat}

| 名称 | 描述 |
| --- | --- |
| getSourceFormat () | 返回有关演示文稿加载来源格式的信息。只读 SourceFormat。 |

**返回：**
int


---


### getVbaProject {#getVbaProject}

| 名称 | 描述 |
| --- | --- |
| getVbaProject () | 获取或设置包含演示文稿宏的 VBA 项目。读/写 IVbaProject。 |

**返回：**
[VbaProject](../vbaproject)


---


### getVideos {#getVideos}

| 名称 | 描述 |
| --- | --- |
| getVideos () | 返回演示文稿中所有嵌入式视频文件的集合。只读 IVideoCollection. |

**返回:**  
[VideoCollection](../videocollection)

---

### getViewProperties {#getViewProperties}

| Name | Description |
| --- | --- |
| getViewProperties () | 获取演示文稿范围的视图属性。只读 IViewProperties. |

**返回:**  
[ViewProperties](../viewproperties)

---

### highlightRegex {#highlightRegex}

| Name | Description |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | 使用指定颜色突出显示正则表达式的所有匹配项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | 用于获取要突出显示的字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

**返回:**  
void

---

### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color) | 使用指定颜色突出显示样本文本的所有匹配项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | 要突出显示的文本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |

**返回:**  
void

---

### highlightText {#highlightText}

| Name | Description |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | 使用指定颜色突出显示样本文本的所有匹配项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | 要突出显示的文本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| options | [TextSearchOptions](../textsearchoptions) | 文本搜索选项 ITextSearchOptions。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

**返回:**  
void

---

### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| Name | Description |
| --- | --- |
| joinPortionsWithSameFormatting () | 在所有幻灯片的所有可接受形状的所有段落中，合并具有相同格式的文本段。 |

**返回:**  
void

---

### replaceRegex {#replaceRegex}

| Name | Description |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | 使用指定的字符串替换正则表达式的所有匹配项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| regex | Pattern | 用于获取要替换的字符串的正则表达式 java.util.regex.Pattern。 |
| newText | String | 用于替换所有待替换字符串出现位置的字符串。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

**返回:**  
void

---

### replaceText {#replaceText}

| Name | Description |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | 将指定文本的所有出现位置替换为另一个指定文本。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| oldText | String | 要被替换的字符串。 |
| newText | String | 用于替换 oldText 所有出现位置的字符串。 |
| options | [TextSearchOptions](../textsearchoptions) | 文本搜索选项 ITextSearchOptions。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int) | 将演示文稿的所有幻灯片保存为指定格式的文件。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int) | 将演示文稿的所有幻灯片保存到指定格式的流中。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [RenderingOptions](../renderingoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [RenderingOptions](../renderingoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PptOptions](../pptoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [PptOptions](../pptoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [XamlOptions](../xamloptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [XamlOptions](../xamloptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [SVGOptions](../svgoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [SVGOptions](../svgoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [MarkdownSaveOptions](../markdownsaveoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [HtmlOptions](../htmloptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [HtmlOptions](../htmloptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PdfOptions](../pdfoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [PdfOptions](../pdfoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [SwfOptions](../swfoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [SwfOptions](../swfoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [TiffOptions](../tiffoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [TiffOptions](../tiffoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [Html5Options](../html5options)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [Html5Options](../html5options) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [XpsOptions](../xpsoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [XpsOptions](../xpsoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [SaveOptions](../saveoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [SaveOptions](../saveoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [GifOptions](../gifoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [GifOptions](../gifoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (String, int, [PptxOptions](../pptxoptions)) | 将演示文稿的所有幻灯片保存为指定格式的文件，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| format | int | 导出数据的格式。 |
| options | [PptxOptions](../pptxoptions) | 附加的格式选项。 |

**返回:**  
void

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [RenderingOptions](../renderingoptions)) | 将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [RenderingOptions](../renderingoptions) | 附加的格式选项。 |

**返回:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试在非 Office 2007-2010 格式下保存加密文件 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [PptOptions](../pptoptions)) | 将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [PptOptions](../pptoptions) | 附加的格式选项。 |

**返回:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试在非 Office 2007-2010 格式下保存加密文件 |

---

### save {#save}

| Name | Description |
| --- | --- |
| save (OutputStream, int, [XamlOptions](../xamloptions)) | 将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加的格式选项。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [XamlOptions](../xamloptions) | 附加的格式选项。 |

**返回:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试在非 Office 2007-2010 格式下保存加密文件 |

---
| save (OutputStream, int, [SVGOptions](../svgoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [SVGOptions](../svgoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [MarkdownSaveOptions](../markdownsaveoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [HtmlOptions](../htmloptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [HtmlOptions](../htmloptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [PdfOptions](../pdfoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [PdfOptions](../pdfoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [SwfOptions](../swfoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [SwfOptions](../swfoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [TiffOptions](../tiffoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [TiffOptions](../tiffoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [Html5Options](../html5options)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [Html5Options](../html5options) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [XpsOptions](../xpsoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [XpsOptions](../xpsoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [SaveOptions](../saveoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [SaveOptions](../saveoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [GifOptions](../gifoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [GifOptions](../gifoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int, [PptxOptions](../pptxoptions)) | 将演示文稿的所有幻灯片保存到流中，使用指定的格式并附加选项。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| format | int | 导出数据的格式。 |
| options | [PptxOptions](../pptxoptions) | 附加的格式选项。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| NotSupportedException | 如果尝试以非 Office 2007-2010 格式保存加密文件 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save ([XamlOptions](../xamloptions)) | 将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [XamlOptions](../xamloptions) | XAML 格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |

**返回值:**  
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [RenderingOptions](../renderingoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [RenderingOptions](../renderingoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [PptOptions](../pptoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [PptOptions](../pptoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [XamlOptions](../xamloptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [XamlOptions](../xamloptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [SVGOptions](../svgoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SVGOptions](../svgoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [HtmlOptions](../htmloptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [HtmlOptions](../htmloptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [PdfOptions](../pdfoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [PdfOptions](../pdfoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [SwfOptions](../swfoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SwfOptions](../swfoptions) | 附加的格式选项。 |

**返回值:**  
void

---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [TiffOptions](../tiffoptions)) | 将演示文稿的指定幻灯片保存到文件，使用指定的格式并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 创建的文件路径。 |
| slides | int[] | 幻灯片位置数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [TiffOptions](../tiffoptions) | 附加的格式选项。 |

**返回值:**  
void
| save (String, int[], int, [Html5Options](../html5options)) | 将演示文稿中指定的幻灯片保存到具有指定格式的文件中，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 已创建文件的路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [Html5Options](../html5options) | 附加格式选项。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [XpsOptions](../xpsoptions)) | 将演示文稿中指定的幻灯片保存到具有指定格式的文件中，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 已创建文件的路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [XpsOptions](../xpsoptions) | 附加格式选项。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [SaveOptions](../saveoptions)) | 将演示文稿中指定的幻灯片保存到具有指定格式的文件中，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 已创建文件的路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SaveOptions](../saveoptions) | 附加格式选项。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [GifOptions](../gifoptions)) | 将演示文稿中指定的幻灯片保存到具有指定格式的文件中，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 已创建文件的路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [GifOptions](../gifoptions) | 附加格式选项。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (String, int[], int, [PptxOptions](../pptxoptions)) | 将演示文稿中指定的幻灯片保存到具有指定格式的文件中，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| fname | String | 已创建文件的路径。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [PptxOptions](../pptxoptions) | 附加格式选项。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |

**返回:**
void


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [RenderingOptions](../renderingoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [RenderingOptions](../renderingoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [PptOptions](../pptoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [PptOptions](../pptoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [XamlOptions](../xamloptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [XamlOptions](../xamloptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [SVGOptions](../svgoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SVGOptions](../svgoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [MarkdownSaveOptions](../markdownsaveoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [MarkdownSaveOptions](../markdownsaveoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [HtmlOptions](../htmloptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [HtmlOptions](../htmloptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [PdfOptions](../pdfoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [PdfOptions](../pdfoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [SwfOptions](../swfoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SwfOptions](../swfoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [TiffOptions](../tiffoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [TiffOptions](../tiffoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [Html5Options](../html5options)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [Html5Options](../html5options) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [XpsOptions](../xpsoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [XpsOptions](../xpsoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [SaveOptions](../saveoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [SaveOptions](../saveoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, [GifOptions](../gifoptions)) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | [GifOptions](../gifoptions) | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |


---


### save {#save}

| 名称 | 描述 |
| --- | --- |
| save (OutputStream, int[], int, {{L...}}) | 将演示文稿中指定的幻灯片保存到流中，以指定格式，并保留页码。 |

**参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始编号为 1。 |
| format | int | 导出数据的格式。 |
| options | {{L...}} | 附加格式选项。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |
| save (OutputStream, int[], int, [PptxOptions](../pptxoptions)) | 将演示文稿的指定幻灯片保存到流中，使用指定格式并保持页码。 |

**Parameters:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 输出流。 |
| slides | int[] | 包含幻灯片位置的数组，起始值为1。 |
| format | int | 导出数据的格式。 |
| options | [PptxOptions](../pptxoptions) | 附加的格式选项。 |

**Returns:**
void

**Exception**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 当使用不受支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

---

### setCurrentDateTime {#setCurrentDateTime}

| 名称 | 描述 |
| --- | --- |
| setCurrentDateTime (Date) | 返回或设置日期和时间，以替代 datetime 字段的内容。默认情况下为此 Presentation 对象创建的时间。读/写 java.util.Date。 |

**Returns:**
void

---

### setFirstSlideNumber {#setFirstSlideNumber}

| 名称 | 描述 |
| --- | --- |
| setFirstSlideNumber (int) | 表示演示文稿中的第一张幻灯片编号 |

**Returns:**
void

---

### setVbaProject {#setVbaProject}

| 名称 | 描述 |
| --- | --- |
| setVbaProject ([VbaProject](../vbaproject)) | 获取或设置包含演示文稿宏的 VBA 项目。读/写 IVbaProject。 |

**Returns:**
void

---