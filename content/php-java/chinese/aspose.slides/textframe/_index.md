---
title: TextFrame
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/textframe/
---
## TextFrame 类

  表示一个 TextFrame。
 
### getHyperlinkQueries {#getHyperlinkQueries}

| 名称 | 描述 |
| --- | --- |
| getHyperlinkQueries () | 提供对包含的超链接的便捷访问。只读 IHyperlinkQueries。 |

 **返回值：**
[HyperlinkQueries](../hyperlinkqueries)


---


### getParagraphs {#getParagraphs}

| 名称 | 描述 |
| --- | --- |
| getParagraphs () | 返回框中所有段落的列表。只读 IParagraphCollection。 |

 **返回值：**
[ParagraphCollection](../paragraphcollection)


---


### getParentCell {#getParentCell}

| 名称 | 描述 |
| --- | --- |
| getParentCell () | 返回父单元格，如果父对象未实现 ICell 接口则返回 null。只读 ICell。 |

 **返回值：**
[Cell](../cell)


---


### getParentShape {#getParentShape}

| 名称 | 描述 |
| --- | --- |
| getParentShape () | 返回父形状，如果父对象未实现 IShape 接口则返回 null。只读 IShape。 |

 **返回值：**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 TextFrame 所属的演示文稿。只读 IPresentation。 |

 **返回值：**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 TextFrame 所属的幻灯片。只读 IBaseSlide。 |

 **返回值：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getText {#getText}

| 名称 | 描述 |
| --- | --- |
| getText () | 获取或设置 TextFrame 的纯文本。读/写 String。值：文本。 |

 **返回值：**
String


---


### getTextFrameFormat {#getTextFrameFormat}

| 名称 | 描述 |
| --- | --- |
| getTextFrameFormat () | 返回此 TextFrame 对象的格式化对象。只读 ITextFrameFormat。 |

 **返回值：**
[TextFrameFormat](../textframeformat)


---


### highlightRegex {#highlightRegex}

| 名称 | 描述 |
| --- | --- |
| highlightRegex (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | 使用指定颜色突出显示正则表达式的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| regex | String | 用于获取要突出显示文本的正则表达式文本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| options | [TextHighlightingOptions](../texthighlightingoptions) | 突出显示选项。 |

 **返回值：**
void


---


### highlightRegex {#highlightRegex}

| 名称 | 描述 |
| --- | --- |
| highlightRegex (Pattern, Color, [IFindResultCallback](../ifindresultcallback)) | 使用指定颜色突出显示正则表达式的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| regex | Pattern | 用于获取要突出显示字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

 **返回值：**
void


---


### highlightText {#highlightText}

| 名称 | 描述 |
| --- | --- |
| highlightText (String, Color) | 使用指定颜色突出显示样本文本的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 要突出显示的文本样本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |

 **返回值：**
void


---


### highlightText {#highlightText}

| 名称 | 描述 |
| --- | --- |
| highlightText (String, Color, [TextHighlightingOptions](../texthighlightingoptions)) | 使用指定颜色突出显示样本文本的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 要突出显示的文本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| options | [TextHighlightingOptions](../texthighlightingoptions) | 突出显示选项。 |

 **返回值：**
void


---


### highlightText {#highlightText}

| 名称 | 描述 |
| --- | --- |
| highlightText (String, Color, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | 使用指定颜色突出显示样本文本的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 要突出显示的文本。 |
| highlightColor | Color | 用于突出显示文本的颜色。 |
| options | [TextSearchOptions](../textsearchoptions) | 文本搜索选项 ITextSearchOptions。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 接收搜索结果的回调对象 IFindResultCallback。 |

 **返回值：**
void


---


### joinPortionsWithSameFormatting {#joinPortionsWithSameFormatting}

| 名称 | 描述 |
| --- | --- |
| joinPortionsWithSameFormatting () | 合并所有段落中具有相同格式的运行。 |

 **返回值：**
void


---


### replaceRegex {#replaceRegex}

| 名称 | 描述 |
| --- | --- |
| replaceRegex (Pattern, String, [IFindResultCallback](../ifindresultcallback)) | 使用指定字符串替换正则表达式的所有匹配项。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| regex | Pattern | 用于获取要替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | String | 用于替换所有待替换字符串的字符串。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 保存替换操作结果的回调对象 IFindResultCallback。 |

 **返回值：**
void


---


### replaceText {#replaceText}

| 名称 | 描述 |
| --- | --- |
| replaceText (String, String, [TextSearchOptions](../textsearchoptions), [IFindResultCallback](../ifindresultcallback)) | 将指定文本的所有出现替换为另一个指定文本。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| oldText | String | 要被替换的字符串。 |
| newText | String | 用于替换所有 oldText 出现的字符串。 |
| options | [TextSearchOptions](../textsearchoptions) | 文本搜索选项 ITextSearchOptions。 |
| callback | [IFindResultCallback](../ifindresultcallback) | 保存替换操作结果的回调对象 IFindResultCallback。 |

 **返回值：**
void


---


### setText {#setText}

| 名称 | 描述 |
| --- | --- |
| setText (String) | 获取或设置 TextFrame 的纯文本。读/写 String。值：文本。 |

 **返回值：**
void


---


### splitTextByColumns {#splitTextByColumns}

| 名称 | 描述 |
| --- | --- |
| splitTextByColumns () | 将 ITextFrame 的文本内容拆分为字符串数组，每个元素对应框内的单独文本列。 |

 **返回值：**
String


---